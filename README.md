(function () {
    const addScript = () => {
        document.head.innerHTML += `<style>
* {
	--ss-transparent: #00000000;
	--ss-black: #000;
	--ss-white: #FFFFFF; /*White Text*/
	--ss-offwhite: #94fff6;
	--ss-yellow0: #52b0c7;
	--ss-yellow: #0acdfc;
	--ss-yolk0: #0acdfc;
	--ss-yolk: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(13,115,20,1) 100%); /*Buttons*/
	--ss-yolk2: #006400;
	--ss-red0: #006400;
	--ss-red: #006400;
	--ss-red2: #006400;
	--ss-red-bright: #000;
	--ss-pink: #006400;
	--ss-pink1: #006400;
	--ss-pink-light: #006400;
	--ss-brown: #006400;
	--ss-blue00: #000;
	--ss-blue0: #006400;
	--ss-blue1: #006400;
	--ss-blue2: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(13,115,20,1) 100%);
	--ss-blue3: #38d638; /*Lighter Box Borders*/
	--ss-blue4: #006400; /*White Subtitles, Darker Box Borders*/
	--ss-blue5: #000;
	--ss-green0: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(13,115,20,1) 100%);
	--ss-green1: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(13,115,20,1) 100%);
	--ss-green2: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(13,115,20,1) 100%);
	--ss-orange1: #006400;
    --ss-green3: #006400;
	--ss-vip-gold:linear-gradient(to right, #fce19a, #fcfbe3, #fab969, #ffd363, #f7a33b);
	--ss-clear: rgba(255,255,255,0);
	--ss-blue2clear: rgba(94, 186, 217, 0);
	--ss-shadow: rgba(0,0,0,0.4);
	--ss-blueshadow: #577187;
    --ss-green3: #006400;
	--ss-darkoverlay: rgba(0, 0, 0, 0.8);
	--ss-darkoverlay2: rgba(0, 0, 0, 0.2);
	--ss-lightoverlay: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(13,115,20,1) 100%); /*Main Background*/
	--ss-lightbackground: linear-gradient(var(--ss-blue1), var(--ss-blue2));
	--ss-blueblend1: linear-gradient(#38c053, #38c053); /*Some Box fill colors*/
	--ss-scrollmask1: #006400
	--ss-scrollmask2: #006400
	--ss-fieldbg: linear-gradient(#91CADB, #ffffff, #ffffff, #ffffff, #ffffff);
	--ss-white-60: rgba(255,255,255,.6);
	--ss-white-90: rgba(255,255,255,.9);
 
	--ss-me-player-bg: #006400;
	--ss-them-blue-bg: rgba(0,66,87,.8);
	--ss-them-blue-color: #5ebbd9;
	--ss-them-red-bg:  rgb(133,0,0,.8);
	--ss-them-red-color: #ff4145;
	--ss-me-red-bg: rgba(255,65,69,.8);
	--ss-me-blue-bg: rgb(94,187,217,.8);
} /* 1377 */


#ammo {
	text-align: right;
	font-size: 3.25em;
	font-family: 'Nunito', sans-serif;
	font-weight: bold;
	line-height: 1em;
	margin: 0;
	
	padding-right: 1.2em;
	padding-top: 0em;
	margin-bottom: 0.1em;

	background-image: url('https://media.discordapp.net/attachments/746776796896297004/747462234153680956/Untitled_6.png?width=335&height=374');
    background-position: right center;
	background-size: contain;
    background-repeat: no-repeat;
}
#best_streak_container h1 {
	margin: 0; padding: 0;
	display: inline;
 
	text-shadow: var(--ss-space-micro) var(--ss-space-micro) var(--ss-shadow);
 
	font-family: 'Nunito', sans-serif !important;
	font-size: 2.5em !important;
	color: var(--ss-white) !important;
	font-weight: bold !important;
	text-transform: lowercase;
 
	padding-left: 1.25em;
	padding-top: 0em;
 
	background-image: url('https://media.discordapp.net/attachments/746776796896297004/747440287407800340/transparent-green-bone-clip-art-skull-5d661cf41a61a0.7480178915669731721081.png?width=406&height=406');
    background-position: left center;
	background-size: contain;
    background-repeat: no-repeat;
}
#maskmiddle {
	background: url('https://media.discordapp.net/attachments/746776796896297004/747389029800214559/Pzl6KGp_1.png?width=406&height=406') center center no-repeat;
	background-size: contain;
	width: 100vh;
	height: 100vh;
}
.crosshair {
	position: absolute;
	transform-origin: 50% top;
	top: 50%;
	border: solid 0.05em black;
	height: 0.8em;
	margin-bottom: 0.12em;
	opacity: 1;
 
	left: calc(50% - 0.15em);
	background: white;
	width: 0.3em;
}
.crosshair.normal {
	left: calc(50% - 0.15em);
	background: cyan;
	width: 0.3em;
}
 
.crosshair.powerful {
	left: calc(50% - 0.25em);
	background: black;
	width: 0.2em;
}
</style>`
    }
    document.body ? addScript() : document.addEventListener("DOMContentLoaded", e => addScript());
})();
