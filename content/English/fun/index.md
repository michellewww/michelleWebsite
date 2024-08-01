<div style="text-align: center; margin-top: 50px;">
    <button onclick="redirectToNextLink()" style="background-color: #FF69B4; color: white; padding: 15px 25px; border: none; text-transform: uppercase; font-weight: bold; cursor: pointer; outline: none; font-size: 24px; border-radius: 5px; box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);">TAKE ME TO A WEBSITE MICHELLE LOVES PLEASE</button>
</div>

<script>
    var urls = [
        'https://pixel-me.tokyo/en/',
        'https://www.drawaurora.com/',
        'https://humanbenchmark.com/',
        'https://tv.hzfe.org/',
        'https://hammyhome.com/',
        'https://bubblespop.netlify.app/',
        'https://aidn.jp/mikutap/',
        'https://www.nasa.gov/image-of-the-day/',
        'https://www.avogado6.com/'
    ];

    // Index to keep track of the current URL
    var currentIndex = 0;

    function redirectToNextLink() {
        if (currentIndex >= urls.length) {
            currentIndex = 0; // Reset to the beginning if we've gone through all URLs
        }
        window.open(urls[currentIndex], '_blank').focus();
        currentIndex++;
    }
</script>