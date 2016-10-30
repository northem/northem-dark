<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-logo-banner.svg"/></p>

<p align="center"><img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/northem-dark/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/northem-dark.svg"/></a> <img src="https://www.npmjs.com/static/images/touch-icons/favicon-32x32.png" width=24 height=24/> <a href="https://www.npmjs.com/package/northem-dark"><img src="https://img.shields.io/npm/v/northem-dark.svg"/></a> <a href="https://www.npmjs.com/package/northem-dark"><img src="https://img.shields.io/npm/dt/northem-dark.svg"/></a> <a href="https://www.npmjs.com/package/northem-dark"><img src="https://img.shields.io/npm/dm/northem-dark.svg"/></a></p>

---

# 2.0.0 (2016-10-30)
**The milestone [Version 2.0.0](https://github.com/arcticicestudio/northem-dark/milestone/2) release!**

The whole project, including both sub-palettes and related sub-projects/ports have been rewritten and cleaned up to adapt to the new project setup like the [Nord](https://github.com/arcticicestudio/nord) project.

## Features
### Naming Scheme
**Color names**
The current naming scheme, where each color got an individual name based on the value, has been replaced with an numbered format.  
Example: `darkest-coal` has been renamed to `northem-dark0`, `dark-coal` to `northem-dark1`.  
This goes on with a continuous numerating where the current position of a color represents its number.

![Northem Dark Palette Overview](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-overview.svg)

**Components**
Next to this, the color palette has been divided into four named components to represent the different color effects where each component contains a different amount of colors:  
  1. **Dark Water** `northem-dark0` - `northem-dark3`  
  2. **Light Wind** `northem-dark4` - `northem-dark6`  
  3. **Ice** `northem-dark7` - `northem-dark10`  
  4. **Rainbow** `northem-dark11` - `northem-dark15`

This naming convention allows an uncomplicated use for terminals and preserves the compatibility to similar projects like [base16](chriskempson.com/projects/base16).

The X11 color scheme names and RGB value variables has been removed, but X11 color names are still included in the Sass- and LESSCSS source documentations.

### New color
A new color has been added to close the gap of the missing sixteenth color.  
The value of the color is `#CBC9C9` which has been added as `northem-dark4` to the *Light Wind* component.  
This color is calculated from the components base color `northem4` (`#CACACA`) of the [Northem](https://github.com/arcticicestudio/northem) color palette via the Sass method `saturate($northem4, 1%)`.

### Source Formats
**Sass**
All [Sass](http://sass-lang.com) sources have been documented via [SassDoc](http://sassdoc.com) and a `template-css.scss` is available to be compiled to a CSS file including all color variables which is compatible to the CSS specification.  
The SassDoc is configurable via the `.sassdocrc` file.
(@arcticicestudio, #4, c7ee4325)

**LESSCSS**
All [LESSCSS](http://lesscss.org) sources have been documented via [KSS](http://warpspire.com/kss).
(@arcticicestudio, #5, 9a79569f)

**Native**
All native files have been recreated containing the new color and the new color naming scheme.
(@arcticicestudio, #6, 385fd851)
  
### Build Tools
**Gulp**
Introduced a [Gulp](gulpjs.com) file to compile Sass sources to CSS, provide a local hot-reload server for instant recompilatio on file changes and to build the new [SassDoc](http://sassdoc.com).  
(@arcticicestudio, #8, a50a0c3b)

**Travis CI and Circle CI**
Added the `.travis.yml` and `circle.yml` configuration files for continuous integration web services.
(@arcticicestudio, #7, 95ab50b4)

### NPM
A `package.json` file has been added to provide project meta data and dependencies for a release as a [NPM](http://npmjs.com) package.
(@arcticicestudio, #9, dd0a335b)

### Assets
All project branding assets have been removed and replaced with new, modern SVG and AI files.
(@arcticicestudio, #3, 5392d894)

### Documentations
All project documentations have been rewritten.  
The project license for the code has been changed to the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0) license.
(@arcticicestudio, #3, 5392d894)

### Git
The `.gitignore` and `.gitattributes` files have been rewritten to remove the high amount of unused pattern and comments.
(@arcticicestudio, #3, 5392d894)

# 1.0.0 (2016-04-16)
![Northem Logo](src/main/assets/media/northem-logo.png)

**Syntax Preview**  
![Northem Dark Syntax Preview](src/main/assets/media/northem-dark-syntax-preview.png)

## Features
### Native
  - Added the "[GIMP](https://www.gimp.org)/[Inkscape](https://inkscape.org) Palette" file format (`.gpl`)
  - Added the "[Adobe Swatch Exchange](https://helpx.adobe.com/illustrator/using/using-creating-swatches.html)" file format (`.ase`)
  - Added the "Alias/WaveFront Material" file format (`.mtl`)
  - Added the "[Gpick](http://www.gpick.org) Palette" file format (`.gpa`)
  - Added the binary exported [GIMP](https://www.gimp.org) XCF project image `northem-dark.png` and `northem-dark-large.png`
  ![Northem Large](src/main/native/northem-dark-large.png)

### Non-Native
  - Implemented the [Sass](http://sass-lang.com) file format (`.scss`)
  - Implemented the [LESSCSS](http://lesscss.org) file format (`.less`)
  - Implemented the [JSON](http://json.org/) file format (`.json`)
  - Implemented the [XML](https://www.w3.org/XML) file format (`.xml`)

# 0.0.0 (2016-04-16)
**Repository Reinitialization**
