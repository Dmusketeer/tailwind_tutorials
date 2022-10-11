# tailwind_tutorials

## How to install tailwind :

1.  Add the Play CDN script to your HTML

         Add the Play CDN script tag to the <head> of your HTML file, and start using Tailwind’s utility classes to style your content.

         <script src="https://cdn.tailwindcss.com"></script>

2.  installation of tailwind in production mode: below
    'https://tailwindcss.com/docs/installation/using-postcss'

# Setup Tailwind Css

        1. npm init -y
        2. create src/input.css and public/css and public/index.html
        3. npm install tailwindcss
        4. npx tailwind init and add a path of html files in content section of tailwind.config.js file.
        5. add a script in package.json -> "build":"tailwindcss -i ./src/input.css -o ./public/css/output.css --watch"
        6.link html to css
