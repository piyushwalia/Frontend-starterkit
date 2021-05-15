# Frontend-starterkit built in LESS
## Starter Kit for Front end development

## Table of Contents
### Folder structure

  1. [Core](#core)
  2. [Layout](#layout)
  3. [modules](#modules)
  4. [plugins](#plugins)
  5. [page.less](#page.less)


- **Core files**

- _button.less
- _fonts.less
- _mixins.less
- _normalize.less
- _reset.less
- _variables.less

- **layout files**

- _global.less

- **modules files**

- _header.less

- **plugins files**

- Any third party css file include

- **Importing file**
- page.less (where all files will be imported)



- **List of mixins used**

 - padding bottom mixin

  ```css
 .aspect-ratio(@width, @height) {
  position: relative;
  width: ~"@{width}px";
  padding-top: (@height / @width) * 100%;     
  height: 0;
    img {
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      transition: all .5s ease;                      
    }
}
  ```


