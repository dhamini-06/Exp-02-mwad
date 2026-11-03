# Ex02 Commercial Website
## Date:03-11-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

index.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Dream Cafe</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Nunito:wght@400;600;700;800&family=Special+Elite&display=swap" rel="stylesheet">
</head>

<body>

<header>
    <div class="logo">
        ANIME DREAM <span>CAFE.</span>
        <p>THE ULTIMATE MANGA DESSERT EXPERIENCE</p>
    </div>

    <nav>
        <a href="#home">HOME</a>
        <a href="#anime">ANIME WORLD</a>
        <a href="#menu">MENU</a>
        <a href="#special">SPECIALS</a>
        <a href="#contact">CONTACT</a>
    </nav>
</header>

<!-- HERO -->

<section class="hero" id="home">
    <div class="hero-content">
        <span class="eyebrow">VOL. 01 — THE SWEETEST CHAPTER</span>
        <h1>WELCOME TO THE<br><span>ANIME UNIVERSE!</span></h1>
        <p>
            Where your favourite anime worlds meet Japanese desserts.
            Step inside, explore the manga atmosphere and enjoy
            something sweet.
        </p>
        <a href="#menu" class="btn">EXPLORE THE MENU →</a>
    </div>

    <div class="hero-art">
        <img
            src="https://img3.hulu.com/user/v3/artwork/382ec8bf-3650-4cde-94db-ecd18665f9e0?base_image=d9f2b170-5a06-4b7a-a9d9-307212895c68&base_image_bucket_name=image_manager&format=webp&size=550x825"
            alt="Jujutsu Kaisen characters Yuji and Gojo">
        <div class="hero-caption">YOUR NEXT FAVOURITE CHAPTER STARTS HERE.</div>
    </div>

    <div class="hero-stamp">夢<br>CAFE</div>
</section>

<!-- ANIME WORLD -->

<section class="anime-world" id="anime">
    <div class="section-heading">
        <span>CHAPTER 01 / OUR ANIME COLLECTION</span>
        <h2>ENTER THE ANIME WORLD</h2>
        <p>Three legendary worlds. One unforgettable café.</p>
    </div>

    <div class="anime-grid">

        <article class="anime-card">
            <div class="anime-image">
                <img
                    src="jujutsu.jpg"
                    alt="Yuji Itadori and Satoru Gojo from Jujutsu Kaisen">
                <span class="image-number">01</span>
            </div>
            <div class="anime-info">
                <span class="series-label">CURSED ENERGY</span>
                <h3>JUJUTSU KAISEN</h3>
                <p>Meet the world of sorcerers, curses and powerful friendships.</p>
            </div>
        </article>

        <article class="anime-card">
            <div class="anime-image">
                <img
                    src="demon slayer.jpg"
                    alt="Tanjiro and Nezuko from Demon Slayer">
                <span class="image-number">02</span>
            </div>
            <div class="anime-info">
                <span class="series-label">BREATH OF FLAVOUR</span>
                <h3>DEMON SLAYER</h3>
                <p>Celebrate courage, family and the beautiful world of demon slayers.</p>
            </div>
        </article>

        <article class="anime-card">
            <div class="anime-image">
                <img
                    src="attack on titan.webp"
                    alt="Levi and Mikasa from Attack on Titan">
                <span class="image-number">03</span>
            </div>
            <div class="anime-info">
                <span class="series-label">FREEDOM AND COURAGE</span>
                <h3>ATTACK ON TITAN</h3>
                <p>Enter a world of mystery, adventure and unforgettable heroes.</p>
            </div>
        </article>

    </div>
</section>

<!-- MANGA QUOTE -->

<section class="quote-section">
    <div class="quote-mark">“</div>
    <h2>EVERY GREAT STORY<br>DESERVES A SWEET ENDING.</h2>
    <p>— ANIME DREAM CAFE</p>
</section>

