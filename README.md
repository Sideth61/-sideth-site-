<!DOCTYPE html>
<html lang="km">
<head>
    <meta charset="UTF-8">
    <title>San Sideth - Portfolio</title>
    <style>
        body { 
            font-family: sans-serif; 
            background-color: #0f172a; 
            background-image: radial-gradient(rgba(56, 189, 248, 0.15) 1px, transparent 1px);
            background-size: 24px 24px;
            color: #fff; 
            text-align: center; 
            padding: 20px; 
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .card { 
            background: rgba(30, 41, 59, 0.85); 
            backdrop-filter: blur(10px);
            padding: 25px; 
            border-radius: 20px; 
            max-width: 400px; 
            width: 100%;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }
        .logo-img { width: 100%; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.3); margin-bottom: 15px; }
        .video-container { position: relative; width: 100%; padding-bottom: 56.25%; height: 0; margin-bottom: 15px; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 10px rgba(0,0,0,0.3); }
        .video-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; }
        h1 { color: #38bdf8; font-size: 22px; margin: 10px 0 5px 0; }
        p { color: #94a3b8; font-size: 13px; margin-bottom: 15px; }
        a { display: block; background: #2563eb; color: #fff; padding: 10px; margin: 8px 0; text-decoration: none; border-radius: 10px; font-weight: bold; transition: 0.3s; font-size: 14px; }
        a:hover { background: #1d4ed8; }
    </style>
</head>
<body>
    <div class="card">
        <!-- រូបឡូហ្គោ -->
        <img src="IMG_2900.png" alt="Logo" class="logo-img">

        <!-- វីដេអូចម្រៀងពី YouTube (បងអាចដូរ Link ខាងក្រោមជាវីដេអូចម្រៀងរបស់បងបាន) -->
        <div class="video-container">
            <iframe src="https://www.youtube.com/embed/Ra8mVoAwNfU" allowfullscreen></iframe>

        </div>

        <h1>សួស្តី! ខ្ញុំ San Sideth</h1>
        <p>Digital Creator & Developer</p>
        
        <a href="https://www.facebook.com/deth61" target="_blank">Facebook Page</a>
        <a href="https://youtube.com/@sideth99" target="_blank">YouTube Channel</a>
        <a href="https://www.tiktok.com/@sideth61" target="_blank">TikTok Shop</a>
    </div>
</body>
</html>
