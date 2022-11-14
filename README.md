# Lato : FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Lato](https://fonts.google.com/specimen/Lato/about).

Lato is a sans serif typeface family started in the summer of 2010 by 
Warsaw-based designer Łukasz Dziedzic (“Lato” means “Summer” in Polish). In 
December 2010 the Lato family was published under the Open Font License by his 
foundry tyPoland, with support from Google.

Designers: Łukasz Dziedzic, Principal design

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/lato-font).

TLRD:

Include fifthtry.github.io/lato-font package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/lato-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/lato-font/assets as lato

;-- fpm.type.headline-small: $lato.fonts.Lato
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `lato` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Lato Font is under [Open Font Licence](https://fonts.google.com/specimen/Lato/about), this FPM wrapper is also
under [Open Font Licence](LICENSE).





