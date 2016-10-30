<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-logo-banner.svg"/></p>

<p align="center"><img src="https://cdn.travis-ci.org/images/favicon-c566132d45ab1a9bcae64d8d90e4378a.svg" width=24 height=24/> <a href="https://travis-ci.org/arcticicestudio/northem-dark"><img src="https://img.shields.io/travis/arcticicestudio/northem-dark/develop.svg"/></a> <img src="https://circleci.com/favicon.ico" width=24 height=24/> <a href="https://circleci.com/gh/arcticicestudio/northem-dark"><img src="https://circleci.com/gh/arcticicestudio/northem-dark.svg?style=shield&circle-token=bce8ea0d5284b23cba9771040e39a10b9cd152e5"/></a> <img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/northem-dark/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/northem-dark.svg"/></a> <a href="https://github.com/arcticicestudio/northem-dark/releases/latest"><img src="https://img.shields.io/badge/pre--release---_-blue.svg"/></a> <img src="https://www.npmjs.com/static/images/touch-icons/favicon-32x32.png" width=24 height=24/> <a href="https://www.npmjs.com/package/northem-dark"><img src="https://img.shields.io/npm/v/northem-dark.svg"/></a> <a href="https://www.npmjs.com/package/northem-dark"><img src="https://img.shields.io/npm/dt/northem-dark.svg"/></a> <a href="https://www.npmjs.com/package/northem-dark"><img src="https://img.shields.io/npm/dm/northem-dark.svg"/></a></p>

<p align="center">A north-bluish, dark color palette.</p>

<p align="center">Created for the clean- and minimal flat design pattern to achieve a optimal focus and readability for code syntax highlighting and UI.
It consists of a total of sixteen, carefully selected, dimmed pastel colors for a eye-comfortable, but yet colorful ambiance.</p>

<p align="center">This project is a more blue-tinged variation of the origin project [Northem](hhtps://github.com/arcticicestudio/northem).</p>

---

The color palette it divided into four named components to represent the different color effects.

![Northem Dark Palette Overview](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-overview.svg)

Northem Dark colors are numbered from `northem-dark0` to `northem-dark15` where each component contains a different amount of colors:  
  1. **Dark Water** `northem-dark0` - `northem-dark3`  
  2. **Light Wind** `northem-dark4` - `northem-dark6`  
  3. **Ice** `northem-dark7` - `northem-dark10`  
  4. **Rainbow** `northem-dark11` - `northem-dark15`  

This naming convention allows an uncomplicated use for terminals and preserves the compatibility to similar projects like [base16](http://chriskempson.com/projects/base16).

## Usage
To show a list of all available [Gulp][gulp] tasks run `gulp` or `gulp help`.

### CSS
The [CSS specification](https://www.w3.org/TR/css-variables) supports the usage of primitive value types to define custom properties which can be used to create e.g. color variables.  
Northem provides the `template-css.scss` template file to compile a `northem-dark.css` stylesheet.

The generated file contains all Northem Dark color variables prefixed with `--` inside the `:root` pseudo-class.  
The `:root` pseudo-class represents an element that is the root of the document.  
This is always the HTML (`<html>`) element which allows to use the Northem Dark color variables for the whole document.

The `northem-dark.css` stylesheet can be compiled via [Gulp][gulp]:  
```sh
npm install
gulp compile-css-template
```

### <img src="http://sass-lang.com/favicon.ico" width=16 height=16 /> Sass
Copy the `northem-dark.scss` file into your project and import it in your [Sass](http://sass-lang.com) files:
```css
@import "northem-dark";
```
The `.scss` file extension is optional.

#### <img src="http://sassdoc.com/favicon.png" width=16 height=16 /> SassDoc
Northem Dark Sass sources are documented using the [SassDoc](http://sassdoc.com) documentation syntax which can be compiled to a HTML documentation via [Gulp][gulp]:  
```sh
npm install
gulp sassdoc
```
The Sassdoc theme can be changed by editing the `.sassdocrc` configuration file.

### <img src="http://lesscss.org/public/ico/favicon.ico" width=16 height=16/> LESSCSS
Copy the `northem-dark.less` file into your project and import it in your [LESSCSS](http://lesscss.org) files:  
```css
@import "northem-dark";
```
Information about how the `@import` statement handles imports with different file extensions can be found in the [official LESSCSS documentation](http://lesscss.org/features/#import-directives-feature).

#### KSS
Northem Dark LESSCSS sources are documented using the [KSS](http://warpspire.com/kss) documentation syntax.  
Information about the generation of a styleguide can be found in the [official KSS documentation](http://warpspire.com/kss/styleguides).

### <img src="https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/icon-color-swatch.svg"/> Color Swatches
Northem Dark is available in various native formats:
  - `.aco` Adobe Photoshop Palette
  - `.ase` Adobe Swatch Exchange
  - `.gpa` Gpick Palette
  - `.gpl` GIMP/Inkscape/CinePaint/Krita Palette
  - `.mtl` Alias/WaveFront Material

A list of detailed information about each file format can be found [here](http://www.selapa.net/swatches/colors/fileformats.php).

## Projects
[![Northem Dark Atom Syntax](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-atom-syntax-banner.svg)](https://atom.io/themes/northem-dark-atom-syntax)  
[![Northem Dark Atom UI](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-atom-ui-banner.svg)](https://atom.io/themes/northem-dark-atom-ui)  
[![Northem Dark Eclipse Syntax](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-eclipse-syntax-banner.svg)](https://github.com/arcticicestudio/northem-dark-eclipse-syntax)  
[![Northem Dark IntelliJ IDEA Syntax](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-intellij-idea-syntax-banner.svg)](https://github.com/arcticicestudio/northem-dark-intellij-idea-syntax)  
[![Northem Dark Java](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-java-banner.svg)](https://github.com/arcticicestudio/northem-dark-java)  
[![Northem Dark Notepad++](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-notepadplusplus-banner.svg)](https://github.com/arcticicestudio/northem-dark-notepadplusplus)  
[![Northem Dark Terminix](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-terminix-banner.svg)](https://github.com/arcticicestudio/northem-dark-terminix)  
[![Northem Dark Vim](https://cdn.rawgit.com/arcticicestudio/northem-dark/develop/src/assets/northem-dark-vim-banner.svg)](https://github.com/arcticicestudio/northem-dark-vim)  

## Development
[![](https://img.shields.io/badge/Changelog-1.0.0-blue.svg)](https://github.com/arcticicestudio/northem-dark/blob/v1.0.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow_Branching_Model-blue.svg)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-blue.svg)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/northem-dark/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center"> <img src="http://arcticicestudio.com/favicon.ico" width=16 height=16/> Copyright &copy; 2016 Arctic Ice Studio</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-blue.svg"/></a></p>

[gulp]: http://gulpjs.com
