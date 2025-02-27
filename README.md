## Hi there 👋

<!--
**Iman6658/Iman6658** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>گالری NFT من</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            width: 100%;
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            padding: 20px;
            width: 100%;
            max-width: 1200px;
        }
        .gallery-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .gallery-item:hover {
            transform: scale(1.05);
        }
        .gallery-item img {
            width: 100%;
            height: auto;
        }
        .gallery-item .description {
            padding: 15px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>گالری NFT من</h1>
    </header>
    <div class="gallery">
        <!-- آیتم‌های گالری -->
        <div class="gallery-item">
            <img src="nft1.jpg" alt="NFT 1">
            <div class="description">توضیح کوتاه درباره NFT 1</div>
        </div>
        <div class="gallery-item">
            <img src="nft2.jpg" alt="NFT 2">
            <div class="description">توضیح کوتاه درباره NFT 2</div>
        </div>
        <!-- آیتم‌های بیشتر را می‌توانید به همین شکل اضافه کنید -->
    </div>
</body>
</html>
