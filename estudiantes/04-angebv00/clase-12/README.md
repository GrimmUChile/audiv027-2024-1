# Codigo posenet
```
<!DOCTYPE html>
<html>

<head>
    <title>PoseNet - Camera Feed Demo</title>
    <link rel="stylesheet" href="/posenet-sketchbook/style.d2841a7d.css">
    <link rel="icon" href="/posenet-sketchbook/favicon.a0c961ca.ico" type="image/png">
    <!-- fonts -->
    <link href="https://fonts.googleapis.com/css?family=Oswald" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Archivo+Black" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Roboto+Mono" rel="stylesheet">
</head>

<body>
    <div id="info" style="display:none">
    </div>
    <div id="loading">
        Loading the model...
    </div>
    <div id="main" style="display:none">
        <div id="record-button-container">
                <button id="start-loop" contenteditable="false">Start recording loop</button>
                <button id="stop-loop" contenteditable="false">Stop recording loop</button>
            </div>
        <video id="video" playsinline="" style=" -moz-transform: scaleX(-1);
        -o-transform: scaleX(-1);
        -webkit-transform: scaleX(-1);
        transform: scaleX(-1);
        display: none;
        ">
        </video>
        <div id="canvas-container">
                <canvas id="livestream"></canvas>
                <canvas id="output"></canvas>
        </div>
        <div id="loopingCanvas-container"></div>
    </div>
    <script src="/posenet-sketchbook/main.8dfc7d0a.js"></script>
</body>

</html>
```
![imagen](https://github.com/angebv00/audiv027-2024-1/assets/163590234/3cc36af7-92fa-493d-a746-bae426c24b81)
