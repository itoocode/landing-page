
Download bootstrap source files to get scss and js file

### install node-sass globally or locally 
i have install globally in my system

To install
```sh
npm install -g node-sass
```

To compile scss file to css
node-sass -o destinationDirectory sourceDir

### to compile all scss to css
node-sass -o css scss

```sh
node-sass -o css scss/main.scss
```
will compiel all main.scss to css/main.css but we should watch for continues compiling

### watch to compile on chnage
add **-w** flag to watch and update the file 
```sh
node-sass -o css scss/main.scss -w
```



code folding ctrl+shift+]
### Useful Blog posts
* [vs code snippets](https://medium.com/better-programming/20-vs-code-shortcuts-for-fast-coding-cheatsheet-10b0e72fd5d)
* [js chart libraries](https://blog.logrocket.com/top-picks-javascript-chart-libraries/)