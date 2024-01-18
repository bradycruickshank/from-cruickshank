# Brady Cruickshank

My favorite song is The Sound of Silence by Simon and Garfunkel. It's a classic folk rock song from the 1960s. The original version of the song was just acoustic guitar and vocals. The song didn't become popular until a radio dj created a new version of the song which added electric guitar, drums, and bass to the original recording.

![<MyMedia.md>](me.jpg)

***

# Great Songs
This table contains a few songs that I believe everyone should listen to. It may be because they're important to the history of music, or just because I think they're really good.

|Name|Reason for Reccomendation|Artist|
|---|---|---|
|While My Guitar Gently Weeps|It's one of the best songs by one of the most influential rock bands of all time|The Beatles|
|I Don't Mind|This song is very catchy and has some fantastic lyrics|Sturgill Simpson|
|It's Not Up To You|While this song is somewhat strange, the production is great and the vocal performance is very powerful|Bjork|
|Like A Rolling Stone|This is another 60s rock classic. It's something everyone should listen to at least once.|Bob Dylan|

***

# Favorite Quotes

> Be the change that you want to see in the world. -*Mahatma Gandhi*

> In the middle of every difficulty lies opportunity. -*Albert Einstein*

***

# Code Snippet

This code snipped delays running the provided function until a certain amount of time has passed.

```
const debounce = (fn: Function, ms = 300) => {
	let timeoutId: ReturnType;
  return function (this: any, ...args: any[]) {
	  clearTimeout(timeoutId);
    timeoutId = setTimeout(() => fn.apply(this, args), ms);
  };
};
```

<https://code.pieces.app/collections/typescript>

