[![bower version](https://img.shields.io/bower/v/k-avatar.svg)](https://libraries.io/bower/k-avatar) 
[![open issues](https://img.shields.io/github/issues/k4ng%2Fk-avatar.svg)](https://github.com/k4ng/k-avatar/issues) 
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/dyazincahya/k-avatar/blob/master/LICENSE) 
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://github.com/dyazincahya/k-avatar) 

# \<k-avatar\>

Simple Element to make Gmail like text avatars for profile pictures. These avatars can be scaled up to any size.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="k-avatar.html">
    <k-avatar data-name="Dy"></k-avatar> <span>Dy</span>
  </template>
</custom-element-demo>
```
-->

## How to install
```markdown
bower install --save k-avatar
```

## Usage

#### Simple
```html
<k-avatar data-name="Dy"></k-avatar> <span>Dy</span>
```

#### Advance

```html
<k-avatar 
    data-name           = "Kang cahya"
    data-height         = "100"
    data-width          = "100"
    data-char-alias     = "2"
    data-text-color     = "#FFFFFF"
    data-font-size      = "40"
    data-font-weight    = "500"></k-avatar> <span>Kang cahya</span>
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
data-border-radius | Set border-radius container character. | 0 (%)

## Contributing
- Fork it!
- Create your feature branch: git checkout -b my-new-feature
- Commit your changes: git commit -m 'Add some feature'
- Push to the branch: git push origin my-new-feature
- Submit a pull request :D