<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dry For You - Kuru Temizleme & Terzi</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f8fb;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #ffffff;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            color: #0056b3;
            letter-spacing: -1px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #555;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #0056b3;
        }

        #hero {
            background: linear-gradient(135deg, #0056b3, #0099ff);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        #hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        #hero p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        #subeler, #iletisim {
            padding: 60px 20px;
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }

        h2 {
            color: #0056b3;
            margin-bottom: 40px;
            font-size: 2rem;
        }

        .branch-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .branch-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            width: 320px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
            text-align: center;
            padding-bottom: 20px;
        }

        .branch-card:hover {
            transform: translateY(-5px);
        }

        .branch-title {
            background-color: #0056b3;
            color: white;
            font-size: 1.5rem;
            font-weight: bold;
            padding: 30px 20px;
            margin-bottom: 20px;
