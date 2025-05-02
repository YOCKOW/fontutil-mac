# What is `fontutil-mac`?

It's a command line tool to inspect font files, or to convert font files into a `.mobileconfig` file.


# Requirements

- macOS
  * Spotlight must be enabled for the directory where the font files are.
- zsh


# Usage

First, copy shell scripts in `src` directory to the directory which is included in your `PATH` environment variable.

## View author(s) of a font

```console
fontutil authors MyFontFile.ttf
```

## View copyright of a font

```console
fontutil copyright MyFontFile.ttf
```

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

## View publisher(s) of a font

```console
fontutil publishers MyFontFile.ttf
```

## View style name of a font

```console
fontutil style-name MyFontFile.ttf
```

## View version of a font

```console
fontutil version MyFontFile.ttf
```

## Export font files to a 'mobileconfig' file.

```console
fontutil mobileconfig --name "My Font Collection" --output MyFontCollection.mobileconfig MyFontFile1.ttf MyFontFile2.ttf
```


# License

MIT License.  
See "LICENSE.txt" for more information.
