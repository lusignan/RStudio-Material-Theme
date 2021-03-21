# RStudio-Material-Theme

Full RStudio port of [Mattia Astorino](https://github.com/equinusocio)'s [Material Theme](https://github.com/material-theme/vsc-material-theme).

<figure>
    <figcaption>Material:</figcaption>
    <img src="https://github.com/lusignan/RStudio-Material-Theme/blob/main/img/material-preview.png"
         alt="Material">    
</figure>

<figure>
    <figcaption>Material Darker:</figcaption>
    <img src="https://github.com/lusignan/RStudio-Material-Theme/blob/main/img/material-darker-preview.png"
         alt="Material Darker">    
</figure>

<figure>
    <figcaption>Material Palenight:</figcaption>
    <img src="https://github.com/lusignan/RStudio-Material-Theme/blob/main/img/material-palenight-preview.png"
         alt="Material Palenight">
</figure>

To install the Palenight variant, run the following in the RStudio console:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material-palenight.rstheme", apply = TRUE)
```

<figure>
    <figcaption>Material Ocean:</figcaption>
    <img src="https://github.com/lusignan/RStudio-Material-Theme/blob/main/img/material-ocean-preview.png"
         alt="Material Ocean">    
</figure>

To install the Ocean variant, run the following in the RStudio console:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material-ocean.rstheme", apply = TRUE)
```

<figure>
    <figcaption>Material Lighter:</figcaption>
    <img src="https://github.com/lusignan/RStudio-Material-Theme/blob/main/img/material-lighter-preview.png"
         alt="Material Lighter">
</figure>

## Installation
To install, download the folder, unzip, and open RStudio. From RStudio click Preferences, Appearance, Add, and then navigate to the rstheme for the theme that you'd like to install. Click apply.

If you're comfortable installing from the console and have Devtools installed then you can copy the following into your console:

Material:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material.rstheme", apply = TRUE)
```
Darker:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material-darker.rstheme", apply = TRUE)
```
Palenight:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material-palenight.rstheme", apply = TRUE)
```
Ocean:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material-ocean.rstheme", apply = TRUE)
```
Lighter:
```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/RStudio-Material-Theme/main/material-lighter.rstheme", apply = TRUE)
```

## Acknowledgements
* Palette by [Mattia Astorino](https://github.com/equinusocio)
* Theme was largely built using [Garrick Aden-Buie](https://github.com/gadenbuie)'s [rsthemes package](https://github.com/gadenbuie/rsthemes)
