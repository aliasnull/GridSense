![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Blogger](https://img.shields.io/badge/blogger-%23FF5722.svg?style=for-the-badge&logo=blogger&logoColor=white)
<br>
[![License](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg?style=for-the-badge&logo=creative-commons&logoColor=white)](LICENSE)
![Repo Size](https://img.shields.io/github/repo-size/AliasNull/GridSense?style=for-the-badge&logo=github&logoColor=white)


# GridSense Blogger Theme

A modern, responsive, and AdSense-friendly Blogger theme with a grid layout, dark mode, and advanced content features.

## Installation

1.  **Backup:** Always backup your current theme before making changes.
2.  **Upload:** Go to Blogger > Theme > Customize > Edit HTML. Copy the entire content of `gridsense.xml` and paste it into the editor. Save.
3.  **Setup Menus:**
    *   Go to **Layout**.
    *   Edit the **Main Menu** widget to add your primary navigation links.
    *   Edit the **Secondary Menu (Topics)** widget to add scrolling topic links (e.g., Trending, Quotes).

## Main Features

*   **Responsive Grid Layout:** Automatically switches between 2-column grid (Desktop) and single column (Mobile).
*   **Dark Mode:** Toggle switch in the header with preference saved automatically.
*   **AdSense Ready:** Dedicated widgets in the Layout editor for:
    *   Below Title
    *   Below Content
    *   In-Article (After 2nd, 4th, 6th paragraphs)
    *   Homepage Ads (Above all posts and after every 4 post)
    *   *Note: Ads are smart enough not to break blockquotes or lyrics.*
*   **Social Sharing:** Built-in buttons for Facebook, Twitter, WhatsApp, and Copy Link at the bottom of every post.
*   **Social Follow:** Built-in buttons for social follows where your fans can follow you.
*   **Related Posts:** Automatically suggests up to 3 relevant articles based on post tags/labels.
*   **Join Community:** A Option to ask your visitors join your community like telegram or x (or wherever you want).
*   **Donation Box:** Built-in donation option where your fans can support you by donating.

## Typography & Content Elements

Use these HTML structures in your posts to take advantage of the theme's built-in styling and features.

### Quotes
Standard blockquotes are styled automatically and include "Copy" and "Share" buttons.

```html
<blockquote>
  "The only way to do great work is to love what you do."
</blockquote>
```

### Lyrics & Poetry
For song lyrics or poems where line breaks matter, use the `lyrics-box` class. This centers the text and preserves formatting. Includes "Copy" and "Share" buttons.

```html
<div class="lyrics-box">
  First line of the song
  Second line of the song

  Chorus line here
</div>
```

### Responsive Tables
Standard HTML tables are automatically optimized for mobile. They will scroll horizontally if they are too wide, ensuring they never break your layout.

```html
<table>
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
    </tr>
  </tbody>
</table>
```

## Custom Post Formats

You can use these special CSS classes in your post editor (HTML view) to create rich content:

### Image Gallery
Create a grid of images by wrapping them in a div with class `gallery-grid`.

```html
<div class="gallery-grid">
  <img src="image1.jpg" />
  <img src="image2.jpg" />
  <img src="image3.jpg" />
</div>
```

### Responsive Video
Wrap your YouTube or other video iframes in a `video-container` div to make them responsive (16:9 aspect ratio).

```html
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/..." ...></iframe>
</div>
```

## Credits

*   **Author:** AliasNull
*   **License:** Creative Commons Attribution 4.0 International

---

## ⭐️ Support the Project

If you find this theme useful or you use it in your projects, please give it a **Star** ⭐️ on GitHub! It helps me keep the project alive.

### ☕ Buy me a Coffee

If you really like my work, you can support me via donation.

| Platform | Address / Link |
| :--- | :--- |
| [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/aliasnull) | https://paypal.me/aliasnull |
| ![Bitcoin](https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white) | `bc1qnn7r30vvhmm29nl27w0uv549gvcglx3vllexzf` |
| ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white) | `0xFc46b12Ac015180D4494051bFa7b6327E287F814` |
| ![Tether](https://img.shields.io/badge/tether-26A17B?style=for-the-badge&logo=tether&logoColor=white) | `TQrAVrRsss8hU3ygeq4E1wmStNdAAuHH8t` |
| ![UPI](https://img.shields.io/badge/UPI-702B90?style=for-the-badge&logo=bhim&logoColor=white) | `aliasnull@ptaxis` |

_Every contribution, however small, is hugely appreciated._ ❤️
