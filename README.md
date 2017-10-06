## How to view Project
To inspect the site on your phone, you can run a local server using Terminal or command prompt:
`$> cd /path/to/your-project-folder`
`$> python -m SimpleHTTPServer 8080`
Then, Open a browser and visit `localhost:8080`

Download and install ngrok to the top-level of your project directory to make your local server accessible remotely.
To run using ngrok:
`$> cd /path/to/your-project-folder`
`$> ./ngrok http 8080`

## Optimized

Main Project: (PageSpeed Score is 95.0 for Desktop and 94.0 for Mobile)
1. index.html: Minified CSS and used media tag.
2. index.html: Encapsulated JS — with asynchronous load.
3. index.html: Async. loading for web fonts.
4. Minify perfmatters.js.
5. Optimized Image(s).

Pizza:
1. Optimized Image(s).
2. Minimized pizza generation to 50.
3. Extracted variable declarations and scope assignment (line 500 on main.js).
4. Remove 'determineDx' function.
5. Refactor 'changePizzaSizes' function.
6. Moved 'pizzasDiv' outside loop. (~line 479).
7. Dynamically calculating pizzas (~line 529 - 534).
8. Declaring 'elem' var outside loop (~line 546).
