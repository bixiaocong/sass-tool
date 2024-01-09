
# ciba-sass quick menu file



### base.scss

> 基本样式

- @mixin height($height: null, $line-height: $height)

- @mixin inline-block($vertical-align: null)

- @mixin text-overflow($line: 1)



### center.scss

> 常用居中

- @mixin center-absolute($width: null, $height: $width, $top: 50%, $left: 50%)

- @mixin center-fixed($width: null, $height: $width, $top: 50%, $left: 50%)

- @mixin center-margin($margin-top: 0, $margin-bottom: $margin-top)

- @mixin center-box()

- @mixin center-flex()



### config.scss

> 配置文件

- $global-width: 1080 !default;

- $global-unit: 'rem' !default;

- $global-rem-size: 10 !default;

- $global-px-size: 320 !default;



### main.scss

> 对外主文件

- @function use($num)

- @function normal($num)

- @function rem($num, $width: $global-width)

- @function px($num, $width: $global-width)

- @function percent($num, $width: $global-width)



### position.scss

> 常用定位

- @mixin pos($top: null, $left: null, $right: null, $bottom: null, $width: null, $height: null)

- @mixin absolute($top: null, $left: null, $right: null, $bottom: null, $width: null, $height: null)

- @mixin relative($top: null, $left: null, $right: null, $bottom: null, $width: null, $height: null)

- @mixin fixed($top: null, $left: null, $right: null, $bottom: null, $width: null, $height: null)

- @mixin atl($top: 0, $left: 0)

- @mixin atr($top: 0, $right: 0)

- @mixin abl($bottom: 0, $left: 0)

- @mixin abr($bottom: 0, $right: 0)

- @mixin fbr($bottom: 0, $right: 0)

- @mixin ftl($top: 0, $left: 0)

- @mixin ftr($top: 0, $right: 0)

- @mixin fbl($bottom: 0, $left: 0)

- @mixin fbr($bottom: 0, $right: 0)

- @mixin wh($width: null, $height: null)

- @mixin square($width: 100%, $height: $width)

- @mixin full()

- @mixin afull()

- @mixin ffull()



### reset.scss

> 内外边距通常让各个浏览器样式的表现位置不同



> 没有 @mixin 或 @function




### transform.scss

> 常用变形

- @mixin scale($x: 1)

- @mixin scaleX($x: 1)

- @mixin scaleY($x: 1)

- @mixin scale3d($x: 1, $y: 1, $z: 1)

- @mixin rotate($x: 0, $unit: 1deg)

- @mixin rotateX($x: 0, $unit: 1deg)

- @mixin rotateY($x: 0, $unit: 1deg)

- @mixin rotate3d($x, $y, $z, $deg)

- @mixin skew($x: 0)

- @mixin skewX($x: 0)

- @mixin skewY($x: 0)

- @mixin translate3d($x: 0, $y: 0, $z: 0)

- @mixin translateX($x: 0)

- @mixin translateY($y:0)

- @mixin x($x: 0)

- @mixin y($y: 0)

- @mixin t3d($x: 0, $y: 0, $z: 0)

