<script>
	import Section from './Section.svelte'
</script>

<main>
	<section id="hero">
		<div class="content">
			<h1>The Gifts You Give to Me</h1>
		</div>
	</section>
	<Section number="One" giftTitle="Time" giftDesc="You always sacrifice this for our family" />
	<Section number="Two" giftTitle="Children" giftDesc="You brought our beautiful children into this world" />
	<Section number="One" giftTitle="Support" giftDesc="You always listen to me and my complaints" />
	<Section number="Two" giftTitle="Advice" giftDesc="Even when I’m stubborn and don’t want to here it" />
	<Section number="One" giftTitle="Career" giftDesc="Without your sacrifice in New York and watching the kids, I couldn’t do what I do" />
	<Section number="Two" giftTitle="Heart" giftDesc="When you said yes to marrying me for eternity" />
	<Section number="One" giftTitle="Meaning" giftDesc="You help me strive to be better everyday" />
	<section>
		<div class="content">
			<h3>To me you are the greatest gift I have or will ever receive. Love you!</h3>
			<h2>Thank you Kat!</h2>
		</div>
	</section>
</main>

<style>
	section {
		padding: 3em 1em 2em;
	}
	
	.content {
		max-width: 800px;
		margin: 0 auto;
		padding: 3em 0;
	}
	
	h1 {
		font-size: 10em;
		line-height: 1em;
		font-weight: bold;
		color: var(--gray800);
	}

	h3 {
		font-size: 2em;
	}

	h2 {
		font-size: 4em;
		font-weight: bold;
	}

	@media only screen and (max-width: 500px){
		section {
			padding: 1em;
		}
		h1 {
			font-size: 4em;
		}
		.content {
			max-width: none;
		}
	}
</style>