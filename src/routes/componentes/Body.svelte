<main class="body">
	<div class="card-one">
		<div class="card-one-text">
			<span class="card-text-title" id="one">Find your adventure</span>
			<span class="card-text-subtitle" id="onesub"
				>Starbucks® Summer Game is here! Play for your chance to win—more than 10 million prizes are
				up for grabs!*</span
			>
			<button class="btn-body-one">Play now</button>
		</div>
		<div class="card-img">
			<img
				src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-84026.jpg"
				alt=""
			/>
		</div>
	</div>
	<div class="card-two">
		<div class="card-img">
			<img
				src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-83789.jpg"
				alt=""
			/>
		</div>
		<div class="card-two-text">
			<span class="card-text-title" id="two">For your enjoy-mint</span>
			<span class="card-text-subtitle" id="twosub"
				>Hooray for our newest cooler-than-cool Chocolate Java Mint Frappuccino® blended beverage.</span
			>
			<button class="btn-body-two">Order now</button>
		</div>
	</div>
	<div class="card-three">
		<div class="card-three-text">
			<span class="card-text-title" id="three">Macadamia just dropped</span>
			<span class="card-text-subtitle" id="threesub"
				>Introducing the White Chocolate Macadamia Cream Cold Brew with toasted cookie <br /> crumbles.</span
			>
			<button class="btn-body-three">Order now</button>
		</div>
		<div class="card-img">
			<img
				src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-83790.jpg"
				alt=""
			/>
		</div>
	</div>
	<div class="card-four">
		<div class="card-img">
			<img
				src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-83791.jpg"
				alt=""
			/>
		</div>
		<div class="card-four-text">
			<span class="card-text-title" id="four">Sweetest of the hive</span>
			<span class="card-text-subtitle" id="foursub"
				>Buzzing into the café, an adorable new <br /> Bumblebee Cake Pop dipped in chocolaty icing.</span
			>
			<button class="btn-body-four">Order now</button>
		</div>
	</div>
</main>

