# rear-vue-mirror

Component library version of [rear-vue-inline](https://github.com/Inventsable/rear-vue-inline), example toolbar controls:

## with [CEP Magic Mirror](https://github.com/Inventsable/CEP-Magic-Mirror)

![menu](https://thumbs.gfycat.com/HonorableTotalAcornwoodpecker-size_restricted.gif)

Class names handle everything in JS and CSS but clutter the HTML:

``` html
<div class="adobe-toolbar">
  <div class="adobe adobe-btn-switch-on">
    <span class="adobe-icon-stroke"></span>
  </div>
  <div class="adobe adobe-btn-switch-off">
    <span class="adobe-icon-fill"></span>
  </div>
  <div class="adobe adobe-btn">
    <span class="adobe-icon-file"></span>
  </div>
  <div class="adobe adobe-btn">
    <span class="adobe-icon-folder"></span>
  </div>
  <div class="adobe-toolbar-divider"></div>
</div>
```

## with [rear-vue-inline](https://github.com/Inventsable/rear-vue-inline)

![demo](https://thumbs.gfycat.com/CarefreeFemaleElkhound-size_restricted.gif)

``` html
<!-- within vue instance -->
  <adobe-toolbar>
    <adobe-btn icon="stroke" switch="true"></adobe-btn>
    <adobe-btn icon="fill" switch="false"></adobe-btn>
    <adobe-btn icon="file"></adobe-btn>
    <adobe-btn icon="folder"></adobe-btn>
    <adobe-checkbox state="on">Text here</adobe-checkbox>
    <adobe-checkbox state="off">Is unchecked</adobe-checkbox>
    <adobe-toolbar-divider />
  </adobe-toolbar>
```
