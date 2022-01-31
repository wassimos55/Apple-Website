1 - npm init -y
2 - npm install tailwindcss autoprefixer 
3 - create "src" folder
4 - create "tailwind.css" file inside "srs" folder
5 - insert into "tailwind.css"
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
6 - create new folder named "dist"
7 - create "style.css" inside "dist" folder     
8 - create "index.html" inside "dist" folder 
9 - edit this secript inside "package.json" folder 
        "scripts": {
            "build-css": "npx tailwindcss-cli@latest build src/tailwind.css -o dist/style.css"
        },
10 - npm run build-css