<style>
	.card-text-title {
		font-size: 50px;
		line-height: 60px;
		font-family: 'Open Sans', sans-serif;
	}
	.card-text-subtitle {
		font-size: 24px;
		font-family: 'HelveticaNeue-Light', 'Helvetica Neue Light', 'Helvetica Neue', Helvetica, Arial,
			'Lucida Grande', sans-serif;
	}
	.body {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		margin-top: 24.5px;
		gap: 24px;
	}
	.card-one {
		display: flex;
		height: 25%;
		width: 82.5%;
		background-color: aqua;
		flex-wrap: wrap;
	}
	.card-one-text {
		height: 100%;
		width: 50%;
		background-color: #006241;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		gap: 20px;
	}
	#one {
		color: #fff;
		letter-spacing: 2px;
		padding: 0 1200px;
		line-height: 48px;
	}
	#onesub {
		color: #fff;
		letter-spacing: -0.012px;
		padding: 0 82px;
		text-align: center;
	}
	.btn-body-one {
		height: 32px;
		width: 85px;
		border-radius: 50px;
		font-size: 12px;
		text-align: center;
		line-height: 14px;
		letter-spacing: -0.012px;
		padding: 7px 15px;
		margin-top: 14px;
		color: #fff;
		border: 1px solid white;
		background-color: transparent;
		cursor: pointer;
	}
	.btn-body-one:hover {
		opacity: 0.6;
	}
	.card-img {
		height: 100%;
		width: 50%;
		background-color: green;
	}
	.card-img img {
		height: 100%;
		width: 100%;
		background-color: green;
	}
	.card-two {
		display: flex;
		height: 624px;
		width: 82.5%;
		background-color: aqua;
		flex-wrap: wrap;
	}
	.card-two-text {
		height: 100%;
		width: 50%;
		background-color: rgb(212, 233, 226);
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		gap: 20px;
		color: #1e3932;
	}
	#two {
		color: #1e3932;
		letter-spacing: 2px;
		line-height: 48px;
	}
	#twosub {
		color: #1e3932;
		letter-spacing: -0.012px;
		padding: 0 82px;
		text-align: center;
	}
	.btn-body-two {
		height: 32px;
		width: 92px;
		border-radius: 50px;
		font-size: 12px;
		line-height: 14px;
		letter-spacing: -0.012px;
		padding: 7px 14px;
		margin-top: 14px;
		color: #1e3932;
		border: 1px solid #1e3932;
		background-color: transparent;
		cursor: pointer;
	}
	.btn-body-two:hover {
		opacity: 0.6;
	}
	.card-three {
		display: flex;
		height: 624px;
		width: 82.5%;

		flex-wrap: wrap;
	}
	.card-three-text {
		height: 100%;
		width: 50%;
		background-color: #cbe678;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		gap: 20px;
		color: #1e3932;
	}
	#three {
		color: #1e3932;
		letter-spacing: 2px;
		text-align: center;
		padding: 0 40px;
		line-height: 48px;
	}
	#threesub {
		color: #1e3932;
		letter-spacing: -0.012px;
		padding: 0 82px;
		text-align: center;
	}
	.btn-body-three {
		height: 32px;
		width: 92px;
		border-radius: 50px;
		font-size: 12px;
		line-height: 14px;
		letter-spacing: -0.012px;
		padding: 7px 14px;
		margin-top: 14px;
		color: #1e3932;
		border: 1px solid #1e3932;
		background-color: transparent;
		cursor: pointer;
	}
	.btn-body-three:hover {
		opacity: 0.6;
	}
	.card-four {
		display: flex;
		height: 624px;
		width: 82.5%;

		flex-wrap: wrap;
	}
	.card-four-text {
		height: 100%;
		width: 50%;
		background-color: #f1ff67;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		gap: 20px;
		color: #1e3932;
	}
	#four {
		color: #1e3932;
		letter-spacing: 2px;
		text-align: center;
		padding: 0 40px;
		line-height: 48px;
	}
	#foursub {
		color: #1e3932;
		letter-spacing: -0.012px;
		padding: 0 82px;
		text-align: center;
	}
	.btn-body-four {
		height: 32px;
		width: 92px;
		border-radius: 50px;
		font-size: 12px;
		line-height: 14px;
		letter-spacing: -0.012px;
		padding: 7px 14px;
		margin-top: 14px;
		color: #1e3932;
		border: 1px solid #1e3932;
		background-color: transparent;
		cursor: pointer;
	}
	.btn-body-four:hover {
		opacity: 0.6;
	}

	@media only screen and (max-width: 906px) {
		* {
			font-size: 200px;
		}
		.card-one {
			display: flex;
			width: 100%;
			height: 50%;
			background-color: aqua;
			flex-wrap: wrap-reverse;
		}
		.card-one-text {
			height: 40%;
			width: 100%;
			background-color: #006241;
			display: flex;
			justify-content: center;
			align-items: center;
			flex-direction: column;
			gap: 10px;
		}
		.card-two {
			display: flex;
			width: 100%;
			height: 50%;
			background-color: aqua;
			flex-wrap: wrap;
		}
		.card-two-text {
			height: 40%;
			width: 100%;
			background-color: rgb(212, 233, 226);
			display: flex;
			justify-content: center;
			align-items: center;
			flex-direction: column;
			gap: 10px;
			color: #1e3932;
		}
		.card-three {
			display: flex;
			width: 100%;
			height: 50%;
			background-color: aqua;
			flex-wrap: wrap-reverse;
		}
		.card-three-text {
			height: 40%;
			width: 100%;
			background-color: #cbe678;
			display: flex;
			justify-content: center;
			align-items: center;
			flex-direction: column;
			gap: 10px;
			color: #1e3932;
		}
		.card-four {
			display: flex;
			width: 100%;
			height: 50%;
			background-color: aqua;
			flex-wrap: wrap;
		}
		.card-four-text {
			height: 40%;
			width: 100%;
			background-color: #f1ff67;
			display: flex;
			justify-content: center;
			align-items: center;
			flex-direction: column;
			gap: 5px;
			color: #1e3932;
		}
		.card-img {
			height: 60%;
			width: 100%;
			background-color: green;
		}
		.card-img img {
			height: 100%;
			width: 100%;
			background-color: green;
		}
		.card-text-title {
			font-size: 30px;
		}
		.card-text-subtitle {
			font-size: 15px;
		}
	}
</style>
