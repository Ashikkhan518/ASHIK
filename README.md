<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garena Style Top-Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #333;
            background-image: url('https://web.garena.com/images/home_bg.jpg'); /* Example Garena like background */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }

        .container {
            background-color: rgba(255, 255, 255, 0.9); /* Slightly transparent white background */
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 500px;
            width: 90%;
            border: 2px solid #ff5722; /* Orange border for highlight */
        }

        .logo {
            margin-bottom: 25px;
        }

        .logo img {
            max-width: 150px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
        }

        h1 {
            color: #ff5722; /* Garena orange color */
            margin-bottom: 15px;
            font-size: 2.2em;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        p {
            font-size: 1.1em;
            line-height: 1.6;
            margin-bottom: 30px;
            color: #555;
        }

        .btn-container {
            margin-top: 30px;
        }

        .btn {
            display: inline-block;
            background-color: #ff5722; /* Garena orange */
            color: #fff;
            padding: 15px 30px;
            border-radius: 8px;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: bold;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 10px rgba(255, 87, 34, 0.4);
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #e64a19; /* Darker orange on hover */
            transform: translateY(-2px);
        }

        .btn:active {
            transform: translateY(0);
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .container {
                padding: 25px;
            }
            h1 {
                font-size: 1.8em;
            }
            p {
                font-size: 1em;
            }
            .btn {
                padding: 12px 25px;
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="f982b22d-4dd1-4db5-a9fc-a1315ec9c827.jpeg" alt="Top-Up Site Logo">
        </div>
        <h1>আপনার পছন্দের গেম টপ-আপ করুন</h1>
        <p>সহজ এবং নিরাপদ উপায়ে আপনার গেমের ক্রেডিট রিচার্জ করুন। সেরা ডিল এবং দ্রুত সার্ভিস!</p>
        <div class="btn-container">
            <a href="Profile page html" class="btn">এখনই টপ-আপ করুন</a>
        </div>
    </div>
</body>
</html>

