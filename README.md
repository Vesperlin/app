<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vesper 系统入口</title>
  <style>
    body { margin:0; font-family:-apple-system; background:#111; color:#fff; }
    header { padding:15px; text-align:center; font-size:20px; font-weight:bold; border-bottom:1px solid #333; }
    .search { margin:15px; }
    .search input {
      width:100%; padding:10px; border:none; border-radius:8px;
      background:#222; color:#fff; font-size:14px;
    }
    .section { margin:15px; }
    .section h2 { font-size:16px; color:#aaa; margin-bottom:10px; }
    .cards { display:flex; flex-wrap:wrap; gap:10px; }
    .card {
      flex:1 1 45%; background:#222; padding:20px; border-radius:10px;
      text-align:center; font-size:16px; font-weight:bold; cursor:pointer;
      transition:0.3s;
    }
    .card:hover { background:#333; color:#4da6ff; }
    footer {
      position:fixed; bottom:0; left:0; right:0; height:50px;
      background:#222; display:flex; justify-content:space-around; align-items:center;
      font-size:14px; border-top:1px solid #333;
    }
    footer div { cursor:pointer; }
    footer div.active { color:#4da6ff; font-weight:bold; }
  </style>
</head>
<body>
  <header>Vesper 系统入口</header>
  <div class="search">
    <input type="text" placeholder="🔍 搜索功能...">
  </div>
  <div class="section">
    <h2>收藏夹</h2>
    <div class="cards">
      <div class="card">OCR</div>
      <div class="card">AI 助手</div>
    </div>
  </div>
  <div class="section">
    <h2>全部功能</h2>
    <div class="cards">
      <div class="card">OCR</div>
      <div class="card">AI 助手</div>
      <div class="card">工具箱</div>
      <div class="card">我的</div>
    </div>
  </div>
  <footer>
    <div class="active">首页</div>
    <div>收藏</div>
    <div>我的</div>
    <div>设置</div>
  </footer>
</body>
</html>
