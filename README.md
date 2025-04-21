# Awaash-bunee-primary school 
zerihun website 
Thanks for sharing the file. I reviewed your HTML file for Awaash Bunee Primary School, and here are a few suggestions and fixes to improve it:

1. Fix HTML Structure Issues

There are a couple of unclosed or misused tags that could cause rendering problems:

The CSS block inside .container is broken (includes HTML tag p inside CSS).

<li> tag for "Grades" is missing a closing </a> tag.

There are stray or unclosed tags (</p> without an opening <p>, misplaced <div>).


2. Improved & Cleaned-up Version

Here’s a corrected version of your HTML:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Awaash Bunee Primary School</title>
  <style>
    ul {
      background-color: black;
      color: white;
      display: flex;
      list-style: none;
      padding: 0;
    }

    ul li {
      padding: 20px;
    }

    li a {
      color: white;
      text-decoration: none;
    }

    li a:hover {
      background-color: green;
      font-size: 20px;
    }

    .container {
      max-width: 1000px;
      background-color: #abcdef;
      padding: 8px;
      margin: 0 auto;
    }

    p {
      line-height: 2;
    }
  </style>
</head>
<body>
  <header>
    <h1>Baga Nagaan Gara Mana Barumsa Awaash Bunee Sadarkaa 1ffaa Dhuftaan</h1>
    <nav>
      <ul>
        <li><a href="Awaash.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="news.html">News</a></li>
        <li><a href="grades.html">Grades</a></li>
        <li><a href="register.html">Register</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <div class="container">
    <h2>Baga nagaan gara website mana barumsa Awaash Bunee sadarkaa 1ffaa dhuftaan</h2>
    <h2>Fayyadamummaa barnootaa sadarkaa tokkooffaa</h2>
    <p>Barnootni bu'uura jireenyati. Barattoonni sadarkaa jalqabaa keessatti hubannoo isaanii ijaaru, dandeetti dubbisuu fi barreessuu ni dagaagsu.</p>
    <img src="image/image/images (7).jpeg" width="80%" height="70%" alt="Education Image 1">
    <h2>Kaayyoon barnoota sadarkaa 1ffaa</h2>
    <p>Kaayyoon isaa ijoolleen akka ogummaa bu'uuraa baratan, akkasumas gara sadarkaa itti aanuuf of qopheessaniif gargaarsa taasisuudha.</p>
    <img src="image/image/images (10).jpeg" width="80%" height="100%" alt="Education Image 2">
    <h2>Herrega bu'uuraa</h2>
    <p>Ijoolleen herrega salphaa akka ida'uu, hir'isuu, bay'isuu fi hirmaachisu baratu. Kun seensa gaarii ta'ee sadarkaa olaanaa keessatti milkaa'uu irratti bu'uura qaba.</p>
    <img src="image/image/images (9).jpeg" width="80%" height="70%" alt="Math Basics">
  </div>
</body>
</html>

Want Me to:

Add a responsive layout?

Create the other pages (about.html, register.html, etc.)?

Send a zipped version via Telegram?


Let me know how you'd like to proceed!

