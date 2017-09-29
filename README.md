Favorite every tweet you can see. Paste the javascript below into the console and your browser will automatically scroll down and like every tweet. Works on profiles, someone's timeline, or anywhere tweets are visible.

```
setInterval(function(){
    window.scrollTo(0,document.body.scrollHeight);
    $('.ProfileTweet-actionButton.js-actionButton.js-actionFavorite:visible').click();
}, 1000);
```

Be careful because it's pretty hard to undo.
