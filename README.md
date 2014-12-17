third-and-long-app
==================

index.html
===========
<!DOCTYPE HTML> 
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
<meta http-equiv="X-Frame-Options" content="deny" />
<title>Third and Long Student Workbook</title>
<!--<link href='css/style.css' rel='stylesheet'/>-->
<link href='css/jquery.mobile-1.2.0.css' rel='stylesheet'/>
<link href='css/Android_Shell.css' rel='stylesheet'/>
<link href="css/popbox.css" type="text/css" rel="stylesheet"/>
<script src="cordova.js" type="text/javascript"></script>
<script src="js/jquery-1.8.2.js" type="text/javascript"></script>
<script src="js/jquery.mobile-1.2.0.js" type="text/javascript"></script>
<script src="js/page_content.js" type="text/javascript"></script>
<script src="js/Shell.js" type="text/javascript"></script>
<script src='js/swipe.js'></script>
<script src='js/iscroll.js'></script>
<script src="js/jquery.iframetracker.js" type="text/javascript"></script>
<!--<script src="pg-plugin-screen-orientation.js"></script>
<script type="text/javascript" charset="utf-8" src="video.js"></script>-->

<style>
*{-webkit-user-select: none;
	-webkit-tap-highlight-color: rgba(0,0,0,0);
	-webkit-touch-callout: none;
}
input, textarea{
	-webkit-user-select: auto;
	-webkit-tap-highlight-color: rgba(0,0,0,0);
	-webkit-touch-callout: inherit;
}
</style>
</head>
<body onResize="setting();">
<div data-role="page" id="pageContainer" style="background:#fff;">
<div class="pageNum">1</div>
<div id="lcpannel_container"></div>
<div id="rspannel_container"></div>
<div id="widget_container"><iframe id="widget_frame" frameborder="0"></iframe><div id="consoleBox"></div><div onClick="closewidget()" id="closewidget"><img src="images/close_btn.png" width="20" height="20"/></div></div>

<div id='slider' class='swipe'>
  <div id="loadpages"></div>
</div>
</div>
</body>
</html> 
