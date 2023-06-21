<div id="white">
	<div id="everything">
		<header>
            <div id="logo">
                <div id="block"/>
                <div id="right-outside"/>
                <div id="left-outside"/>
                <div id="top-bar"/>
                <div id="bottom-bar"/>
                <p id="blink">blink</p>
                <p id="numbers">-182-</p>
            </div>
            <div id="text">
                <h1>all the small things</h1>
                <h4>CD single</h4>
            </div>
        </header>
		<div id="guys" />
	</div>
</div>

<style>

    @font-face {
        font-family: "Univers 85 Extra Black Oblique";
        src: url(/univers-85-extra-black-oblique.otf);
    }
    @font-face {
        font-family: "Folio Condensed Bold";
        src: url(/Equal-Sans-Demo.ttf.woff);
    }
    @font-face {
        font-family: "Helvetica Neue 85";
        src: url(/helvetica-neue-lt-std-83-heavy-extended-oblique.otf);
    }
    :global(html) {
        font-size: 2vmin;
    }
	:global(body) {
		margin: 0;
		padding: 0;
	}

    /* logo styles */  
     
    #logo {
        height: 100%;
        width: 43%;
        background: #01a3d4;
        display: block;
    }
    #block {
        background: white;
        height: 10.7vmin;
        width: 15.2vmin;
        
        position: relative;
        left: 22.5vmin;
        top: 6vmin;

        border-right: #fff 0rem solid;
        border-top-right-radius: 50vmin;
        border-bottom-right-radius: 50vmin;

    }
    #right-outside {
        height: 15vmin;
        width: 20.5vmin;
        
        position: absolute;
        margin-left: 19.5vmin;
        margin-top: -7.7vmin;

        border: #fff 0.5rem solid;
        border-radius: 50vmin;

        border-top-left-radius: 0;
        border-bottom-left-radius: 0;
        border-left: none;
    }
    #left-outside {
        height: 11.8vmin;
        width: 16.3vmin;
        
        position: absolute;
        margin-left: 3vmin;
        margin-top: -6.2vmin;

        border: #fff 0.5rem solid;
        border-radius: 50vmin;

        border-top-right-radius: 0;
        border-bottom-right-radius: 0;
        border-right: none;
    }
    #top-bar {
        position: absolute;
        background: white;
        height: 1.8vmin;
        width: 0.5rem;

        margin-left: 19.5vmin;
        margin-top: -7vmin;


    }
    #bottom-bar {
        position: absolute;
        background: white;
        height: 1.8vmin;
        width: 0.5rem;

        margin-left: 19.5vmin;
        margin-top: 6.6vmin;
    }
    #blink {
        position: absolute;
        font-family: "Helvetica Neue 85";
        font-size: 5.3vmin;
        font-weight: 500;
        color: #fff;
        margin-left: 6.5vmin;
        margin-top: -2.8vmin;
    }
    #numbers {
        position: absolute;
        font-family: "Folio Condensed Bold";
        font-weight: bold;
        font-size: 11vmin;
        letter-spacing: 0vmin;
        color: red;
        margin-left: 23vmin;
        margin-top: -5vmin;
        z-index: 1;
    }

    /* this is actually the cd cover */
	#everything {
		height: 100vmin;
		width: 100vmin;
		display: flex;
		flex-direction: column;
		justify-content: space-evenly;
		background: #fff004;
        overflow: visible;
	}
	header {
		width: 100%;
		height: 22.56vmin;
        display: flex;
		background: #01a3d4;

	}
    #text {
        margin-top: 9.5vmin;
        line-height: 0.95;
    }
    h1 {
        font-size: 5.05vmin;
    }
    h4 {
        font-size: 2.7vmin;
    }
    h1, h4 {
        text-transform: capitalize;
        font-family: "Univers 85 Extra Black Oblique";
        font-weight: 100;
        color: #fdfde8;
        margin: 0;
    }
	#guys {
		height: 60.5vmin;
		width: 64.5vmin;
        /* position: relative;
        left: 5vmin; */
		background-image: url(/good-guys.jpg);
        background-size: 102%;
        background-position-y: 66%;
        background-position-x: 50%;
		border: #fc2509 0.75rem solid;
		border-radius: 6%;
        margin-left: 4.3%;
	}
    /* this is actually the bcakground */
    #white {
        height: 100vh;
        width: 100vw;
        background: url(chrome://global/skin/media/imagedoc-darknoise.png);
        display: flex;
        justify-content: center;
    }
</style>
