<!DOCTYPE html>
<html>
<head>

...

<!-- PASTE THIS INTO YOUR HEADER -->
<link href="http://static.storyform.co/v0.6/css/read.css" rel="stylesheet" />
<script>
var _template = {
    version: 'v0.6',
    group: 'Puget',
    appKey: '8ED9C95551064AC6B8DFE60824C5A683'
};
/*-- START RENDER SCRIPT --*/!function(a){function b(a,b){var c=new XMLHttpRequest;c.onreadystatechange=function(){4===c.readyState&&(c.status>=200&&c.status<300?b(null,c):b(c),c.onreadystatechange=function(){})},c.open("GET",a.uri,!0),c.send()}document.documentElement.className+=" js";var c=void 0===_template.host?"//storyform.co":_template.host,d=_template.version||"v0.6",e=_template.generator?"&generator="+_template.generator:"",f=c+"/"+d+"/render/"+a._template.group+"?appKey="+encodeURIComponent(_template.appKey)+"&uri="+encodeURIComponent(document.location.href)+"&lastModified="+encodeURIComponent(document.lastModified)+"&title="+document.title.substr(0,200)+"&width="+window.innerWidth+"&height="+window.innerHeight+"&deviceWidth="+window.screen.width+"&deviceHeight="+window.screen.height+e;a.App=a.App||{},a.App.Data=a.App.Data||{},a.App.Data.render={callback:function(){},data:null,uri:f},b({uri:f},function(b,c){if(c){var d=a.App.Data.render.data=JSON.parse(c.responseText);a.App.Data.render.callback(null,d),a.App.Data.render.callback=function(){}}else a.App.Data.render.error=b,a.App.Data.render.callback(b),a.App.Data.render.callback=function(){}})}(this);/*-- END RENDER SCRIPT --*/
</script>
<script src="http://static.storyform.co/v0.6/js/read.js"></script>
<!-- END PASTE-->
...

</head>
<body>
<!-- STRUCTURE YOUR CONTENT LIKE THIS -->
<article data-content>
    <h1>Хөгжлийн хүчний эрэлд</h1>
    <post-publisher data-publisher>Article Author</post-publisher>
    <time data-published datetime="March 18, 2014">March 18, 2014</time>

    ...content of the article goes here...

</article>

<!-- AN OPTIONAL NAVIGATION BAR -->
<header class="navbar navbar-minimized navbar-left horizontal-links" role="navigation" data-win-control="UI.NavBar">
    <div class="navbar-toggle">
        <div class="navbar-lines-button">
          <span class="navbar-lines"></span>
        </div>
    </div>
    <div class="navbar-content">
        <a class="navbar-logo" href="/" rel="home">
            <h2 class="navbar-site-title">This is my site title</h2>
            <img src="/logo.png" alt="logo" />
        </a>
        <div class="navbar-title">
            <h6><a href="#">Title of the article</a></h6>
        </div>
        <div class="navbar-controls">
            <a class="navbar-icon" data-win-control="UI.FacebookShare" href="#"></a>
            <a class="navbar-icon" data-win-control="UI.TwitterShare" href="#"></a>
            <a class="navbar-icon" data-win-control="UI.GooglePlusShare" href="#"></a>
            <a class="navbar-icon" data-win-control="UI.FullScreenButton" href="#"></a>
        </div>
        <nav class="navbar-nav navbar-links">
            <ul id="menu-all-pages" class="menu">
                <li><a href="/pageA">Page A</a></li>
                <li><a href="/pageB">Page B</a></li>
            </ul>
        </nav>
    </div>
</header>
<div class="navbar-overlay"></div>

<!-- DON'T FORGET THE ACTUAL MAGAZINE VIEWER -->
<div class="primary-content">
    <div class="magazine" data-win-control="Controls.FlipView">
        <div data-win-control="UI.ProgressBar"></div>
        <div data-win-control="UI.PageNumbers"></div>
    </div>
</div>
</body>
</html>
</code>
