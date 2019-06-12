# 环境配置

假设你已经配置好了```DuiLib```环境。

# 快速开始

## 编写```xml```文件

在项目目录添加文件```main.xml```，内容如下：

```xml
<?xml version="1.0" encoding="utf-8" standalone="yes" ?>
<Window size="800,600" caption="0,0,0,32" roundcorner="4,4">
  <Default name="VScrollBar" shared="true" value="button1normalimage=&quot;file='skin/scrollbar.bmp' source='0,90,16,106' mask='#FFFF00FF'&quot; button1hotimage=&quot;file='skin/scrollbar.bmp' source='18,90,34,106' mask='#FFFF00FF'&quot; button1pushedimage=&quot;file='skin/scrollbar.bmp' source='36,90,52,106' mask='#FFFF00FF'&quot; button1disabledimage=&quot;file='skin/scrollbar.bmp' source='54,90,70,106' mask='#FFFF00FF'&quot; button2normalimage=&quot;file='skin/scrollbar.bmp' source='0,108,16,124' mask='#FFFF00FF'&quot; button2hotimage=&quot;file='skin/scrollbar.bmp' source='18,108,34,124' mask='#FFFF00FF'&quot; button2pushedimage=&quot;file='skin/scrollbar.bmp' source='36,108,52,124' mask='#FFFF00FF'&quot; button2disabledimage=&quot;file='skin/scrollbar.bmp' source='54,108,70,124' mask='#FFFF00FF'&quot; thumbnormalimage=&quot;file='skin/scrollbar.bmp' source='0,126,16,142' corner='2,2,2,2' mask='#FFFF00FF'&quot; thumbhotimage=&quot;file='skin/scrollbar.bmp' source='18,126,34,142' corner='2,2,2,2' mask='#FFFF00FF'&quot; thumbpushedimage=&quot;file='skin/scrollbar.bmp' source='36,126,52,142' corner='2,2,2,2' mask='#FFFF00FF'&quot; thumbdisabledimage=&quot;file='skin/scrollbar.bmp' source='54,126,70,142' corner='2,2,2,2' mask='#FFFF00FF'&quot; railnormalimage=&quot;file='skin/scrollbar.bmp' source='0,144,16,160' corner='2,2,2,2' mask='#FFFF00FF'&quot; railhotimage=&quot;file='skin/scrollbar.bmp' source='18,144,34,160' corner='2,2,2,2' mask='#FFFF00FF'&quot; railpushedimage=&quot;file='skin/scrollbar.bmp' source='36,144,52,160' corner='2,2,2,2' mask='#FFFF00FF'&quot; raildisabledimage=&quot;file='skin/scrollbar.bmp' source='54,144,70,160' corner='2,2,2,2' mask='#FFFF00FF'&quot; bknormalimage=&quot;file='skin/scrollbar.bmp' source='0,162,16,178' corner='2,2,2,2' mask='#FFFF00FF'&quot; bkhotimage=&quot;file='skin/scrollbar.bmp' source='18,162,34,178' corner='2,2,2,2' mask='#FFFF00FF'&quot; bkpushedimage=&quot;file='skin/scrollbar.bmp' source='36,162,52,178' corner='2,2,2,2' mask='#FFFF00FF'&quot; bkdisabledimage=&quot;file='skin/scrollbar.bmp' source='54,162,70,178' corner='2,2,2,2' mask='#FFFF00FF'&quot; " />
  <Default name="HScrollBar" shared="true" value="button1normalimage=&quot;file='skin/scrollbar.bmp' source='0,0,16,16' mask='#FFFF00FF'&quot; button1hotimage=&quot;file='skin/scrollbar.bmp' source='18,0,34,16' mask='#FFFF00FF'&quot; button1pushedimage=&quot;file='skin/scrollbar.bmp' source='36,0,52,16' mask='#FFFF00FF'&quot; button1disabledimage=&quot;file='skin/scrollbar.bmp' source='54,0,70,16' mask='#FFFF00FF'&quot; button2normalimage=&quot;file='skin/scrollbar.bmp' source='0,18,16,34' mask='#FFFF00FF'&quot; button2hotimage=&quot;file='skin/scrollbar.bmp' source='18,18,34,34' mask='#FFFF00FF'&quot; button2pushedimage=&quot;file='skin/scrollbar.bmp' source='36,18,52,34' mask='#FFFF00FF'&quot; button2disabledimage=&quot;file='skin/scrollbar.bmp' source='54,18,70,34' mask='#FFFF00FF'&quot; thumbnormalimage=&quot;file='skin/scrollbar.bmp' source='0,36,16,52' corner='2,2,2,2' mask='#FFFF00FF'&quot; thumbhotimage=&quot;file='skin/scrollbar.bmp' source='18,36,34,52' corner='2,2,2,2' mask='#FFFF00FF'&quot; thumbpushedimage=&quot;file='skin/scrollbar.bmp' source='36,36,52,52' corner='2,2,2,2' mask='#FFFF00FF'&quot; thumbdisabledimage=&quot;file='skin/scrollbar.bmp' source='54,36,70,52' corner='2,2,2,2' mask='#FFFF00FF'&quot; railnormalimage=&quot;file='skin/scrollbar.bmp' source='0,54,16,70' corner='2,2,2,2' mask='#FFFF00FF'&quot; railhotimage=&quot;file='skin/scrollbar.bmp' source='18,54,34,70' corner='2,2,2,2' mask='#FFFF00FF'&quot; railpushedimage=&quot;file='skin/scrollbar.bmp' source='36,54,52,70' corner='2,2,2,2' mask='#FFFF00FF'&quot; raildisabledimage=&quot;file='skin/scrollbar.bmp' source='54,54,70,70' corner='2,2,2,2' mask='#FFFF00FF'&quot; bknormalimage=&quot;file='skin/scrollbar.bmp' source='0,72,16,88' corner='2,2,2,2' mask='#FFFF00FF'&quot; bkhotimage=&quot;file='skin/scrollbar.bmp' source='18,72,34,88' corner='2,2,2,2' mask='#FFFF00FF'&quot; bkpushedimage=&quot;file='skin/scrollbar.bmp' source='36,72,52,88' corner='2,2,2,2' mask='#FFFF00FF'&quot; bkdisabledimage=&quot;file='skin/scrollbar.bmp' source='54,72,70,88' corner='2,2,2,2' mask='#FFFF00FF'&quot; " />

  <VerticalLayout bkimage="file='skin/loginbk.bmp' corner='2,32,2,36'">
    <!-- header -->
    <HorizontalLayout height="32">
      <Control width="6" />
      <Container enabled="true" width="16" height="16" padding="0,8,0,0" bkimage="skin\icon.png" />
      <Label text="CMiniblink" textcolor="0xFFFFFFFF" textpadding="5,5,5,5"></Label>
      <Control />
      <Button name="closebtn" padding="0,1,1,0" width="30" height="30" normalimage="file='skin/closem.png' source='0,0,30,30'" hotimage="file='skin/closem.png' source='0,30,30,60'" pushedimage="file='skin/closem.png' source='0,60,30,90'"></Button>
    </HorizontalLayout>
    <HorizontalLayout>
      <miniblink name="login_browser" url="about:blank" padding="0,0,5,0"></miniblink>
    </HorizontalLayout>
    <HorizontalLayout height="36">
      <Label text="CMiniblink" textcolor="0xFF0000FF" textpadding="5,5,5,5"></Label>
    </HorizontalLayout>
  </VerticalLayout>

</Window>
```

## 创建窗口类

在项目中创建窗口类```CDuiFrameWnd```，继承自```WindowImplBase```。

由于该控件属于自定义控件，需要添加自定义的```xml```标签解析，在```CDuiFrameWnd```类的```CreateControl```中添加如下代码：
```c++
CControlUI* CDuiFrameWnd::CreateControl(LPCTSTR pstrClass) {
	if (_tcscmp(pstrClass, _T("Miniblink")) == 0)
	{
		DuiLib::CMiniblink *web = new DuiLib::CMiniblink();
		return web;
	}
	return NULL;
}
```

此时，你的窗口中已经能正常浏览网页了。