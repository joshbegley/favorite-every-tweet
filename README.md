**Favorite every tweet.** Paste the javascript below into the console and your browser will automatically scroll down and like every tweet you can see. 

Works on profiles, someone's timeline, or anywhere tweets are visible.

```
setInterval(function(){
    window.scrollTo(0,document.body.scrollHeight);
    $('.ProfileTweet-actionButton.js-actionButton.js-actionFavorite:visible').click();
}, 1000);
```

Be careful because it's pretty hard to undo. 

![like.gif](/like.gif)

To **unlike** all the tweets you just liked, use the following:

```
setInterval(function(){
  window.scrollTo(0,document.body.scrollHeight);
  $('.ProfileTweet-actionButtonUndo.js-actionButton.js-actionFavorite:visible').click();
}, 1000)
```