<!-- SAKURA DESSERT MENU -->

<section class="menu" id="menu">
    <div class="section-heading">
        <span>CHAPTER 02 / JAPANESE DESSERT COLLECTION</span>
        <h2>SAKURA SWEET MENU</h2>
        <p>A little taste of Japanese happiness!</p>
    </div>

    <div class="menu-container">

        <article class="food-card">
            <img src="mochi.jpg"
                 alt="Strawberry dessert">
            <div class="food-info">
                <span>01 / SIGNATURE SWEET</span>
                <h3>Strawberry Mochi</h3>
                <p>Soft Japanese rice cake filled with sweet strawberry cream.</p>
                <h4>₹140</h4>
            </div>
        </article>

        <article class="food-card">
            <img src="takiyaki.jpg"
                 alt="Japanese dessert">
            <div class="food-info">
                <span>02 / CLASSIC JAPANESE</span>
                <h3>Classic Taiyaki</h3>
                <p>Traditional fish-shaped Japanese cake with sweet filling.</p>
                <h4>₹120</h4>
            </div>
        </article>

        <article class="food-card">
            <img src="dorayaki.jpg"
                 alt="Chocolate cake">
            <div class="food-info">
                <span>03 / CHOCOLATE SPECIAL</span>
                <h3>Chocolate Dorayaki</h3>
                <p>Fluffy Japanese pancakes filled with chocolate cream.</p>
                <h4>₹150</h4>
            </div>
        </article>

        <article class="food-card">
            <img src="tiramisu.jpg"
                 alt="Matcha dessert">
            <div class="food-info">
                <span>04 / MATCHA COLLECTION</span>
                <h3>Matcha Tiramisu</h3>
                <p>Creamy layered dessert with authentic Japanese matcha flavour.</p>
                <h4>₹220</h4>
            </div>
        </article>

        <article class="food-card">
            <img src="hanami.jpg"
                 alt="Colourful dessert">
            <div class="food-info">
                <span>05 / TRADITIONAL TREAT</span>
                <h3>Hanami Dango</h3>
                <p>Colourful Japanese rice dumplings inspired by cherry blossoms.</p>
                <h4>₹110</h4>
            </div>
        </article>

        <article class="food-card">
            <img src="cheesecake.jpg"
                 alt="Cheesecake">
            <div class="food-info">
                <span>06 / CHEF'S SPECIAL</span>
                <h3>Japanese Cheesecake</h3>
                <p>Light, fluffy and soft Japanese-style cheesecake.</p>
                <h4>₹190</h4>
            </div>
        </article>

    </div>
</section>

<!-- SPECIAL COMBO -->

<section class="special" id="special">
    <div class="special-content">
        <span>CHAPTER 03 / LIMITED EDITION</span>
        <h2>SAKURA DREAM BOX</h2>
        <p>
            Enjoy a delicious combination of strawberry mochi,
            dorayaki and a refreshing matcha drink.
        </p>
        <h3>₹299</h3>
        <a href="#contact" class="btn">ORDER YOUR BOX →</a>
    </div>

    <div class="special-art">
        <span>🍓</span>
        <span>🍡</span>
        <span>🍵</span>
    </div>
</section>

<!-- ABOUT -->

<section class="about">
    <span>CHAPTER 04 / OUR STORY</span>
    <h2>A CAFE STRAIGHT OUT OF A MANGA</h2>
    <p>
        Anime Dream Café brings together Japanese culture,
        traditional desserts and the worlds of anime.
        Our space is inspired by manga pages, iconic characters
        and the creativity of Japanese storytelling.
    </p>
    <p>
        Whether you are a Jujutsu Kaisen fan, a Demon Slayer
        enthusiast or an Attack on Titan follower, there is
        something special waiting for you.
    </p>
    <h3>「夢と甘さ」 — DREAMS AND SWEETNESS</h3>
</section>

<!-- CONTACT -->

