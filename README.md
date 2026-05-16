# María Valentina Müller 

Personal portfolio site built with plain HTML/CSS. No frameworks, no dependencies.

## Files

```
index.html          → Home page
portfolio.html      → Projects
teaching.html       → Teaching & mediation
style.css           → All styles
cv/                 → Put your CV PDF here
images/             → Put your project images here
```

## How to publish on GitHub Pages

1. Create a GitHub account at github.com
2. Create a new repository named exactly: `yourusername.github.io`
   (replace "yourusername" with your actual GitHub username)
3. Upload all these files to the repository (drag and drop in the GitHub interface)
4. Go to Settings → Pages → Source: Deploy from branch → main → Save
5. Your site will be live at: `https://yourusername.github.io`

## Adding your photo

In `index.html`, replace this block:
```html
<div class="photo-placeholder">
  <span>Photo</span>
</div>
```
With:
```html
<img src="photo.jpg" alt="María Valentina Müller Araya">
```
And upload your photo file (named `photo.jpg`) to the root folder.

## Adding project images

In `portfolio.html`, each project has a commented line like:
```html
<!-- Add project image: <img src="images/atlas.jpg" alt="Disaster Risk Atlas"> -->
```
Uncomment it and upload your image to the `images/` folder.

## Adding your CV

Create a folder named `cv/` and put your PDF there:
```
cv/CV_MariaValentinaMuller_EN.pdf
```
