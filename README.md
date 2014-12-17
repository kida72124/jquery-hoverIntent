jQuery 本身提供了很方便的 .hover() 事件來讓我們設計出滑鼠的移入/出動作；但有時是希望當使用者移入/出經過多久時間後才執行指定的動作，此時就得自己在加入計時器來控制了。
而 hoverIntent 則是幫我們擴充了原有的 .hover() 功能，讓設計者能用參數的方式來設定移入/出的延遲時間。

hoverIntent jQuery Plug-in
==========================

hoverIntent is a plug-in that attempts to determine the user's intent... like a crystal ball, only with mouse movement! It is similar to [jQuery's hover method](http://api.jquery.com/hover/). However, instead of calling the handlerIn function immediately, hoverIntent waits until the user's mouse slows down enough before making the call.

Why? To delay or prevent the accidental firing of animations or ajax calls. Simple timeouts work for small areas, but if your target area is large it may execute regardless of intent. That's where hoverIntent comes in...

For more information, visit [http://cherne.net/brian/resources/jquery.hoverIntent.html](http://cherne.net/brian/resources/jquery.hoverIntent.html)
