# Sorting-Techniques
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Sorting Visualization</title>
</head>

<body>
	<div class="header">
		<h1>Sorting Techniques</h1>
		<div class="vars">
			<div class="range">
				<div class="slide"><label for="bars">ِArray Size</label> : <input id="bars" type="range" name="bars"
						min="1" max="100" value="50" oninput="setup()" onchange="setup()">
					<span id="b"> </span></div>
				<div class="slide"><label for="delay">Speed</label> : <input id="delay" type="range" name="delay"
						min="0" max="1000" value="25" oninput="setup()" onchange="setup()">
					<span id="d"></span></div>
			</div>
			<div class="sorts">
				<input type="button" onclick="SelectionSort()" value="Selection Sort">
				<input type="button" onclick="BubbleSort()" value="Bubble Sort">
				<input type="button" onclick="InsertionSort()" value="Insertion Sort">
				<input type="button" onclick="MergeSort()" value="Merge Sort">
				<input type="button" onclick="QuickSort()" value="Quick Sort">
				<input type="button" onclick="HeapSort()" value="Heap Sort"><br><br>
			</div>
			<button onclick="reset()">Generate New Array</button>
		</div>
	</div>
	<div id="container">
	</div>
	<script src="/beep.js"></script>
	<script src="/first.js"></script>
</body>

</html>
