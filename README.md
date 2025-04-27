# What is `fontutil-mac`?

It's a command line tool to inspect font files, or to convert font files into a `.mobileconfig` file.


# Requirements

- macOS
  * Spotlight must be enabled for the directory where the font files are.
- zsh


# Usage

First, copy shell scripts in `src` directory to the directory which is included in your `PATH` environment variable.


## View family name(s) of a font

```console
fontutil family-name MyFontFile.ttf
```

## View fond name of a font

```console
fontutil fond-name MyFontFile.ttf
```

## View full name of a font

```console
fontutil full-name MyFontFile.ttf
```

## View PostScript name of a font

```console
fontutil postscript-name MyFontFile.ttf
```


# License

MIT License.  
See "LICENSE.txt" for more information.
