﻿<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Office Games Organizer</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f4f8;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            text-align: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            font-size: 2.5rem;
            color: #333;
            margin-bottom: 20px;
        }

        .category-boxes {
            display: flex;
            justify-content: space-around;
            align-items: center;
            width: 100%;
        }

        .category-box {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 30%;
            margin: 10px;
            text-align: center;
            padding: 20px;
            transition: transform 0.3s;
        }

            .category-box.active:hover {
                transform: scale(1.05);
            }

            .category-box.inactive {
                opacity: 0.5;
                cursor: not-allowed;
            }

                .category-box.inactive:hover {
                    transform: none;
                }

        .emoji {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        .coming-soon {
            font-size: 1rem;
            color: #888;
            margin-top: 10px;
        }

        h2 {
            font-size: 1.5rem;
            color: #555;
        }

        /* Footer styling */
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        /* Responsive styles */
        @media (max-width: 768px) {
            .category-box {
                width: 45%;
            }
        }

        @media (max-width: 480px) {
            .category-box {
                width: 100%;
            }

            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>VR Digital Agency Games</h1>
        <div class="category-boxes">
            <!-- Active category box with link -->
            <a href="https://thesecondletter.github.io/VR_Games/" class="category-box active" style="text-decoration: none; color: inherit;">
                <div class="emoji">🍻</div> <!-- Beer emoji for Drinking Games -->
                <h2>Drinking Games</h2>
            </a>
            <div class="category-box inactive">
                <div class="emoji">❓</div> <!-- Quiz emoji for Quiz Games -->
                <h2>Quiz Games</h2>
                <div class="coming-soon">Coming Soon</div>
            </div>
            <div class="category-box inactive">
                <div class="emoji">🤝</div> <!-- Handshake emoji for Team Building -->
                <h2>Team Building</h2>
                <div class="coming-soon">Coming Soon</div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    
</body>
</html>
