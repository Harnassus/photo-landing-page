<script>
	import FaAlignRight from 'svelte-icons/fa/FaAlignRight.svelte';
	import FaShareAlt from 'svelte-icons/fa/FaShareAlt.svelte';
</script>

<div class="wrapper">
	<div class="left" />
	<div class="right" />

	<nav class="nav">
		<ul>
			<li class="w-12 h-11">
				<FaAlignRight />
			</li>
			<li>collection</li>
			<li>explore</li>
			<li>search</li>
			<li>
				<img src="" alt="" />
			</li>
		</ul>
	</nav>

	<div>
		<div class="img-container">
			<div class="Olaolu" />
		</div>

		<div>
			<ul>
				<li>unsplash.com</li>
				<li>@Lágbájáwá</li>
				<li>Lágbájáwá.com</li>
				<li class="w-12 h-11">
					<FaShareAlt />
				</li>
			</ul>
		</div>

        <div>
            <h1>Lágbájá wá</h1>
            <p>Street Photographer</p>
        </div>

        <div>Lágbájá wá</div>

        <div class="bottomnav">
            <ul>
                <li>profile</li>
                <li>portfolio</li>
                <li>contact</li>
            </ul>
        </div>
	</div>
</div>

<style>

    @font-face {
        font-family: 'Raiderfont';
        src: local('Raiderfont'), url('../../static/Raiderfont.ttf') format('truetype')
    }

    .left,
    .right{
        position: absolute;
        width: 50%;
        height: 100%;
        z-index: -1;
    }
    .right {
        background: #191921
    }
    .left{
        background: #B3B4AF;
        left: 0%;
    }
    
</style>