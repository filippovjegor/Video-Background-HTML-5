# Video-Background-HTML-5
Examples of creating and using Video Background HTML 5 
Create Video background is no more difficult than a normal background image by using a minimal set of properties in CSS.
Wrap video tag in <code>div class=&quot;fullscreen-bg&quot;</code>
<pre class="prettyprint">&lt;div class=&quot;fullscreen-bg&quot;&gt;
    &lt;video loop muted autoplay poster=&quot;media/videoframe.png&quot; class=&quot;fullscreen-bg__video&quot;&gt;
        &lt;source src=&quot;media/videoframe.webm&quot; type=&quot;video/webm&quot;&gt;
        &lt;source src=&quot;media/videoframe.mp4&quot; type=&quot;video/mp4&quot;&gt;&gt;
    &lt;/video&gt;
&lt;/div&gt;</pre>

Define the minimum CSS properties:
<pre class="prettyprint">.fullscreen-bg { 
     position: absolute;
     top: 0px;
     left: 0px;
     min-width: 100%;
     min-height: 100%;
     width: auto;
     height: auto;
     z-index: -100;
     overflow: hidden;
}
.fullscreen-bg video{
    min-height: 100%;
    min-width: 100%;
    width: 100%;
}</pre>
All! And you thought will be more difficult?

<h2>3 Examples of application Video Background HTML 5</h2>

<h2><a href="http://filwebs.ru/example/videobg/videobg-1.html" target="_blank">Example Demo-1</a></h2>
<h2><a href="http://filwebs.ru/example/videobg/videobg-2.html" target="_blank">Example Demo-2</a></h2>
<h2><a href="http://filwebs.ru/example/videobg/videobg-3.html" target="_blank">Example Demo-3</a></h2>

<h2><a href="http://filwebs.ru/sozdanie-video-background-html-5/" target="_blank">DESCRIPTIONS</a></h2>
