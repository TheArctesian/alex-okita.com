<script>
    import Google from '../../Compontents/Links/google.svelte';
    import Social from '../../Compontents/Links/social.svelte';
    import Searchbar from '../../Compontents/Links/SearchBar.svelte';
</script>

<div class="bag">
	<div class="head">
	</div>
<div class="search">
		<Searchbar />
	</div>

		<!-- <div
			class="flex items w-half  flex-wrap flex-row p-5 lg:justify-around md:flex-wrap
		sm:flex-warp"
		>
			<Todo />
		</div> -->
		<div
			class="flex items w-half m-auto flex-wrap flex-row p-5 lg:justify-around md:flex-wrap
		sm:flex-warp"
		>
			<Google />
			<Social />
		</div>
	</div>
	

<style>
	div {
		background-color: #272727;
	}
	.bag {
		height: 100vh;
	}
	.search {
		padding-left: 5rem;
		padding-right: 5rem;
	}
.head {
			padding-top: 3rem;
			padding-left: 0rem;
			text-align: center;
		}
	@media (max-width: 750px) {
		.head {
			padding-top: 3rem;
			padding-left: 0rem;
			text-align: center;
		}
		.items {
			flex-wrap: wrap;
			align-items: center;
			justify-content: center;
		}
	}
</style>
