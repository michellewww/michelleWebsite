<div style="text-align: center; margin-top: 50px;">
    <button onclick="redirectToRandomLink()" style="background-color: #FF69B4; color: white; padding: 15px 25px; border: none; text-transform: uppercase; font-weight: bold; cursor: pointer; outline: none; font-size: 24px; border-radius: 5px; box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);">TAKE ME TO A WEBSITE MICHELLE LOVES PLEASE</button>
</div>

<script>
function redirectToRandomLink() {
    var urls = [
        'https://humanbenchmark.com/',
        'https://tv.hzfe.org/',
        'https://hammyhome.com/',
        'https://bubblespop.netlify.app/',
        'https://pixel-me.tokyo/en/',
        'https://aidn.jp/mikutap/',
        'https://www.nasa.gov/image-of-the-day/',
        'https://www.avogado6.com/',
        'https://www.drawaurora.com/'
    ];
    var randomIndex = Math.floor(Math.random() * urls.length);
    window.open(urls[randomIndex], '_blank').focus();
}
</script>
