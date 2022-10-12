# ERRATA

## color-palette: Ciklusok egymásba ágyazása, világosabb színek generálása
Az új SCSS verzió miatt a `generate-lighter-colored-backgrounds` mixinben a `$lightness: $percent` helyett az alábit kell írni:
`$lightness: $percent * 1%`

## color-palette: Ciklusok egymásba ágyazása, sötétebb színek generálása
Az új SCSS verzió miatt a `generate-darker-colored-backgrounds` mixinben a `$lightness: $percent` helyett az alábit kell írni:
`$lightness: $percent * -1%`