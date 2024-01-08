<div class="mainContainer">
	<div class="heading">
		<h1>JITSIE Blogs</h1>
		<span>
			Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eligendi, minima? Quaerat a debitis,
			corrupti excepturi iure commodi impedit
		</span>
	</div>
	<div class="cardsContainer">
		<div class="blogsCard">
			<div class="imgCont">
				<img
					src="https://images.getimg.ai/resize?url=https%3A%2F%2Fassets.getimg.ai%2Fimages%2Fbackground-replacement.jpg&type=auto&width=256&quality=75"
					alt=""
				/>
			</div>
			<div class="cardContent">
				<span class="card_heading"> Artificial Intelligence For marketing </span>
				<span class="card_content">
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero nulla sequi eligendi
					natus. Quam que soluta temporibus.
				</span>
				<button>Learn Now</button>
			</div>
		</div>
		<div class="blogsCard">
			<div class="imgCont">
				<img
					src="https://images.getimg.ai/resize?url=https%3A%2F%2Fassets.getimg.ai%2Fimages%2Fbackground-replacement.jpg&type=auto&width=256&quality=75"
					alt=""
				/>
			</div>
			<div class="cardContent">
				<span class="card_heading"> Artificial Intelligence For marketing </span>
				<span class="card_content">
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero nulla sequi eligendi
					natus. Quam que soluta temporibus.
				</span>
				<button>Learn Now</button>
			</div>
		</div>
		<div class="blogsCard">
			<div class="imgCont">
				<img
					src="https://images.getimg.ai/resize?url=https%3A%2F%2Fassets.getimg.ai%2Fimages%2Fbackground-replacement.jpg&type=auto&width=256&quality=75"
					alt=""
				/>
			</div>
			<div class="cardContent">
				<span class="card_heading"> Artificial Intelligence For marketing </span>
				<span class="card_content">
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero nulla sequi eligendi
					natus. Quam que soluta temporibus.
				</span>
				<button>Learn Now</button>
			</div>
		</div>
		<div class="blogsCard">
			<div class="imgCont">
				<img
					src="https://images.getimg.ai/resize?url=https%3A%2F%2Fassets.getimg.ai%2Fimages%2Fbackground-replacement.jpg&type=auto&width=256&quality=75"
					alt=""
				/>
			</div>
			<div class="cardContent">
				<span class="card_heading"> Artificial Intelligence For marketing </span>
				<span class="card_content">
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero nulla sequi eligendi
					natus. Quam que soluta temporibus.
				</span>
				<button>Learn Now</button>
			</div>
		</div>
		<div class="blogsCard">
			<div class="imgCont">
				<img
					src="https://images.getimg.ai/resize?url=https%3A%2F%2Fassets.getimg.ai%2Fimages%2Fbackground-replacement.jpg&type=auto&width=256&quality=75"
					alt=""
				/>
			</div>
			<div class="cardContent">
				<span class="card_heading"> Artificial Intelligence For marketing </span>
				<span class="card_content">
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero nulla sequi eligendi
					natus. Quam que soluta temporibus.
				</span>
				<button>Learn Now</button>
			</div>
		</div>
	</div>
	<div class="heading">
		<h1>Lorem Ipsum</h1>
	</div>
</div>

<style>
	.mainContainer {
		max-width: 2000px;
		margin: auto;
		font-family: 'Inter', sans-serif;
		background-color: black;
		color: white;
	}

	.heading {
		margin: 3em 0;
		display: flex;
		flex-direction: column;
		justify-content: center;
		text-align: center;
	}

	.heading h1 {
		font-size: 3em;
	}

	.heading span {
		margin: auto;
		width: 50%;
	}

	.cardsContainer {
		width: fit-content;
		display: flex;
		flex-wrap: wrap;
		gap: 5em;
		margin: auto;
	}

	.blogsCard {
		background-color: #3b54c5;
		border-radius: 1em;
		padding: 3em;
		width: fit-content;
		display: flex;
		gap: 4em;
		position: relative;
		margin: auto;
		box-shadow: 0px 10px 0 -5px #14448b, 0px 20px 0 -10px #193258;
	}

	.imgCont img {
		border-radius: 1em;
		width: 12em;
		height: 12em;
	}
	.cardContent {
		width: 14em;
		display: flex;
		flex-direction: column;
		height: fit-content;
		margin: auto 0;
		text-transform: capitalize;
		gap: 1em;
	}

	.card_heading {
		font-weight: 600;
		font-size: 20px;
	}

	.card_content {
		font-size: 14px;
	}

	.cardContent button {
		font-weight: bold;
		padding: 1.3em 2em;
		background-color: #242731;
		width: fit-content;

		border: none;
		border-radius: 10px;
		border: none;
	}

	@media (max-width: 620px) {
		.blogsCard {
			flex-direction: column;
			gap: 2em;
		}

		.imgCont img {
			width: 100%;
		}

		.cardContent {
			margin: auto;
			width: 16em;
		}

		.cardContent button {
			margin: auto;
		}
	}
</style>
