
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Official webpage of Harmony Heights, featuring our latest music, tour dates, and exclusive content for our fans.">
    <title>Harmony Heights: Feel the Music</title>
    <style>
        /* Modern Band Aesthetic Design */
        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: #121212; /* Dark theme */
            color: #ffffff;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://edube.org/uploads/media/default/0001/04/band-photo.jpg');
            background-size: cover;
            background-position: center;
            padding: 100px 20px;
            text-align: center;
        }

        h1 {
            font-size: 3.5rem;
            color: #ff3e3e; /* Electric Red */
            text-transform: uppercase;
            margin-bottom: 10px;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        h2 {
            border-left: 5px solid #ff3e3e;
            padding-left: 15px;
            margin-top: 50px;
            color: #ff3e3e;
            text-transform: uppercase;
        }

        .member-gallery {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 30px;
        }

        .member-gallery img {
            width: 250px;
            height: 300px;
            object-fit: cover;
            border-radius: 10px;
            border: 2px solid #333;
            transition: transform 0.3s;
        }

        .member-gallery img:hover {
            transform: scale(1.05);
            border-color: #ff3e3e;
        }

        audio, video {
            width: 100%;
            margin-top: 15px;
            background-color: #333;
            border-radius: 8px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            background: #1e1e1e;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        a {
            color: #ff3e3e;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        .social-links a {
            display: inline-block;
            background: #333;
            padding: 10px 20px;
            margin: 5px 0;
            border-radius: 5px;
            width: 150px;
            text-align: center;
        }

        form {
            background: #1e1e1e;
            padding: 30px;
            border-radius: 10px;
            margin-top: 20px;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin-top: 5px;
            background: #333;
            border: 1px solid #444;
            color: white;
            border-radius: 5px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background: #ff3e3e;
            color: white;
            border: none;
            font-weight: bold;
            cursor: pointer;
            margin-top: 20px;
            transition: background 0.3s;
        }

        input[type="submit"]:hover {
            background: #cc0000;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Harmony Heights</h1>
        <p style="max-width: 600px; margin: auto; font-size: 1.2rem;">
            We are Harmony Heights, a band that blends genres to create unique sounds. 
            Our journey through music has been incredible, and we're excited to share it with you.
        </p>
    </header>

    <div class="container">
        <div class="member-gallery">
            <img src="https://edube.org/uploads/media/default/0001/04/band-photo.jpg" alt="Harmony Heights Band Photo">
            <img src="https://edube.org/uploads/media/default/0001/04/member1-amy.jpg" alt="Harmony Heights Vocals/Sampling: Amy Duncan">
            <img src="https://edube.org/uploads/media/default/0001/04/member2-john.jpg" alt="Harmony Heights Bass/Guitars: John Smith">
            <img src="https://edube.org/uploads/media/default/0001/04/member3-trevor.jpg" alt="Harmony Heights Drums: Trevor G.">
        </div>

        <h2>Listen to Our Latest Tracks</h2>
        <audio controls>
            <source src="https://edube.org/uploads/media/default/0001/04/track1.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>

        <h2>Watch Our Performances</h2>
        <video controls>
            <source src="https://edube.org/uploads/media/default/0001/04/performance1.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>

        <h2>Upcoming Tour Dates</h2>
        <ul>
            <li>
                March 12, 2029, Orlando, FL 
                <a href="https://example.com/purchase-tickets-harmony-heights-orlando" target="_blank">Get Tickets</a>
            </li>
            <li>
                March 14, 2029, Salt Lake City, UT 
                <a href="https://example.com/purchase-tickets-harmony-heights-slc" target="_blank">Get Tickets</a>
            </li>
        </ul>

        <h2>Follow Us</h2>
        <p>Stay updated with our latest news and releases:</p>
        <div class="social-links">
            <a href="https://www.example.com/faceblock/hh" target="_blank">Faceblock</a><br>
            <a href="https://www.example.com/instagrump/hh" target="_blank">Instagrump</a><br>
            <a href="https://www.example.com/twotter/hh" target="_blank">Twotter</a>
        </div>

        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>

            <label for="subject">Subject:</label><br>
            <input type="text" id="subject" name="subject" required><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="5" required></textarea><br>

            <input type="submit" value="Send">
        </form>
    </div>

    <footer style="text-align: center; padding: 40px; color: #666; font-size: 0.8rem;">
        &copy; 2026 Harmony Heights. All Rights Reserved.
    </footer>

</body>
</html>
