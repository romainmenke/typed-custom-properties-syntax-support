# Typed custom properties do not have matching support in JS and CSS

The `syntax` descriptor from JS supports more types than CSS.

see : https://www.romainmenke.com/typed-custom-properties-syntax-support/

This example uses the `<url>` syntax value to created typed custom properties that should resolve urls to the stylesheet where they are registered.

Since this is only supported in JS and not CSS, the url is not consistently resolved between the two.

### Chromium bug report

https://bugs.chromium.org/p/chromium/issues/detail?id=1478472
