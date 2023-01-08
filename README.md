<iframe width="560" height="315" src="https://www.youtube.com/embed/GuGCw6xdNII" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


<script src="https://cdn.jsdelivr.net/clappr/latest/clappr.min.js" type="text/javascript"></script>
<script src="https://cdn.jsdelivr.net/clappr.level-selector/latest/level-selector.min.js" type="text/javascript"></script>
<div id="oper"></div>
<div id="vid"></div>
<script>
 player = new Clappr.Player({
 source: "http://apex-media.xyz:8080/live/adamryan762@gmail.com/e3QZWRs/1514084.m3u8",
 mimeType: "application/x-mpegURL",
 autoPlay: true, 
 height: "1080",
 width: "100%",
 plugins: {"core": [LevelSelector]}, 
 parentId: "#vid"});
</script>
