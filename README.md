# flexbox-mixin
A bunch of SASS flexbox mixins from MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Mixins

# Usage

In any CSS file:

```css
@import 'flexbox-mixin';

.some-selector {
  @include flexbox;                                                             
  @include justify-content(flex-start);                                         
  @include align-items(center);                                                 
  @include flex-direction(column);                                              
  @include flex-wrap(nowrap);                                                   
  @include align-content(flex-start);
}
```
