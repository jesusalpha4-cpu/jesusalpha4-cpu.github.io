<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alejandro's Website</title>
    <style>
        body {
            /* This sets a Barcelona stadium background that covers the full screen */
            background-image: url('https://images.unsplash.com/photo-1522778119026-d647f0596c20?q=80&w=2070');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        .container {
            /* This creates a semi-transparent dark box so your text is easy to read */
            background-color: rgba(0, 76, 151, 0.85); /* Barcelona Blue with transparency */
            border: 4px solid #A50044; /* Barcelona Deep Red border */
            border-radius: 15px;
            padding: 30px;
            max-width: 600px;
            text-align: center;
            box-shadow: 0 8px 16px rgba(0,0,0,0.5);
        }

        h1 {
            font-size: 24px;
            margin-bottom: 20px;
            line-height: 1.4;
        }

        .description {
            font-size: 18px;
            margin-bottom: 25px;
            line-height: 1.6;
        }

        .messi-img {
            width: 100%;
            max-width: 350px;
            border-radius: 10px;
            border: 3px solid #EDBB00; /* Barcelona Gold border */
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Your main introduction -->
        <h1>Hello My Name Is Alejandro, I really like to play Video games and See or Play Soccer My favorite Team is Barcelona Fc</h1>
        
        <!-- 2 sentence description about Messi -->
        <p class="description">
            Lionel Messi is widely regarded as one of the greatest football players of all time, having spent the majority of his legendary career dominating at Barcelona FC. His incredible dribbling, playmaker vision, and unmatched scoring record brought countless trophies and unforgettable memories to Camp Nou.
        </p>
        
        <!-- Picture of Messi at the bottom -->
        <img class="messi-img" src="https://images.unsplash.com/photo-1508098682722-e99c43a406b2?q=80&w=2070" alt="Lionel Messi playing soccer">
    </div>

</body>
</html>
