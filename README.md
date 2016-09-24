# Simple SVG Icons

Resource for simple SVG icons

**Play**

![Play](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/play.svg)

    <svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
      <polygon points="5,0 25,15 5,30"/>
    </svg>


**Pause**

![Pause](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/pause.svg)

    <svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
      <rect height="30" width="8" x="3"/>
      <rect height="30" width="8" x="17"/>
    </svg>


**Restart**

![Restart](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/restart.svg)

    <svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
    	<defs>
    		<mask id="m">
    			<rect height="30" width="30" fill="white"/>
    			<circle cx="15" cy="15" r="7" fill="black"/>
    			<polygon points="0,15 15,15 0,28" fill="black"/>
    		</mask>
    	</defs>
      <circle cx="15" cy="15" r="13" stroke-width="6" mask="url(#m)" />
      <rect height="10" width="5" y="3" fill=""/>
      <rect height="5" width="13" y="12" fill=""/>
    </svg>
