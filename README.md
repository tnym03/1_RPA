<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ニュース一覧テスト</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .news-list {
            list-style: none;
            padding: 0;
        }
        .news-list li {
            margin-bottom: 10px;
            border-bottom: 1px dotted #ccc;
            padding-bottom: 10px;
        }
        .news-list li a {
            text-decoration: none;
            color: #0066cc;
            font-weight: bold;
        }
        .news-list li span {
            font-size: 0.9em;
            color: #666;
            margin-left: 10px;
        }
    </style>
</head>
<body>
    <h1>最新ニュース</h1>
    <ul class="news-list">
        <li>
            <a href="article1.html">タイトル1：新技術が発表されました</a>
            <span>(2025/05/22)</span>
        </li>
        <li>
            <a href="article2.html">タイトル2：経済指標が改善傾向に</a>
            <span>(2025/05/21)</span>
        </li>
        <li>
            <a href="article3.html">タイトル3：地域イベント開催のお知らせ</a>
            <span>(2025/05/20)</span>
        </li>
        <li>
            <a href="article4.html">タイトル4：スポーツ大会の結果速報</a>
            <span>(2025/05/19)</span>
        </li>
    </ul>

    <h2>カテゴリ別ニュース</h2>
    <ul class="category-news-list">
        <li><a href="category_a.html">カテゴリAのニュース</a></li>
        <li><a href="category_b.html">カテゴリBのニュース</a></li>
    </ul>
</body>
</html>
