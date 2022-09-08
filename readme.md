This is a practice I found in youtube.
Kodus to the original author. [link](https://youtu.be/Vp6GC3jKG20)

```
#### tailwind dependency
$ npm install -D tailwindcss

#### integrate with IDE - class intellisense
$ npm i autoprefixer postcss -D
```

#### create the tailwind.config.js (we modified the config, see the changes in the file)
```
$ npx tailwindcss init
```

#### add to package.json script to watch and compile tailwind
```
$ npx tailwindcss -i ./src/index.css -o ./dist/tailwind.css --watch
```

#### create index.html and add in the required repos
```
    <!-- our tailwind compiled file -->
    <link rel="stylesheet" href="./tailwind.css">

    <!-- google font: selected poppins weights -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
```

#### start practicing with the tutorial: [link](https://youtu.be/Vp6GC3jKG20)