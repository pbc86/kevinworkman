# Jekyll totorial on Happy Coding by Kevin Workman

Kevin has a bunch of tutorial on his [website](https://happycoding.io/). Go to Tutorials tab, under HTML, you can find his [Jekyll Tutorial](https://happycoding.io/tutorials/html/jekyll).

Remember to add a **dot** (`.`) just before the / to indicate parent folder instead of root. For instance:

```html
<link rel="stylesheet" type="text/css" href="./styles.css">
<a href="./index.html">Home</a>
        <a href="./contact.html">Contact</a>
        <a href="./beach.html">Beach</a>
```

### Timestamps:

24:34 - Creating Beach.html  
26:11 - Creating folder images  
28:03 - Update `css` as file not found when rendering beach.html due to relative path. _Note_: here Kevin use slash to go to "root" folder, but I have to use ./ to go to current folder instead.  
30:10 - Add `permalink` to `Beach.html`  
30:40 - update `permalink` using **Placeholders** (i.e. from `beach` to `:title`)  
32:30 - create _config.yml file and move the permalink  
35:10 - create `hike.html`
  


