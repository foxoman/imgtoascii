# Img to Ascii
A command line tool for converting images to ASCII!

## Compiling / Building

* Install using nimble:
```bash
 nimble install https://github.com/foxoman/imgtoascii.git 
```

## Usage
```bash
imgtoascii <source> <scale> [width stretch] [palette]
```
### Arguments:
*Required arguments are surrounded in <>, optional arguments are surrounded in [].*
- `source` - *The source, a path to a file.*
- `scale` - *Used to scale down the image to fit in your console, recommended value is 0.1.*
- `width stretch` - *Used to account for console characters being taller than they are wide, default value is 2.0.*
- `palette` - *The palette used, one of BLOCK, HIGH, LOW, BRAILE, or a custom palette as a string.*
