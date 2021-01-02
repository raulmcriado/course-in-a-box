---
layout: index
published: true
---

Course-in-a-Box is a free tool for building and publishing online courses—no prior coding experience required. This guide was made using Course-in-a-Box, so what you see here is what you’ll start with. There are three modules that walk through the course creation process, all linked in the nav bar at the top of the page:
* **[Setup](/modules/setup/getting-started/)** - Get your instance of Course-in-a-Box up and running
* **[Content](/modules/content/markdown-and-media)** -  Update the course structure and add your copy & media
* **[Customize](/modules/customize/favicon)** - Add some (optional) finishing touches

<br> 

<html>

<head>
        <title>Apps with Toolbar: Graphing Calculator</title>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
		<script src="navigation.js"></script>
</head>

<body>
<div>
        <h1>Apps with Toolbar: Graphing Calculator</h1>
        <p style="width:800px">This page shows how to embed GeoGebra Graphing Calculator without construction in a webpage. 
        For details about customization please refer to <a href="https://wiki.geogebra.org/en/Reference:Applet_Parameters">documentation</a>. Please check out embedding examples for our other apps:</p>
          <a class="btn active" id="app_graphing" href="example-graphing.html">Graphing Calculator</a>
        <a class="btn" id="app_geometry" href="example-geometry.html">Geometry</a>
        <a class="btn" id="app_classic" href="example-tools.html">Classic</a>
        <script type="text/javascript" src="https://cdn.geogebra.org/apps/deployggb.js"></script>

        <script type="text/javascript">
				function perspective(p){
					updateHelp(p);
					ggbApplet.setPerspective(p);
				}
                var parameters = {
                        "id":"ggbApplet",
                        "appName":"graphing",
                        "width":800,
                        "height":600,
                        "showToolBar":true,
                        "borderColor":null,
                        "showMenuBar":true,
                        "allowStyleBar":true,
                        "showAlgebraInput":true,
                        "enableLabelDrags":false,
                        "enableShiftDragZoom":true,
                        "capturingThreshold":null,
                        "showToolBarHelp":false,
                        "errorDialogsActive":true,
                        "showTutorialLink":true,
                        "showLogging":true,
                        "useBrowserForJS":false};

                var applet = new GGBApplet(parameters, '5.0', 'applet_container');
               //  when used with Math Apps Bundle, uncomment this:
               //  applet.setHTML5Codebase('GeoGebra/HTML5/5.0/web3d/');

                window.onload = function() { applet.inject('applet_container'); }

        </script>


        <div id="applet_container"></div>
		</div>
</body>

</html>


#### Course-in-a-Box Courses We Love ❤️
Here are some examples of Course-in-a-Box in the wild:

* [Making and Learning](http://p2pu.github.io/makingandlearning/) by Children’s Museum of Pittsburgh
* [Designing for Documentation and Assessment](https://playfulmit.github.io/beyond-rubrics/) by MIT Playful Journey Lab
* [ExplOERer Course](http://www.exploerercourse.org/en/) by Gothenburg University, Open University, and CC Poland
* [Learning about Learning Circles](https://p2pu.github.io/learning-about-learning-circles/)  by P2PU

<br> 

#### Need some help?
Our [community forum](https://community.p2pu.org/c/tech/course-in-a-box/78) is a great place to ask questions or find help when you get stuck. Feel free to post there anytime!

You can also hire P2PU to provide support with learning design, technical setup, course customizations, or web hosting. If you’re interested in collaborating on a project, reach out to us at thepeople@p2pu.org

<br> 

#### About Course-in-a-Box

P2PU created Course-in-a-Box in 2014 as a free and lightweight tool for building online courses. We wanted to preserve the modular structure of MOOCs outside of the bulky (and often proprietary) environment of learning/content management systems. Course-in-a-Box is open-source, and we welcome contributions [on our Github repo](https://github.com/p2pu/course-in-a-box).

p.s. Designing a course for learning circles? [Check out the Learning Circle Course Creation guide](https://docs.google.com/document/u/1/d/116fJM3GS7XDzilUOL_ynMZ0yTncUD6aVUbcQKsTra6U/edit#heading=h.l36tzg40xcgr) for some best practices on course design.
