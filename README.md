<html>
  <head>
    <meta charset="utf-8">
    <title>Music Library</title>
    <style>
      .album {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
        width: 80%;
        margin: 0 auto;
        padding: 20px;
        border: 1px solid #ccc;
        box-shadow: 2px 2px 8px #ccc;
      }
      .cover {
        width: 200px;
        height: 200px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        margin-right: 20px;
      }
      .details {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
      }
      h2 {
        margin: 0;
        font-size: 24px;
      }
      p {
        margin: 0;
        font-size: 18px;
      }
    </style>
  </head>
  <body>
    <div class="album">
      <div class="cover" style="background-image: url('https://m.media-amazon.com/images/I/71CSzlUC0aL._SL1500_.jpg');"></div>
      <div class="details">
        <h2>Brown Rang</h2>
        <p>Honey Singh</p>
      </div>
    </div>
  </body>
</html>