<section class="contact" id="contact">
    <span>CHAPTER 05 / FIND US</span>
    <h2>VISIT OUR CAFE</h2>
    <p>Every anime lover is welcome here!</p>

    <div class="contact-info">
        <p>📍 Chennai, Tamil Nadu</p>
        <p>📞 +91 98765 43210</p>
        <p>✉ animedream@gmail.com</p>
        <p>🕒 10:00 AM – 9:00 PM</p>
    </div>

    <form onsubmit="event.preventDefault(); alert('Thank you for contacting Anime Dream Cafe!');">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">SEND MESSAGE →</button>
    </form>
</section>

<footer>
    <h2>ANIME DREAM CAFE.</h2>
    <p>THE END? NEVER. JUST THE NEXT CHAPTER.</p>
    <p>© 2026 Anime Dream Café. All Rights Reserved.</p>
</footer>

</body>
</html>
```

style.css

```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Nunito', sans-serif;
    color: #171717;
    background-color: #eeeae0;

    background-image:
        radial-gradient(#bcb8ae 0.7px, transparent 0.7px);
    background-size: 5px 5px;
}

/* HEADER */

header {
    background: #111;
    color: white;
    padding: 20px 6%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    border-bottom: 5px solid #c90019;
}

.logo {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 32px;
    letter-spacing: 2px;
}

.logo span {
    color: #ed1c24;
}

.logo p {
    font-family: 'Nunito', sans-serif;
    font-size: 10px;
    letter-spacing: 2px;
    color: #ccc;
}

nav a {
    text-decoration: none;
    color: white;
    font-size: 13px;
    font-weight: 800;
    margin-left: 20px;
    transition: 0.3s;
}

nav a:hover {
    color: #ff2538;
}

/* HERO */

.hero {
    min-height: 570px;
    padding: 65px 9%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 40px;
    position: relative;
    overflow: hidden;

    background:
        linear-gradient(120deg, #f7f5ed 60%, #dedbd2 60%);
    border-bottom: 5px solid #111;
}

.hero::after {
    content: "";
    position: absolute;
    inset: 0;
    pointer-events: none;

    background-image:
        radial-gradient(#111 0.8px, transparent 0.8px);
    background-size: 9px 9px;
    opacity: 0.10;
}

.hero-content {
    max-width: 570px;
    position: relative;
    z-index: 2;
}

.eyebrow,
.section-heading span,
.special-content span,
.about > span,
.contact > span {
    font-family: 'Special Elite', cursive;
    font-size: 12px;
    color: #c90019;
    letter-spacing: 2px;
    font-weight: bold;
}

.hero h1 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 76px;
    line-height: 0.98;
    margin: 25px 0;
    letter-spacing: 2px;
}

.hero h1 span {
    color: #c90019;
    text-shadow: 3px 3px 0 #111;
}

.hero-content p {
    max-width: 470px;
    line-height: 1.9;
    margin-bottom: 30px;
    font-size: 16px;
}

.btn {
    display: inline-block;
    background: #c90019;
    color: white;
    text-decoration: none;
    padding: 14px 25px;
    border: 3px solid #111;
    font-weight: 800;
    box-shadow: 5px 5px 0 #111;
    transition: 0.3s;
}

.btn:hover {
    background: #111;
    transform: translate(3px, 3px);
    box-shadow: 2px 2px 0 #c90019;
}

.hero-art {
    width: 320px;
    background: white;
    padding: 10px;
    border: 4px solid #111;
    box-shadow: 12px 12px 0 #c90019;
    transform: rotate(3deg);
    position: relative;
    z-index: 2;
}

.hero-art img {
    width: 100%;
    height: 340px;
    object-fit: cover;
    display: block;
    filter: grayscale(15%);
}

.hero-caption {
    font-family: 'Special Elite', cursive;
    text-align: center;
    padding: 12px 5px 5px;
    font-size: 11px;
    font-weight: bold;
}

.hero-stamp {
    position: absolute;
    right: 35%;
    bottom: 35px;
    background: #c90019;
    color: white;
    font-family: 'Bebas Neue', sans-serif;
    font-size: 24px;
    text-align: center;
    padding: 12px;
    border: 3px solid #111;
    transform: rotate(-12deg);
    z-index: 3;
}

.hero::before {
    content: "!";
    position: absolute;
    right: 8%;
    top: 20px;
    font-family: 'Bebas Neue', sans-serif;
    font-size: 150px;
    color: #c90019;
    opacity: 0.12;
}

/* ANIME WORLD */

.anime-world {
    padding: 80px 7%;
    background: #e8e5dc;
    border-bottom: 5px solid #111;
}

.section-heading {
    text-align: center;
    margin-bottom: 40px;
}

.section-heading h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 48px;
    margin: 12px 0;
    letter-spacing: 2px;
}

