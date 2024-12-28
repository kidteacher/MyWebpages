# MyWebpages
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }
        .hero {
            position: relative;
            height: 100vh;
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('background.jpg') no-repeat center center/cover;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.5rem;
            margin: 20px 0;
        }
        .hero button {
            padding: 10px 20px;
            font-size: 1.2rem;
            color: #fff;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .hero button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <section class="hero">
        <div>
            <h1>Innovative Robotics and Design</h1>
            <p>Exploring the world of physical computing through hands-on projects and creative solutions.</p>
            <button onclick="window.location.href='#projects'">View My Projects</button>
        </div>
    </section>
</body>
</html>
