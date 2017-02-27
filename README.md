[![bower version](https://img.shields.io/bower/v/k-avatar.svg)](https://libraries.io/bower/k-avatar) 
[![open issues](https://img.shields.io/github/issues/k4ng%2Fk-avatar.svg)](https://github.com/k4ng/k-avatar/issues) 
[![npm](https://img.shields.io/npm/v/k-avatar.svg)](https://www.npmjs.com/package/k-avatar)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://github.com/k4ng/k-avatar) 


# \<k-avatar\>

Simple component to make Gmail like text avatars for profile pictures. These avatars can be scaled up to any size. [view demo](https://k4ng.github.io/k-avatar/)

<!--
```
<custom-element-demo height="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="k-avatar.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<k-avatar 
    data-name           = "Kang cahya"
    data-height         = "100"
    data-width          = "100"
    data-char-alias     = "2"
    data-text-color     = "#FFFFFF"
    data-border-radius  = "10"
    data-font-size      = "40"
    data-font-weight    = "500"></k-avatar> 
    <p><strong>Kang cahya</strong></p>
```


## How to install

### bower

```markdown
bower install --save k-avatar
```

### npm

```markdown
npm install k-avatar
```


## Properties

Data Attribute | Description | Default Value
-------------- | ----------- | -------------
data-name | Name of the user which the profile picture should be generated. | K4ng
data-height | Height of the picture. | 48 (pixel)
data-width | Width of the picture. | 48 (pixel)
data-char-alias | Number of characherts to be shown in the picture. | 1
data-text-color | Color of the text. | #FFFFFF (white)
data-font-size | Font size of the character(s). | 20 (pixel)
data-font-weight | Font weight of the character(s). | 400 
data-border-radius | Set border-radius container. | 0 (%)
data-box-shadow | set box-shadow container. | 0px 0px 0px 0px rgba(33,33,33,0.75)
data-text-shadow | set text-shadow character. | 0px 0px 0px rgba(33,33,33,0.75)

## Contributing

1. Fork it!
1. Create your feature branch: git checkout -b my-new-feature
1. Commit your changes: git commit -m 'Add some feature'
1. Push to the branch: git push origin my-new-feature
1. Submit a pull request :D

## License

[MIT License](https://github.com/dyazincahya/k-avatar/blob/master/LICENSE) 
