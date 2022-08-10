# Lato Font

`fifthtry.github.io/lato` is a wrapper over [Lato font](https://github.com/latofonts/lato-source).

# How To Use This Font

include fifthtry.github.io/lato package into FPM.ftd file

```ftd
-- fpm.dependency: fifthtry.github.io/lato

-- fpm.auto-import: fifthtry.github.io/lato as lato
```

Inside your .ftd file to change for any specific token use:

```
-- fpm.type.headline-small.font: $lato.fonts.lato

-- ftd.text:
role: $fpm.type.headline-small
```

[How to Use fonts](https://fpm.dev/how-to/how-to-use-fonts/).

# License

[Lato is distributed under SIL Open Font License 1.1](https://github.com/latofonts/lato-source/blob/master/LICENSE.txt). We use the same license to be compatible with them.
