# Internet Bird embed snippet

A migratory bird that flies over the world of the internet, from one web page to another. This is the snippet that lets you add your page to her route.

Part of the [Internet Bird](https://joub.in/bird/lands) project by [Joubin Zargarbashi](https://joubinzargarbashi.com).

## How to use

1. Email joubinz@gmail.com to register your page as one of the bird's known lands. You'll be given a `webLandId` code.
2. Open `index.html` here, copy everything between `<!-- start of bird snippet -->` and `<!-- end of bird snippet -->`, and paste it into your own page.
3. Replace `YOUR_LAND_ID` with the code you were given.

## Adding it to WordPress

- **One page/post only**: edit the page, add a **Custom HTML** block (Gutenberg editor), and paste the snippet into it. No plugin needed.
- **A few specific pages**: use an HTML-snippet plugin (e.g. **Insert HTML Snippet**, or WPCode's snippet feature). Define the snippet once in the plugin, then drop the shortcode it gives you (e.g. `[html_snippet id="123"]`) onto whichever pages you want.
- **Every page (site-wide)**: install a plugin like **Insert Headers and Footers** (WPCode), then paste the snippet into its "footer" script box so it loads on every page automatically.

Whichever option, remember to replace `YOUR_LAND_ID` with your actual code first.
