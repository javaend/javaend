# JavaEnd
JavaEnd Jenkly theme


## Word Doc
## Install

<https://tianqi.name/jekyll-TeXt-theme/docs/en/quick-start>

```
cd D:\GitPages\jekyll
d:
bundle install
```

 

## Start local

 

```
cd D:\GitPages\jekyll

d:

bundle exec jekyll serve
```

 

 

## Paths

Tutorial Path

`D:\GitPages\jekyll\docs`

 

## Navigation

  There are two types of navigation in TeXt: **Header Navigation** and **Sidebar Navigation**, both are defined in **data/navigation.yml****.**

 

## Sidebar Navigation

To use sidebar navigation, you should first define a navigation in *data/navigation.yml*.

```
docs-en:
  - title:      Start
    children:
      - title:  Quick Start
        url:    /docs/en/quick-start
      - title:  Structure
        url:    /docs/en/structure
      ...
  - title:      Customization
    children:
      - title:  Configuration
        url:    /docs/en/configuration
      - title:  Navigation
        url:    /docs/en/navigation
      ...
```

And then use the defined navigation as article’s sidebar navigation in the Front Matter:

```
sidebar:
  nav: docs-en
```

 

 

## Configuration

 *`_config.yml`* file placed in your site’s root directory,

 

 

## Notes

Tutorials Display Page

/articles/grid-small.html

 

Home Design

/articles/brief-info.html

Or

archive.html?tag=TeXt 

 

Homepage is : **D:\GitPages\jekyll\docs\landing.html** 

We need to replace this with 

 

 

 

 

 

 

 

 
