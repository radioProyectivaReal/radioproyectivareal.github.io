---
layout: page
title: "player"
date: 2014-05-29 20:17
comments: true
sharing: true
footer: true
---

<link href="skin/jplayer.blue.monday.css" rel="stylesheet" type="text/css" />
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.jplayer.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){

	$("#jquery_jplayer_1").jPlayer({
		ready: function (event) {
			$(this).jPlayer("setMedia", {
				mp3:"http://rpr.out.airtime.pro:8000/rpr_a"
			});
		},
		swfPath: "js",
		supplied: "mp3",
		wmode: "window",
		smoothPlayBar: true,
		keyEnabled: true
	});
});
</script>

<iframe src="http://localhost:4000/player/track_widget.html">


</iframe>
<div id="jquery_jplayer_1" class="jp-jplayer"></div>
<div id="jp_container_1" class="jp-audio">
  <div class="jp-type-single">
    <div class="jp-gui jp-interface">
      <ul class="jp-controls">
        <li><a href="javascript:;" class="jp-play" tabindex="1">play</a></li>
        <li><a href="javascript:;" class="jp-pause" tabindex="1">pause</a></li>
        <li><a href="javascript:;" class="jp-stop" tabindex="1">stop</a></li>
        <li><a href="javascript:;" class="jp-mute" tabindex="1" title="mute">mute</a></li>
        <li><a href="javascript:;" class="jp-unmute" tabindex="1" title="unmute">unmute</a></li>
        <li><a href="javascript:;" class="jp-volume-max" tabindex="1" title="max volume">max volume</a></li>
      </ul>
      <div class="jp-progress">
        <div class="jp-seek-bar">
          <div class="jp-play-bar"></div>
        </div>
      </div>
      <div class="jp-volume-bar">
        <div class="jp-volume-bar-value"></div>
      </div>
      <div class="jp-time-holder">
        <div class="jp-current-time"></div>
        <div class="jp-duration"></div>
        <ul class="jp-toggles">
        </ul>
      </div>
    </div>







      <div class="jp-no-solution">
        <span>Update Required</span>
        To play the media you will need to either update your browser to a recent version or update your <a href="http://get.adobe.com/flashplayer/" target="_blank">Flash plugin</a>.
      </div>
    </div>
  </div>
