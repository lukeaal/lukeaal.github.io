# The Living Room 🛋️
This is where I post my most recent projects, check out the site here -> https://lukeatkins.me/

I had a wonderful time creating this site using a Tailwind css and Spline for the 3D background. The
css of my site, created with the class names from Tailwind was designed with moblie first principles.
The background was made by using random noise filters to distort the geometry of a sphere, and colored with 
light hues. 

Tech stack used: HTML, CSS, JS, TailwindCSS, and Spline

# Usage
I would like to offer anyone who would like to use this repository as a starting place for their own
personal website template, to do so. I had been looking for templates as simple as this, but could 
never find it, and I was reluctant to build my own from scratch, but in the end I am glad I did!
Setting up this site is fairly simple, put your own spin on it!

# Installation and Dependancies
## 1. Install TailwindCSS 
(sourced from TailwindCSS docs) -> https://v2.tailwindcss.com/docs/installation

Using your mac terminal run the following command in your project directory

```shell
$ npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
```
Then init TailwindCSS by running

```shell
$ npx tailwindcss init
```

Note that in the CSS file of this project these TailwindCSS components are already there

```CSS
/* ./your-css-folder/styles.css */
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## 2. Design your own Spline 3D Background
### Create a Spline account
Spline website -> https://spline.design/

This is where you can create and save your 3D creations. You could follow a tutorial on 
Youtube or start from scratch if you are already familair with something like Blender. 
Once your design is complete, create an animation for it and set the camera angle. Spline also offers the option to create immersive 3D worlds that visitors of your site can explore. Here is a cool example template that one could find on the Spline website
to start from -> https://app.spline.design/library/a6d6b73b-0ab2-44d4-a53a-b869c2162742 

Once you have completed your design, you can export your work in the form of a link, 
this link can then be embedded into your websites background by simply copy and pasting 
the link into the index.html file of your project. For example, my own website...

inside of the index.html file, near the head of the document, the embedding is as follows.
```HTML
<!--My head and styling are above this--> 
<body class="gradient-bg">
  <div class="spline-view-bg">
    <!--Here is the embedding, just copy and paste from Spline (export as embed)--> 
    <script type="module" src="https://unpkg.com/@splinetool/viewer@0.9.366/build/spline-viewer.js"></script>
    <spline-viewer url="https://prod.spline.design/Q6uqLDKQMUySYmup/scene.splinecode">
    </spline-viewer>
  </div>
  <!--My body and footer are belllow this--> 
</body>  
```


# Usage (if you want copy my work)
## 1. Replace photos, text, and links
Be sure to go over every link and text in the index.html page so that all of your github links are corretly placed. While I would not mind the extra SEO, I wish you the best in your thourough look though the code. Take the photos and replace them with whatever you would like. The CouchEmoji icon should be about 24pt by 24pt, and the profile photo should be about 600px by 800px.
