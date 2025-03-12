<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>🎨 趣味拼图大冒险 🧩</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

  <h1>🎉 趣味拼图大冒险 🧩</h1>

  <div>
    <label for="rows">行数：</label>
    <input type="number" id="rows" value="3" min="2" max="10">
    <label for="cols">列数：</label>
    <input type="number" id="cols" value="3" min="2" max="10">
    <button id="startBtn">开始游戏</button>
  </div>

  <div>
    <button id="shuffleBtn">🔀 一键洗牌</button>
    <button id="restartBtn">🔄 重新开始</button>
  </div>

  <div id="puzzleContainer" class="puzzle-container"></div>

  <div id="winMessage" class="win-message">🎉 恭喜你，拼图完成！ 🎉</div>

  <script src="js/script.js"></script>
</body>
</html>
