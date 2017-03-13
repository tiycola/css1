1. The example provided is not "semantically correct," so to speak. Yes, the text, "Will I be seen?" will display, albeit not in the proper way. Without the correct tags enclosing it, different browsers will have various ways of interpreting it. Screen readers, too, will have trouble conveying the message properly to the user.

2.

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>VAPORWAVE</title>
  </head>
    <body>
  <header>
    <h1>VAPORWAVE RULES EVERYTHING AROUND ME</h1>
    <img src="/floral_shoppe.jpg" class="floral_shoppe" alt="Macintosh Plus' Monumental Album, Floral Shoppe">
  </header>
    <article class="main_article">
      <p> <b>Vaporwave</b> (British English: vapourwave) is an electronic music subgenre and art movement that originated in the early 2010s and spread over the next half of the decade among various Internet communities. It is characterized by a nostalgic or surrealist fascination with entertainment, technology and advertising of the 1980s and 1990s, and styles of both corporate and popular music such as lounge music, smooth jazz and elevator music. Vaporwave music is interpreted as a critique or reflection on consumer capitalism and popular culture. Its name alludes to vaporware, a term for products, typically computer software or hardware, which are announced but never released.</p>

      <img src="http://placekitten.com/300/400" class="cat" alt="cat">

      <p>The visual style of vaporwave (as seen on album covers and music videos) is commonly referred to as aesthetics (often stylized as <b>"ＡＥＳＴＨＥＴＩＣＳ"</b>, with fullwidth characters). The style often involves classical sculpture, web design, surrealism, low-poly computer renderings, glitch art, VHS recordings, cassette tapes, Japanese art and cyberpunk tropes.</p>
    </article>

  <footer>
    <form>
      <fieldset>
        <legend>Crucial Info:</legend>
        <label for="name">Name:</label>
        <input type="text"><br>
        <label for="name">Email:</label>
        <input type="text"><br>
        How are you doing today?<br>
        <select>
          <option value=ok>Ok</option>
          <option value="could_be_better">Could be better</option>
          <option value="not_bad">Not bad</option>
          <option value="incredible">incredible</option>
        </select>
      </fieldset>
    </form>
  </footer>
</html>


3.

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>The Decemberists</title>
  </head>
    <body>
        <div class="article">
          <div class="article_title">
        <h1>The Decemberists: The King Is Dead</h1>
      </div>

      <div class="article_text">
        <article>When a 12-and-a-half-minute murder ballad ("The Island," from 2006's The Crane Wife) stands as one of your more concise career high points, it's probably time to consider reining things in. That's just what the Decemberists — the Portland, Oregon, band known for its complex story-songs about fairy queens and shape-shifting lovers — have done on The King Is Dead.</article> <br>
      <a href="#" class="link">More</a>
      </div>
    </div>
  </body>
</html>
