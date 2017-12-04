<!DOCTYPE html>
<html>
<head>
<script>//5var autoRefresh = setTimeout(function(){ location.reload(); }, 3000);</script>
<meta charset="UTF-8">
<title>FullScale TimeLine - Code</title>
<script src="window.js" type="text/javascript"></script>
<script src="Wheel.js" type="text/javascript"></script>
<script src="Calendar.js" type="text/javascript"></script>
<script src="Calendar.ctx.js" type="text/javascript"></script>
<script src="Calendar.phases.js" type="text/javascript"></script>
<script src="Calendar.events.js" type="text/javascript"></script>
<script src="Calendar.generate.js" type="text/javascript"></script>
<script src="Calendar.expansion.js" type="text/javascript"></script>
<link href="style.css" rel="stylesheet" />
</head>
<body>
<button style="opacity: 0; position: fixed; bottom: 0px; z-index: 1" onclick="window.popup('timelineV7.html', 'Fullscale Timeline', 1024, 576)">Popup</button>
<div id="compact" style="border: 1px solid; position: fixed; bottom: 0px; width: 50%; height: 200px"></div>
</body>
<script>
// Calendar
var timeline1 = new Calendar(document.body, 'year')
var timeline2 = new Calendar(document.getElementById('compact'), 'year')
var timeline3 = new Calendar(document.body, 'year', 0, 50)
//.Streaming().access()
window.onresize()
</script>
</html>