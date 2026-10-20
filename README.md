# Funny Birthday Website

A small interactive birthday page I made for my friend Nikhil Rajput. It's a single HTML file with plain CSS and JavaScript, hosted on GitHub Pages.

**Live:** https://adityaraj8118.github.io/Funny-birthday-website/

## What happens on the page

1. **Cake:** five candles on a cake. Tap each one to blow it out. A joke message counts down the candles left.
2. **Gift loading:** a progress bar "searches" for a gift and gets stuck at 99%.
3. **"Bhai, party dega?":** a Yes / No question. Every time he presses **Nahi**, the page fades out and back in with a new message (fake error codes included), a different emoji, a bigger **Haan** button and a smaller **Nahi** button. After 20 tries the **Nahi** button disappears.
4. **Party pakki:** the final screen, which shows how many times he said no before agreeing.

## Built with

- HTML, CSS and vanilla JavaScript in one file (`index.html`), no libraries or build step
- Google Fonts (Baloo 2, Yatra One)
- Emoji pictures embedded directly in the page as inline SVG (no image files)

## Running it

Open `index.html` in any browser, or visit the live link.

To make one for someone else, change the name in the `<h1>` and `<title>` and edit the `messages` list in the script.

## Credits

Emoji graphics are from [Twemoji](https://github.com/jdecked/twemoji), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
