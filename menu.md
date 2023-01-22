```yml
navigation:
  - name: Menu
    link: ./index.html
    sublist:
      - name: Image
        link: ./index.html#small-image
  - name: Another Page
    link: ./another-page.html
  - ...
```

### Example:

[Live Example](https://vaibhavvikas.github.io/jekyll-theme-minimalistic/)\
[Code used in GitHub page](https://github.com/vaibhavvikas/jekyll-theme-minimalistic/tree/gh-pages)

Lets say you have a file name xyz.md, you put that into the root dir. Now, add the text in step 1 at the top of the md file. After that for the text in _config.yml you will put it like:

```yml
navigation:
  - name: [Write name of your hyperlink]
    link: ./xyz.html
```

### Adding Card:

Use the code template:
```html
<div class="card">
  <h3>Some Title</h3>
  <p><b>New Delhi</b>, India<br>
  Some Text</p>
  <a href="https://vaibhavvikas.ml/"><span class="card-link-spanner"></span></a>
</div>
```