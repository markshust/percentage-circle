# Percentage Circle

This css file is a variation of <a href="https://github.com/toubou91/percircle" target="_blank">https://github.com/toubou91/percircle</a>.

I needed a very simple file with little fluff and pre-defined configuration. This CSS file varies from `percircle` in the fact that animations and vendor-prefixes have been removed. It also assumes no pre-defined width, height or color, so it is up to you to define those parameters.

<a href="http://jsfiddle.net/vqhdvh3d/" target="_blank">Here is a JSFiddle example of circle with a 100px diameter, blue in color, with black progress bar.</a>

```
<div class="c100 p30">
    <div class="slice">
        <div class="bar"></div>
        <div class="fill"></div>
    </div>
</div>

<style>
.c100 {
  font-size: 100px;
}
.c100:after {
  background: blue;
}
.c100 .bar,
.c100 .fill {
  border-color: black;
}
</style>
```

