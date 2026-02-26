# Mine-forever-
<!DOCTYPE html>
<html>
<head>
    <title>For My Love ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            font-family: 'Segoe UI', sans-serif;
            text-align: center;
            color: white;
            overflow-x: hidden;
        }

        .container {
            margin-top: 80px;
            padding: 20px;
            animation: fadeIn 2s ease-in-out;
        }

        h1 {
            font-size: 45px;
        }

        p {
            font-size: 20px;
            width: 85%;
            margin: auto;
            line-height: 1.6;
        }

        button {
            margin-top: 25px;
            padding: 14px 30px;
            font-size: 18px;
            border: none;
            border-radius: 30px;
            background-color: white;
            color: #ff4b6e;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            transform: scale(1.05);
            background-color: #ffe6ec;
        }

        video {
            margin-top: 30px;
            width: 85%;
            max-width: 500px;
            border-radius: 15px;
            display: none;
            box-shadow: 0 0 20px rgba(0,0,0,0.3);
        }

        audio {
            display: none;
        }

        @keyframes fadeIn {
            from {opacity: 0;}
            to {opacity: 1;}
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>❤️ For My Love ❤️</h1>

        <p>
            From the day you came into my life,  
            everything feels more beautiful.  
            Your smile is my peace,  
            your voice is my favorite sound.  
            This little surprise is just a small reminder  
            of how much you mean to me.
        </p>

        <button onclick="openGift()">Open My Heart 🎁</button>

        <video id="giftVideo" controls>
            <source src="yourvideo.mp4" type="video/mp4">
        </video>

        <audio id="bgMusic" autoplay loop>
            <source src="music.mp3" type="audio/mpeg">
        </audio>
    </div>

    <script>
        function openGift() {
            document.getElementById("giftVideo").style.display = "block";
        }
    </script>

</body>
</html>
