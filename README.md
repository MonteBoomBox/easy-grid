# easy-grid
## Create complex grid layouts with a simple CSS syntax.

### Start using with CDN (recommended)
```
https://cdn.jsdelivr.net/gh/MonteBoomBox/easy-grid/easy-grid.css
```
---

#### Create a grid container with the `.grid` class
```
<div class="grid"></div>
```

#### Specify a column amount between 1 to 12 using the `.col-{number}` class
```
<div class="grid col-4"></div>
```

#### Span a grid item across a column using the `.col-span-{number}` class
```
<div class="grid col-4">
  <div class="grid-item col-span-2">
</div>
```

#### Span a grid item across a row using the `.row-span-{number}` class
```
<div class="grid col-4">
  <div class="grid-item row-span-2">
</div>
```

#### Apply gaps to the grid using the `.gap-{number}` class
```
<div class="grid gap-4"></div>
```
