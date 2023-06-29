# The Living Room 🛋️
This is where I post my most recent projects, check out the site here -> https://lukeatkins.me/

I had a wonderful time creating this site using a Tailwind css and Spline for the 3D background. The
css of my site, created with the class names from tailwind was designed with moblie first principles.
The background was desinged by using random noise filters to distort the geometry of a sphere, colored with 
light hues. 

Tech stack used: HTML, CSS, JS, TailwindCSS, and Spline

# Usage
I would like to offer anyone who would like to use this repository as a starting place for their own
personal website template. I myself had been looking for template as simple as mine, but could 
never find it, and I was reluctant to build myown from scratch, but in the end I am glad I did!
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
### Create a 
```shell
# Ubuntu
$ sudo apt install cmake libsndfile1-dev libsamplerate0-dev qt6-base-dev qt6-multimedia-dev

# macOS
$ brew install cmake libsamplerate libsndfile pkg-config qt
```

### Compilation
```shell
$ cmake -B build && cd build
$ cmake --build . -j
```

## Usage
## GUI
To launch the TMS Express GUI frontend, simply invoke the program with no arguments

```shell
$ tmsexpress
```

## The Encode Command
The `encode` command accepts audio file(s) and a variety of parameters which affect how they are processed, analyzed,
and formatted for output. TMS Express automatically detects when the input path is a directory and performs a batch job.

```shell
$ tmsexpress encode [OPTIONS] input output
```

### Explanation of Options
