<!DOCTYPE html>
<html lang="en">
<head>
    <title>Intro to Xaid</title>
    <style>
        /* Apply Papyrus font globally */
        body {
            background-color: black;
            font-family: 'Papyrus', sans-serif; /* Use Papyrus font */
            color: white;
        }

        #blink {
            font-size: 75px;
            transition: 1.9s;
        }

        button {
            font-size: 18px;
            padding: 10px 20px;
            cursor: pointer;
            background-color: #2d38be;
            color: white;
            border: none;
            font-family: 'Papyrus', sans-serif; /* Apply Papyrus to button */
        }

        button:hover {
            background-color: #1f2a7f;
        }

        h2 {
            font-family: 'Papyrus', sans-serif; /* Apply Papyrus to all <h2> tags */
        }
    </style>
</head>
<body>
    <marquee behavior="scroll" direction="left">
        <font face="'Courier New', monospace;">
            <br><br>
            <!-- Apply the blink ID here to make the text blink -->
            <h1 id="blink">Welcome to Xaid Beauty! 🌟</h1>
        </font>
    </marquee>
    <br><br><br><br><br>

    <!-- Your Beauty Index Text -->
    <h2>
        Our Beauty Index highlights top skincare, makeup, and beauty essentials from the hottest brands, carefully selected for their performance, quality, and relevance to current trends.
    </h2>
    <h2>
        Whether you're looking to update your routine or discover the latest must-haves, we ensure you're always in the know. With expert recommendations and insights on emerging beauty trends, the Beauty Index helps you make informed decisions and stay ahead of the curve. From clean beauty to innovative products, it's your go-to guide for discovering what truly works and inspires in the beauty world.
    </h2>

    <br><br><br>
    <button onclick="document.location.href='Hpage.html'">Enter Page</button>

    <script type="text/javascript">
        // Get the element with the id "blink"
        var blink = document.getElementById('blink');
        
        // Set interval to toggle opacity and make text blink every 1.5 seconds
        setInterval(function() {
            blink.style.opacity = (blink.style.opacity == 0 ? 1 : 0);
        }, 1500);
    </script>
</body>
</html>