.section-heading p {
    color: #555;
}

.anime-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.anime-card {
    background: #fff;
    border: 4px solid #111;
    box-shadow: 7px 7px 0 #111;
    transition: 0.3s;
}

.anime-card:hover {
    transform: translateY(-8px) rotate(-1deg);
    box-shadow: 10px 12px 0 #c90019;
}

.anime-image {
    height: 310px;
    position: relative;
    overflow: hidden;
    border-bottom: 4px solid #111;
    background: #ccc;
}

.anime-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: 0.4s;
}

.anime-card:hover .anime-image img {
    transform: scale(1.06);
}

.image-number {
    position: absolute;
    top: 10px;
    left: 10px;
    background: #c90019;
    color: white;
    padding: 7px 12px;
    font-family: 'Bebas Neue', sans-serif;
    font-size: 20px;
    border: 2px solid #111;
}

.anime-info {
    padding: 20px;
}

.series-label {
    color: #c90019;
    font-family: 'Special Elite', cursive;
    font-size: 11px;
    font-weight: bold;
}

.anime-info h3 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 29px;
    margin: 8px 0;
}

.anime-info p {
    color: #555;
    line-height: 1.7;
    font-size: 14px;
}

/* MANGA QUOTE */

.quote-section {
    background: #111;
    color: white;
    text-align: center;
    padding: 70px 15%;
    position: relative;
    overflow: hidden;
}

.quote-section::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
        radial-gradient(#777 0.8px, transparent 0.8px);
    background-size: 7px 7px;
    opacity: 0.18;
}

.quote-mark {
    color: #ed1c24;
    font-family: Georgia, serif;
    font-size: 90px;
    height: 65px;
    position: relative;
}

.quote-section h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 46px;
    letter-spacing: 2px;
    margin: 20px 0;
    position: relative;
}

.quote-section p {
    color: #ed1c24;
    letter-spacing: 3px;
    font-family: 'Special Elite', cursive;
    position: relative;
}

/* MENU */

.menu {
    padding: 80px 7%;
    background: #f4f1e8;
    border-bottom: 5px solid #111;
}

.menu-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.food-card {
    background: white;
    border: 3px solid #111;
    box-shadow: 6px 6px 0 #111;
    transition: 0.3s;
}

.food-card:hover {
    transform: translateY(-7px);
    box-shadow: 9px 10px 0 #c90019;
}

.food-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    display: block;
    border-bottom: 3px solid #111;
}

.food-info {
    padding: 20px;
}

.food-info span {
    font-family: 'Special Elite', cursive;
    color: #c90019;
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 1px;
}

.food-info h3 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 27px;
    margin: 10px 0;
}

.food-info p {
    color: #555;
    font-size: 14px;
    line-height: 1.7;
}

.food-info h4 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 27px;
    color: #c90019;
    margin-top: 15px;
}

/* SPECIAL */

.special {
    padding: 75px 10%;
    background: #c90019;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
    border-bottom: 5px solid #111;
}

