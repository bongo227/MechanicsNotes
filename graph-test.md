<script>alert('Hello world');</script>

<link rel="stylesheet" type="text/css" href="http://jsxgraph.uni-bayreuth.de/distrib/jsxgraph.css" />
 <script type="text/javascript" src="http://jsxgraph.uni-bayreuth.de/distrib/jsxgraphcore.js"></script>
 
<div id="box" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
 let box = document.getElementById("box");
 box.innerHtml = "Hello world";
 
 var board = JXG.JSXGraph.initBoard('box', {boundingbox: [-10, 10, 10, -10], axis:true});
</script>
 
 