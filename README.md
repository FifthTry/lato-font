# Lato : fastn Font Package

This repository contains a [fastn font package](https://fastn.dev/featured/fonts/) containing [Google Font: 
Lato](https://fonts.google.com/specimen/Lato/about).

Lato is a sans serif typeface family started in the summer of 2010 by 
Warsaw-based designer Łukasz Dziedzic (“Lato” means “Summer” in Polish). In 
December 2010 the Lato family was published under the Open Font License by his 
foundry tyPoland, with support from Google.

Designers: Łukasz Dziedzic, Principal design

## How To Use This Font In Your fastn Package:

[Read the docs and demo](https://fifthtry.github.io/lato-font).

TLRD:

Include fifthtry.github.io/lato-font package into `fastn.ftd` file:

```ftd
;-- fastn.dependency: fifthtry.github.io/lato-font
```

Inside your `fastn/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/lato-font/assets as lato

;-- fastn.type.headline-small: $lato.fonts.Lato
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fastn.type.headline-small
```

You will see the `lato` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fastn.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Lato Font is under [Open Font Licence](https://fonts.google.com/specimen/Lato/about), this fastn wrapper is also
under [Open Font Licence](LICENSE).





