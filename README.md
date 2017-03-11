## Blinking pointer for capturing user's attention

Features: 
- capture user's attention with a blink! 
- efficient. only CSS. no jquery, no javascript
- ships with multiple colours (white, black, red, yellow, purple, green, orange, pink)


## Installation
```
  <link rel="stylesheet" href="https://raw.githubusercontent.com/ytbryan/blinking-pointer/master/blinking-pointer.css">
```
You should probably host this css yourself. 

## Usage

```
<div class="">
  <a href="#">Putting this beside a hyperlink makes sense too.</a>
  <span class="circle-pointer">
    <span class="inner-circle-pointer red-circle"></span>
  </span>
</div>

<button type="button" name="button">This is a button
  <span class="circle-pointer">
  	<span class="inner-circle-pointer red-circle"></span>
  </span>
</button>

```

## Motivation & caveat

I wish to use blinking pointer on all my existing projects to on-board my users.

> The caveat is there should only be one blinking pointer on a single page. Too many blinking pointers back-fire and distract the users.

## DEMO

[http://ytbryan.com/examples/blinking-pointer](http://ytbryan.com/examples/blinking-pointer)

## Contact

ytbryan@gmail.com 

> If you use this in your project or find this useful, let me know through email on how you use it. 

## License

MIT 
