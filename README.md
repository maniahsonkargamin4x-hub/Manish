index.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI Prompt Hub</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header class="top">
  <div class="logo">✳ AI Prompt <span>Hub</span>
    <small>Dream • Prompt • Create</small>
  </div>
  <nav>
    <a href="#">⌂ Home</a>
    <a href="#categories">▦ Categories</a>
    <a href="#trending">★ Top Prompts</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>
  <button class="login">Login / Sign Up</button>
</header>

<div class="layout">

<aside class="side">
<a class="active" href="#categories">▦ All Categories</a>
<a href="#categories">▧ AI Image Prompts</a>
<a href="#categories">✣ Photo Editing Prompts</a>
<a href="#categories">◉ AI Art Prompts</a>
<a href="#categories">♛ Fantasy Prompts</a>
<a href="#categories">★ Anime Prompts</a>
<a href="#categories">♥ Girl & Boy Prompts</a>
<a href="#categories">❀ Nature Prompts</a>
<a href="#categories">🎮 Gaming Prompts</a>
<a href="#categories">◇ 3D & Cartoon Prompts</a>

<div class="premium">
👑 <b>Premium Prompts</b>
<p>Unlock exclusive prompts!</p>
<button>Go Premium →</button>
</div>

<div class="stats">
👥 1M+ Happy Users<br><br>
⭐ 4.9/5 User Rating<br><br>
🚀 99% Success Rate
</div>
</aside>

<main class="main">

<section class="hero">
<span>⚡ Next Level AI Creativity</span>
<h1>AI Prompt <span class="gradient">Hub</span></h1>
<p>Get the Best AI Prompts for
<b>Stunning Images</b>, Creative Edits & Amazing Results!</p>

<div class="search">
<input id="q" placeholder="Search for prompts...">
<button onclick="searchPrompts()">🚀 Search</button>
</div>

<div class="chips">
<span class="chip">⚡ 1000+ Prompts</span>
<span class="chip">⭐ High Quality</span>
<span class="chip">⚡ Free to Use</span>
<span class="chip">💎 Regular Updates</span>
</div>
<div class="person">🧑🏻‍💻</div>
</section>

<section class="section" id="categories">
<h2 class="heading">🌟 Popular Categories</h2>

<div class="categories">
<div class="card"><div class="art">🏞️</div><b>AI Image Prompts</b><small>100+ Prompts</small></div>
<div class="card"><div class="art">📸</div><b>Photo Editing Prompts</b><small>100+ Prompts</small></div>
<div class="card"><div class="art">🦁</div><b>AI Art Prompts</b><small>100+ Prompts</small></div>
<div class="card"><div class="art">🏰</div><b>Fantasy Prompts</b><small>100+ Prompts</small></div>
<div class="card"><div class="art">🎮</div><b>Gaming Prompts</b><small>100+ Prompts</small></div>
<div class="card"><div class="art">🧸</div><b>3D & Cartoon Prompts</b><small>100+ Prompts</small></div>
</div>
</section>

<section class="section">
<div class="prompt-detail">

<img class="example-image"
src="https://i.ibb.co/KjYGZqk6/IMG-20261006-071127.jpg"
alt="AI Prompt Example">

<h2>✨ AI IMAGE PROMPT</h2>
<h3>📌 Cinematic Portrait Prompt</h3>

<div class="prompt-text" id="mainPrompt">
Create an ultra-realistic cinematic portrait of a stylish young Indian man wearing a premium black shirt with rolled-up sleeves and black rectangular sunglasses. He has thick, naturally curly, voluminous dark hair, a clean youthful face, and a confident expression.

Dark cinematic background with glowing orange and golden light particles, dramatic warm lighting from the upper right side, subtle orange rim lighting around the hair and shoulders.

Premium professional photoshoot, realistic skin texture, highly detailed facial features, sharp focus, DSLR photography, shallow depth of field, luxurious dark atmosphere, rich contrast, 85mm portrait lens, 8K Ultra HD, photorealistic.

Keep the original face and facial identity unchanged.
</div>

<button class="copy" onclick="copyPrompt('mainPrompt',this)">
📋 Copy Main Prompt
</button>

<h3>⚡ Holographic 3D Portrait Prompt</h3>

<div class="prompt-text" id="hologramPrompt">
Create an ultra-realistic cinematic portrait of a stylish young Indian man wearing a premium black shirt and black rectangular sunglasses.

The man is standing in a futuristic pose with both hands extended forward, presenting a magical holographic projection.

Create a smaller glowing holographic 3D duplicate of the same person in front of his chest.

Surround the hologram with neon blue energy rings, glowing digital grids, scanning lines and floating particles.

Background: Deep black cinematic atmosphere with electric blue smoke on the left and dramatic red smoke on the right.

Lighting: Intense blue neon illumination, red rim lighting, realistic skin texture, cinematic shadows and volumetric lighting.

Full vertical portrait, subject centered, 8K Ultra HD, photorealistic.

Preserve the original person's face and identity.
</div>

<button class="copy" onclick="copyPrompt('hologramPrompt',this)">
📋 Copy Hologram Prompt
</button>

<p class="status" id="status"></p>

</div>
</section>

<section class="section" id="trending">
<h2 class="heading">🔥 Trending Prompts</h2>

<div class="trending" id="list">

<div class="prompt" data-key="indian flag cinematic photo">
<div class="pic">🇮🇳</div>
<p>Indian Flag Cinematic Photo</p>
<button onclick="copyDirect(this,'Create a cinematic portrait with a respectful Indian flag, sunset lighting and realistic photography.')">Copy Prompt</button>
</div>

<div class="prompt" data-key="stylish girl garden photo">
<div class="pic">🌸</div>
<p>Stylish Girl Photo Prompt</p>
<button onclick="copyDirect(this,'Create a stylish garden portrait with flowers, natural lighting and realistic details.')">Copy Prompt</button>
</div>

<div class="prompt" data-key="cyberpunk neon style">
<div class="pic">🌃</div>
<p>Cyberpunk Style Prompt</p>
<button onclick="copyDirect(this,'Create a cyberpunk city portrait with glowing purple and cyan neon lights and cinematic atmosphere.')">Copy Prompt</button>
</div>

<div class="prompt" data-key="royal king photo">
<div class="pic">👑</div>
<p>Royal King Photo Prompt</p>
<button onclick="copyDirect(this,'Create a royal king portrait in a grand palace with golden details and cinematic lighting.')">Copy Prompt</button>
</div>

<div class="prompt" data-key="dragon fantasy">
<div class="pic">🐉</div>
<p>Dragon Fantasy Prompt</p>
<button onclick="copyDirect(this,'Create an epic blue fantasy dragon above a magical kingdom with cinematic lighting.')">Copy Prompt</button>
</div>

</div>
</section>

<footer id="about">
✳ AI Prompt Hub | Privacy Policy | Terms & Conditions
<p id="contact">Contact Us: hello@example.com</p>
<p>Follow Us: ▶️ ✈️ 📸 🐦 ⓕ</p>
💜 Powered by AI ✨
</footer>

</main>
</div>

<script src="script.js"></script>
</body>
</html>
