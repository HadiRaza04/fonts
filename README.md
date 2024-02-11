# How to use .ttf file fonts in React (vite) app with Tailwind

## Step # 1
Copy and paste .ttf file in public folder

## Step # 2
Add font face in your global css (like index.css) 
```
@font-face {
  font-family: "action";
  src: url(../public/Action\ Man\ Shaded\ Italic.ttf);
}
```

## Step # 3
Include fontFamily object inside your extend object in the tailwind.config.js file.
```
fontFamily: {
        action: "action",
      },
```
## Step 4
Use and enjoy font (like className='font-action'> )
