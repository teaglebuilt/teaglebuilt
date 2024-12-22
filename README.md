<div align="center">
    <svg width="500" height="500" xmlns="http://www.w3.org/2000/svg">
      <!-- Define a radial gradient -->
      <defs>
        <radialGradient id="grad1" cx="50%" cy="50%" r="50%" fx="50%" fy="50%">
          <stop offset="0%" style="stop-color:rgb(255,255,255);stop-opacity:0" />
          <stop offset="100%" style="stop-color:rgb(0,0,0);stop-opacity:0.75" />
        </radialGradient>
        
        <!-- Define a shadow filter -->
        <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
          <feDropShadow dx="5" dy="5" stdDeviation="5" flood-color="black" />
        </filter>
      </defs>
  
      <!-- Use the gradient as a background -->
      <rect width="100%" height="100%" fill="url(#grad1)" />
      
      <!-- Define an image with a shadow filter -->
      <image href="https://github.com/teaglebuilt/teaglebuilt/raw/master/images/teaglebuilt.png" x="50" y="50" width="400" height="400"                   filter="url(#shadow)" />
  
      <!-- Define some animated text -->
      <text x="50%" y="475" dominant-baseline="middle" text-anchor="middle" fill="white" font-size="30" font-family="Arial" stroke="black"               stroke-width="1">
        <animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite"/>
        TeagleBuilt
      </text>
  </svg>
</div>

<div align="center">
    <a href="https://www.linkedin.com/in/teaglebuilt" target="#">
        <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white">
    </a>
    <a href="https://twitter.com/teaglebuilt" target="#">
        <img src="https://img.shields.io/badge/teaglebuilt-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white">
    </a>
    <a href="https://dev.to/teaglebuilt" target="#">
        <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white">
    </a>
    <img src="https://img.shields.io/badge/rss-F88900?style=for-the-badge&logo=rss&logoColor=white">
</div>
<br/>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,azure,kubernetes,docker,linux,python,golang,typescript,bash,git,nix,lua,webassembly,react,nest,ansible,terraform,elasticsearch&perline=9" />
  </a>
</p>

<!-- <div>
<br/>
    <h1 align="center">
       <img src="./images/showcase.png" height="60px"/> The Showcase
    </h2>
    <br/>
    <ul style="list-style:none; display:flex; align-items: center;">
        <li style="margin: 20px">
            <p>Built At Home</p>
        </li>
        <li style="margin: 20px">
            <p>Dotfiles</p>
        </li>
    </ul>
</div> -->
