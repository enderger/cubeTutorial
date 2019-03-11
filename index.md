<head>
	<title>Rubik's Cube Beginner's Method</title>
	<style>
		button {
		  background-color: dimgrey;
		  color: ghostwhite;
 		  text-align: center;
  		  text-decoration: none;
		  display: block;
		  font-size: 16px;
		  border: 1px solid forestgreen;
		  width: 90%;
		  padding-bottom: 7px;
		  padding-top: 7px;
		  overflow: hidden;
		}
		button:hover {
		  background-color: ghostwhite;
		  color: black;
		}
	</style>
	<script>
		function stage1() {
			if (document.getElementById('notation').style.display == none) {
				document.getElementById('notation').style.display = block;
			} else {
				document.getElementById('notation').style.display = none;
			}
		}
	</script>
</head>
# Rubik's Cube Layer-by-Layer Beginner's Method
<body>
	<button onclick="stage1">Part 1: Notation</button> <br>
	<button onclick="stage2">Part 2: White Cross</button> <br>
	<button onclick="stage3">Part 3: White Corners</button> <br>
	<button onclick="stage4">Part 4: Solve the Second Layer</button> <br>
	<button onclick="stage5">Part 5: Orient the Yellow Cross</button> <br>
	<button onclick="stage6">Part 6: Orient the Yellow Corners</button> <br>
	<button onclick="stage7">Part 7: Permute the Yellow Corners</button> <br>
	<button onclick="stage8">Part 8: Permute the Yellow Edges</button> <br>
</body>
<div id="notation">
	<h1>Notation</h1>
</div>
