# I heard you like webpages.

So I made a webpage inside a webpage, so you can learn about webpages while you make webpages. [1](http://cdn.memegenerator.net/instances/800x/36074126.jpg)

I'm going to try and keep everything simple and avoid the technical jargon. Let's just dive in.


## What the heck is a webpage?

Well, in it's most basic form, a webpage is just a text file. You can write something in any text editor, save it as a `.htm` or `.html` file, and open it up with a browser of your choice.

It may not look very pretty, but every browser will render it the same - which sounds like a legit webpage to me.

Go ahead and give that a shot.


## How do I make a webpage?

Now let's try to make a webpage that will actually contain valid HTML.

### Choose a text editor

Open up any text editor you like. It can be something as basic as Notepad on Windows or TextEdit on Mac. But you might want something a bit more awesome, such as [Sublime Text](http://www.sublimetext.com/).

Some other good options include [Coda](http://panic.com/coda/), [TextMate](http://macromates.com/), [Notepad++](http://notepad-plus-plus.org/), and [Adobe Dreamweaver](http://www.adobe.com/ca/products/dreamweaver.html).

### Prepare the page

Every HTML file contains at minimum these base components:

```html
<!doctype html>
<html>
	<head>
		<meta charset="utf-8">
	</head>
	<body>
		...
	</body>
</html>
```

Here's what each of these components mean:

#### `<!doctype html>`

A statement to let the browser know what type of document this is.

There have been many (long) variations of HTML declarations. But with HTML5, it has been standardized with this short and succinct statement.

#### `<html>…</html>`

This is the root HTML document `element`.

### Copy the content

Highlight the text below and copy it into the text editor.

```
Uuummmm, this is a tasty burger!
You see? It's curious. Ted did figure it out - time travel. And when we get back, we gonna tell everyone. How it's possible, how it's done, what the dangers are. But then why fifty years in the future when the spacecraft encounters a black hole does the computer call it an 'unknown entry event'? Why don't they know? If they don't know, that means we never told anyone. And if we never told anyone it means we never made it back. Hence we die down here. Just as a matter of deductive logic.
```

> Placeholder text courtesy of [slipsum.com](http://slipsum.com/lite/)


----

###### … more to come