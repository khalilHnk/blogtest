<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <meta name="description" content="experimental blog page">
    <style>
      body,.pg,.pg * {outline:1px dashed green;margin:0;padding:0;box-sizing:border-box}
      .flx{display:flex;align-items:center}
      .pg{justify-content:space-between;flex-direction:column;border:10px solid #000;background:#ccc;text-align:center}
      header,footer{line-height:2;background-color:rgba(255,255,0,0.2)}
      article{min-width:200px;min-height:200px}
    </style>
    <title>Blog 1</title>
  </head>
  <body>
    <div class="flx pg">
      <header>
        <h1>MAIN TITLE</h1>
      </header>
      <main style="outline:4px solid rgba(255,0,0,0.4)">
        <article>
          <h2>ARTICLE</h2>
          <p>
            Text : paragraphe.
          </p>
        </article>
      </main>
      <footer>
        <p>Blog&copy;2021</p>
      </footer>
    </div>
  </body>
</html>
