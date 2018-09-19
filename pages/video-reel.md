---
layout: page
permalink: /video-reel/
useVideoPlayer: true
navPage: nav-video
title: Matthew James Kelly - Video Reel
---
<div id="main" class="twelvecol first clearfix" role="main">        
    <h2>Film</h2>            
    {% for v in site.data.videos-film %}
    <div id="videoPlayer" class="video_player">
        <iframe src="http://player.vimeo.com/video/{{ v.id }}?color=ffffff" width="500" height="282" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe> 
        <p><a href="http://vimeo.com/62889356">{{ v.title }}</a> {{ v.credit }}.</p>
    </div>                
    {% endfor %}				        
    <h2>TV and Commercials</h2>        
    {% for v in site.data.videos-tv %}
    <div id="videoPlayer" class="video_player">
        <iframe src="http://player.vimeo.com/video/{{ v.id }}?color=ffffff" width="500" height="282" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe> 
        <p><a href="http://vimeo.com/62889356">{{ v.title }}</a> {{ v.credit }}.</p>
    </div> 
    {% endfor %}                
</div> <!-- end #main -->