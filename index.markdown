---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<style>
  .kontakt-block { display: grid; grid-template-columns: auto 1fr; column-gap: 1.5em; }
  .kontakt-logo { position: relative; }
  .kontakt-logo img { position: absolute; top: 0; right: 0; height: 100%; max-width: 100%; object-fit: contain; object-position: right top; }

  /* Handy: Logo unter den Kontaktblock */
  @media (max-width: 600px) {
    .kontakt-block { grid-template-columns: 1fr; row-gap: 1.5em; }
    .kontakt-logo img { position: static; height: auto; width: 100%; max-width: 300px; }
  }
</style>

<h1><strong>Hier entsteht etwas schönes</strong></h1>

<br><br><br><br><br>

<div class="kontakt-block">
  <div>
    Sebastian Birth<br>
    <br>
    <a href="mailto:sebastian@fs-birth.de?subject=Anfrage%20per%20Website: ">sebastian@fs-birth.de</a><br>
    <br>
    <a href="tel:+494030980506">+49 40 30980506</a><br>
    <br>
    <a href="https://www.instagram.com/fs_birth/"><img src="https://fs-birth.de/bilder/Instagram_Glyph_Gradient.png" alt="Instagram" height="60" width="60" style="display: block;"></a>
  </div>
  <div class="kontakt-logo">
    <img src="/bilder/fsb-icon_oo.png" alt="FS-Birth Logo">
  </div>
</div>
