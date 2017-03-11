## Blinking pointer for capturing user's attention

## Motivation & caveat

I wish to use blinking pointer on all my existing projects to on-board my users.

The caveat is that there should only have one blinking pointer on one page. Too many of them distract the users.

## Installation
```
  <link rel="stylesheet" href="blinking-pointer.css">
```

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

## DEMO

[http://ytbryan.com/examples/blinking-pointer](http://ytbryan.com/examples/blinking-pointer)
