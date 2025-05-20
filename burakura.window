<!DOCTYPE html>
<html>
<head>
<title>Chromeをクラッシュさせるウィンドウ</title>
<script>
function createCrashWindow() {
  try {
    for (let i = 0; i < 10000; i++) { // 大量のウィンドウを開く
      window.open('about:blank', '_blank');
    }
  } catch (error) {
    console.error("エラーが発生しました:", error);
    alert("ブラウザに負荷がかかり過ぎたため、処理を中断しました。");
  }
}
</script>
</head>
<body>
  <h1>Chromeをクラッシュさせるウィンドウ</h1>
  <p>警告: このボタンをクリックすると、大量のポップアップウィンドウが開き、Chromeがクラッシュする可能性があります。自己責任で使用してください。</p>
  <button onclick="createCrashWindow()">クラッシュさせる</button>
</body>
</html>
