Favorite every tweet you can see. 

Open Twitter, paste the javascript below into the console, press enter, and your browser will automatically scroll down and like every tweet.

```
setInterval(function(){
    window.scrollTo(0,document.body.scrollHeight);
    $('.ProfileTweet-actionButton.js-actionButton.js-actionFavorite:visible').click();
}, 1000);
```

Be careful because it's pretty hard to undo.
