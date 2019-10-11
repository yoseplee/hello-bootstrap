# hello-bootstrap
> Learning bootstrap for fast-prototyping.

# 12 grid system
![grid system](https://dzone.com/storage/temp/891159-dzone4.jpg)

Regard web page as a grid. Just set grid you want and pour contents! Consider that all the grid classification such as 1, 4, 8, 6, 12 is subset of grid-1. For example, the width of col-md-4 is the same as the width of 4 col-md-1s.
# Usage

Mark down your contents under div class container>row>your-cols.

It's really easy!

```html
<div class="container">
    <div class="row">
        <div class="col-md-4">YOUR CONTENTS</div>
        <div class="col-md-4">YOUR CONTENTS</div>
        <div class="col-md-4">YOUR CONTENTS</div>
    </div>
</div>
```

# CDN
insert into head
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
```