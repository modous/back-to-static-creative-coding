<body class="container">
	<section class="sec">
		<article>
			<h1 style="font-size: 30px">Awful post-apocaliptic rift</h1>
			<img class="rift tree" src="Rift.jpg" alt="" />

			<img
				class="rift cat"
				src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS_jljfMzhSw4X3aYF-2vW_3LhCdbAwgrLweQ&usqp=CAU"
				alt=""
			/>

			<img class="rift2 tree second" src="Rift.jpg" alt="" />
		</article>

		<article>
			<img
				class="rift tree tree2"
				src="https://upload.wikimedia.org/wikipedia/commons/b/bf/Tree_Transparent_Background.png"
				alt=""
			/>
		</article>
	</section>
</body>

<style>
	.container {
		position: relative;
		background: url('https://best-sci-fi-books.com/wp-content/uploads/2014/08/Post-Apocalyptic_Cityscape_600.jpg')
			center/cover no-repeat; /* Replace 'your-image.jpg' with the actual path to your image */
		height: 200vh; /* Adjust the height as needed */
	}

	body {
		margin: 0;
		padding: 0;
	}


	.tree2{

		max-width: 100px;
		margin-left: 900px;
	}
	.tree {
		animation: rotate 5s linear infinite;
	}

	@keyframes rotate {
		from {
			margin-top: 100px;
			transform: rotate(0deg);
		}
		to {
			margin-top: 0px;
			transform: rotate(360deg);
		}
	}
	.cat {
		margin-bottom: 200px;
		max-width: 50px;
		padding-right: 200px;
		animation: leftRight 5s linear infinite;
	}

	@keyframes leftRight {
		0% {
			transform: rotate(0deg);
			margin-left: 0px;
			scale: 1.4;
		}
		100% {
			transform: rotate(360deg);
			margin-left: 200px;
			scale: 0.1;
		}
	}

	.rift {
		width: 400px;
	}

	.rift2 {
		margin-bottom: 200px;
		width: 100px;
		
	}

	.sec {
		display: flex;
		justify-content: center;
		flex-direction: column;
	}

	.second {
		margin-left: 200px;
	}
</style>
