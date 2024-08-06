# Frontend Mentor - Social links profile solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS/hub). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

Desktop
![Desktop](./screenshots/screenshot_desktop.png)

Mobile
![Mobile](./screenshots/screenshot_mobile.png)

Active
![Active](./screenshots/screenshot_active.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/kephalosk/nft-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://kephalosk.github.io/nft-preview-card-component-main/)

## My process

1. download Project


2. move Project to target folder


3. open Project in IDE


4. read README


5. add .gitignore-file


6. check files


7. check design


8. initialize repo
* create repo on GitHub
* git init
* git add .
* git commit -m "initial commit"
* git remote add origin git@github.com:kephalosk/${projectname}.git
* git push -u origin master

9. check html
* build general structure
* open index.html in browser for comparison

10. check css
* image styling
* font styling
* color styling
* frame styling
* spacing styling

11. check transitions


12. check mobile/responsive design


13. check accessability
* semantic html
* headings
* alternative texts
* language
* clear language
* link texts

14. extract css


15. add screenshots


16. update README


17. publish website

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Desktop-first workflow

### What I learned

I learned to create an overlay effect:
```html
<div class="container">
  <img class="imgNFT" alt="image of NFT" src="images/image-equilibrium.jpg">
  <div class="overlay"><img src="images/icon-view.svg"></div>
</div>
```

```css
.container {
  position: relative;
  height: 100%;
  width: 100%;
  max-height: 350px;
  max-width: 350px;
}

.container:hover .overlay {
  opacity: 1;
}

.overlay {
  align-items: center;
  border-radius: 10px;
  justify-content: center;
  display: flex;
  position: absolute;
  bottom: 0;
  background: hsl(178, 100%, 50%, 0.5);
  color: hsl(0, 0%, 100%);
  height: 100%;
  width: 100%;
  transition: .5s ease;
  opacity:0;
}
```

I learned how to border images:
```css
.imgAvatar {
    border: 1px solid hsl(0, 0%, 100%);
}
```

I learned about letter-spacing:
```css
p {
    letter-spacing: 1px;
}
```

### Continued development

* improve html
* improve css

### Useful resources

- [w3schools](https://www.w3schools.com/) - HTML and CSS knowledge
- [selfhtml](https://wiki.selfhtml.org/wiki/HTML) - HTML knowledge

## Author

- Website - [kephalosk](https://easywebpath.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

None.