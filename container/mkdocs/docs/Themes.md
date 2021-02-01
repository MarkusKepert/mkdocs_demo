# Themes and Theme enhancemnt

## Basic theme integration
Add Theme to mkdocs.yml
```
theme: material
```

## Theme enhancement
Derive existing theme with custom styles:
```
theme: 
    name: material
    language: de
    font: false
    favicon: favicon.png
    logo: logo.png
```

## Extra Styles
Place CSS on top of current theme in an extra file and load this file in mkdocs.yml:
```
extra_css: 
    - css/custom.css
```