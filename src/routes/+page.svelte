<div id="white">
	<div id="everything">
		<header>
            <h1>all the small things</h1>
            <h6>cd single</h6>
        </header>
		<div id="guys" />
	</div>
</div>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
	}
	#everything {
		height: 50vh;
		width: 50vh;
		display: flex;
		flex-direction: column;
		justify-content: space-around;
		background: yellow;
        overflow: visible;
	}
	header {
		width: 100%;
		background: #01a3d4;

	}
    header > h1, header > h6 {
        text-transform: capitalize;
        font-style: italic;
        font-weight: bold;
        color: white;
    }
	#guys {
		height: 50%;
		width: 50%;
		background: lightgrey;
		border: red 10px solid;
		border-radius: 7%;
        margin-left: 10%;
	}
    #white {
        height: 100vh;
        width: 100vw;
        background: white;
        display: flex;
        justify-content: center;
    }
</style>
