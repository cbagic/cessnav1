<!DOCTYPE html>
<html>
<head>
<title>Cessna Tour</title>
<meta charset="utf-8">
<meta name="viewport" content="target-densitydpi=device-dpi, width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no, minimal-ui" />
<style> @-ms-viewport { width: device-width; } </style>
<link rel="stylesheet" href="vendor/reset.min.css">
<link rel="stylesheet" href="style.css">
</head>
<body class="multiple-scenes ">

<div id="pano"></div>

<div id="sceneList">
  <ul class="scenes">
    
      <a href="javascript:void(0)" class="scene" data-id="0-welcome-to-cessna">
        <li class="text">Welcome to Cessna!</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="1-explore-the-shoreline">
        <li class="text">Explore the Shoreline</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="2-explore-netting">
        <li class="text">Explore Netting</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="3-get-ready-to-build-reefs">
        <li class="text">Get Ready to Build Reefs</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="4-cross-the-water">
        <li class="text">Cross the Water</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="5-keep-going-towards-the-reefs">
        <li class="text">Keep Going Towards the Reefs</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="6-time-to-build-a-reef">
        <li class="text">Time To Build A Reef</li>
      </a>
    
      <a href="javascript:void(0)" class="scene" data-id="7-around-the-point">
        <li class="text">Around the Point</li>
      </a>
    
  </ul>
</div>

<div id="titleBar">
  <h1 class="sceneName"></h1>
</div>

<a href="javascript:void(0)" id="autorotateToggle">
  <img class="icon off" src="img/play.png">
  <img class="icon on" src="img/pause.png">
</a>

<a href="javascript:void(0)" id="fullscreenToggle">
  <img class="icon off" src="img/fullscreen.png">
  <img class="icon on" src="img/windowed.png">
</a>

<a href="javascript:void(0)" id="sceneListToggle">
  <img class="icon off" src="img/expand.png">
  <img class="icon on" src="img/collapse.png">
</a>

<a href="javascript:void(0)" id="viewUp" class="viewControlButton viewControlButton-1">
  <img class="icon" src="img/up.png">
</a>
<a href="javascript:void(0)" id="viewDown" class="viewControlButton viewControlButton-2">
  <img class="icon" src="img/down.png">
</a>
<a href="javascript:void(0)" id="viewLeft" class="viewControlButton viewControlButton-3">
  <img class="icon" src="img/left.png">
</a>
<a href="javascript:void(0)" id="viewRight" class="viewControlButton viewControlButton-4">
  <img class="icon" src="img/right.png">
</a>
<a href="javascript:void(0)" id="viewIn" class="viewControlButton viewControlButton-5">
  <img class="icon" src="img/plus.png">
</a>
<a href="javascript:void(0)" id="viewOut" class="viewControlButton viewControlButton-6">
  <img class="icon" src="img/minus.png">
</a>

<script src="vendor/screenfull.min.js" ></script>
<script src="vendor/bowser.min.js" ></script>
<script src="vendor/marzipano.js" ></script>

<script src="data.js"></script>
<script src="index.js"></script>

</body>
</html>
