
`index.html`
```html
<html>
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/1.3.5/axios.min.js" integrity="sha512-nnNHpffPSgINrsR8ZAIgFUIMexORL5tPwsfktOTxVYSv+AUAILuFYWES8IHl+hhIhpFGlKvWFiz9ZEusrPcSBQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.12.0/dist/cdn.min.js"></script>
  </head>
  <body>
    <div class="header-container" x-init x-html="(await axios.get('/components/header.html')).data">
      ...
    </div>
    <main>
      Hi!
    </main>
  </body>
</html>
```

`components/header.html`
```html
<h1 style="font-size:5rem;">This is the header!</h1>
<hr>
```
