[index.html](https://github.com/user-attachments/files/25516597/index.html)
<!DOCTYPE html>
<html>
<head>
    <title>Nilphamari</title>
    <style>
        body {
            text-align: center;
            font-family: Arial;
            background-color: blue;
            color: white;
        }

        h1 {
            color: yellow;
        }

        .box {
            padding: 15px;
            margin: 10px;
            font-weight: bold;
            border-radius: 8px;
        }

        .video { background-color: red; }
        .audio { background-color: green; }
        .pictures { background-color: purple; }
        .blogs { background-color: orange; }
        .books { background-color: brown; }
        .notes { background-color: teal; }
        .study { background-color: darkred; }

        a {
            color: white;
            text-decoration: none;
            display: block;
        }

        footer {
            margin-top: 40px;
            padding: 15px;
            background-color: black;
        }
    </style>
</head>
<body>

    <h1>Welcome to my site</h1>

    <div class="box video"><a href="video.html">Video</a></div>
    <div class="box audio"><a href="audio.html">Audio</a></div>
    <div class="box pictures"><a href="pictures.html">Pictures</a></div>
    <div class="box blogs"><a href="blogs.html">Blogs</a></div>
    <div class="box books"><a href="books.html">Books</a></div>
    <div class="box notes"><a href="notes.html">Notes</a></div>
    <div class="box study"><a href="study.html">Study Materials</a></div>

    <footer>
        <p>Contact us | 
        <a href="https://facebook.com" target="_blank">Visit us on FB</a></p>
        <p>Arafat Zaman</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Video Page</title>
</head>
<body style="background-color: lightblue; text-align: center;">

    <h1>My Video</h1>

    <video width="500" controls>
        <source src="videos/myvideo.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</body>
</html>
