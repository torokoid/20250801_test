# 20250801_test

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>テストサイト</title>
  <style>
    body {
      background: #222;
      color: #fff;
      font-family: "Arial", "Helvetica Neue", Helvetica, sans-serif;
      margin: 0;
      padding: 0;
      min-height: 100vh;
    }
    header, footer {
      background: #333;
      padding: 1em 0.5em;
      text-align: center;
      color: #fff;
    }
    main {
      max-width: 600px;
      margin: 2em auto;
      padding: 1em;
      background: #282828;
      border-radius: 12px;
      box-shadow: 0 0 10px #0004;
    }
    h1, h2, h3, h4 {
      color: #fff;
      margin-top: 0;
    }
    p, .note, .subtext {
      color: #fff;
      font-size: 1em;
      line-height: 1.7;
    }
    a {
      color: #fff;
      text-decoration: underline;
      word-break: break-all;
    }
    img {
      width: 100%;
      max-width: 600px;
      height: auto;
      display: block;
      margin: 1em 0;
      border-radius: 8px;
      box-shadow: 0 0 12px #0003;
    }
    .youtube-wrapper {
      position: relative;
      width: 100%;
      max-width: 600px;
      margin: 1em 0;
      padding-bottom: 56.25%; /* 16:9 */
      height: 0;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 0 12px #0003;
      background: #111;
    }
    .youtube-wrapper iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }
    button, input, select, textarea {
      background: #333;
      color: #fff;
      border: 1px solid #444;
      border-radius: 4px;
      padding: 0.4em 0.8em;
      margin: 0.4em 0;
      font-size: 1em;
    }
    @media (max-width: 700px) {
      main, img, .youtube-wrapper {
        max-width: 100vw;
        border-radius: 0;
      }
      main {
        margin: 0;
        padding: 0.5em;
        box-shadow: none;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>テストサイト</h1>
    <p class="subtext">灰色の文字はすべて白色に変更済み</p>
  </header>
  <main>
    <h2>サンプル画像</h2>
    <a href="20250725_024.JPG" target="_blank">
      <img src="20250725_024.JPG" alt="サンプル画像">
    </a>
    <p class="note">クリックで拡大表示できます。</p>
    <h2>サンプルYouTube動画</h2>
    <div class="youtube-wrapper">
      <iframe src="https://www.youtube.com/embed/Q-zFz772_1s?si=CEiXoJj3mkp-pc5w"
        title="YouTube video player"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>
    <p>動画の幅も画像と揃えて表示されます。</p>
    <h2>リンクの表示例</h2>
    <p>
      <a href="https://torokoid.github.io/20250725_tochigi/" target="_blank">リンク例（外部サイト）</a>
    </p>
    <h2>フォーム・ボタンの例</h2>
    <form>
      <label for="name">名前：</label>
      <input type="text" id="name" name="name" placeholder="お名前">
      <br>
      <button type="submit">送信</button>
    </form>
    <p class="note">フォーム・ボタンもダークテーマに対応しています。</p>
  </main>
  <footer>
    &copy; 2025 テストサイト
  </footer>
</body>
</html>
