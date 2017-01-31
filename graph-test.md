# Graph test

<link rel="stylesheet" type="text/css" href="http://jsxgraph.uni-bayreuth.de/distrib/jsxgraph.css" />
 <script type="text/javascript" src="http://jsxgraph.uni-bayreuth.de/distrib/jsxgraphcore.js"></script>

<div id="test">
Testing
</div>

<div id="box" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
 var board = JXG.JSXGraph.initBoard('box', {boundingbox: [-10, 10, 10, -10], axis:true});
</script>

<script>
let t = document.getElementById('test');
t.innerHTML = 'bob';
</script>
 