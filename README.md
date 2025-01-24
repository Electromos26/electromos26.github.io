<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full-Screen PDF Viewer</title>
    <style>
        /* Set the body and HTML to take up the full viewport */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden; /* Prevent scrollbars */
        }

        /* Ensure the iframe spans the full screen */
        iframe {
            position: absolute; /* Positioned relative to the viewport */
            top: 0;
            left: 0;
            width: 100%; /* Full width of the screen */
            height: 100%; /* Full height of the screen */
            border: none; /* No borders around the iframe */
        }
    </style>
</head>
<body>
    <iframe src="Assets/MusseHidru_Portfolio.pdf"></iframe>
</body>
</html>

