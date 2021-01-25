# The Equal Feature

A OpenType script that displays Hebrew multi-gender words as *male* or *female*. Developed by Avraham Cornfeld at [AlefAlefAlef](https://alefalefalef.co.il).

The feature works on 'divided words' such as: דרושים/ות, א.נשים, שלכםן etc.

## Embedding Instruction

CSS:
```CSS
.female { font-feature-settings: "ss11"; }
.male { font-feature-settings: "ss12"; }
```

Javascript:
```JavaScript
document.getElementById("MyElement").className = "female";
```


Read more at:

[About Equal Fonts (in Hebrew)](https://alefalefalef.co.il/about-equal-fonts/)

[The Ivrita Project](https://github.com/AlefAlefAlef/ivrita)

## Contributing

Pull requests are welcome.

## Open Source

This script is distributed under [*CC-NC-ND*](https://creativecommons.org/licenses/by-nc-nd/3.0/). Let us know if you have any uses you want to get an exclusion for.