.special-content {
    max-width: 600px;
}

.special-content span {
    color: #fff;
}

.special h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 55px;
    color: white;
    margin: 15px 0;
}

.special p {
    line-height: 1.8;
    margin-bottom: 15px;
}

.special h3 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 38px;
    margin-bottom: 20px;
}

.special .btn {
    background: white;
    color: #111;
}

.special .btn:hover {
    background: #111;
    color: white;
}

.special-art {
    width: 220px;
    height: 220px;
    background: #f4f1e8;
    border: 5px solid #111;
    box-shadow: 10px 10px 0 #111;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 5px;
    font-size: 48px;
    transform: rotate(4deg);
}

/* ABOUT */

.about {
    padding: 80px 15%;
    text-align: center;
    background: #e8e5dc;
    border-bottom: 5px solid #111;
}

.about h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 44px;
    margin: 15px 0;
}

.about p {
    color: #444;
    line-height: 1.9;
    margin: 15px 0;
}

.about h3 {
    font-family: 'Special Elite', cursive;
    color: #c90019;
    margin-top: 25px;
}

/* CONTACT */

.contact {
    padding: 75px 10%;
    text-align: center;
    background: #f4f1e8;
}

.contact h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 45px;
    margin: 15px 0;
}

.contact-info {
    margin: 25px 0;
    line-height: 2.2;
}

form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

input,
textarea {
    padding: 14px;
    border: 2px solid #111;
    background: white;
    font-family: 'Nunito', sans-serif;
    outline: none;
}

input:focus,
textarea:focus {
    border-color: #c90019;
}

textarea {
    height: 110px;
    resize: vertical;
}

button {
    padding: 15px;
    border: 3px solid #111;
    background: #c90019;
    color: white;
    font-weight: 800;
    font-size: 15px;
    cursor: pointer;
    box-shadow: 5px 5px 0 #111;
    transition: 0.3s;
}

button:hover {
    background: #111;
    transform: translate(3px, 3px);
    box-shadow: 2px 2px 0 #c90019;
}

/* FOOTER */

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 35px 15px;
    line-height: 2;
    border-top: 5px solid #c90019;
}

footer h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 35px;
    letter-spacing: 2px;
    color: #ed1c24;
}

footer p {
    font-family: 'Special Elite', cursive;
    font-size: 12px;
}

/* RESPONSIVE */

@media (max-width: 900px) {
    .hero h1 {
        font-size: 58px;
    }

    .anime-grid,
    .menu-container {
        grid-template-columns: repeat(2, 1fr);
    }

    .hero-art {
        width: 260px;
    }

    .hero-art img {
        height: 290px;
    }
}

@media (max-width: 650px) {
    header {
        flex-direction: column;
        gap: 18px;
        text-align: center;
    }

    nav {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 12px;
    }

    nav a {
        margin: 0;
        font-size: 11px;
    }

    .hero {
        flex-direction: column;
        text-align: center;
        padding: 60px 7%;
    }

    .hero h1 {
        font-size: 48px;
    }

    .hero-art {
        width: 80%;
        max-width: 320px;
    }

    .hero-stamp {
        right: 8%;
        bottom: 20px;
    }

    .anime-grid,
    .menu-container {
        grid-template-columns: 1fr;
    }

    .anime-image {
        height: 280px;
    }

    .special {
        flex-direction: column;
        text-align: center;
    }

    .special h2 {
        font-size: 42px;
    }

    .special-art {
        width: 180px;
        height: 180px;
        font-size: 38px;
    }

    .quote-section {
        padding: 60px 8%;
    }

    .quote-section h2 {
        font-size: 35px;
    }

    .about {
        padding: 65px 8%;
    }
}
```


## OUTPUT

![alt text](../1.png)

![alt text](../2.png)

![alt text](../3.png)

![alt text](../5.png)

![alt text](../6.png)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.