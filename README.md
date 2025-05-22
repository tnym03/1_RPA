<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>商品一覧テスト</title>
    <style>
        .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }
        .product-item {
            border: 1px solid #ccc;
            padding: 15px;
            width: 200px;
            text-align: center;
        }
        .product-name {
            font-weight: bold;
            margin-bottom: 5px;
        }
        .product-price {
            color: #e60000;
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .product-stock {
            color: green;
        }
        .product-item.sold-out .product-stock {
            color: red;
        }
    </style>
</head>
<body>
    <h1>商品一覧</h1>
    <div class="product-list">
        <div class="product-item">
            <p class="product-name">商品A</p>
            <p class="product-price">¥1,980</p>
            <p class="product-stock">在庫あり</p>
        </div>
        <div class="product-item">
            <p class="product-name">商品B</p>
            <p class="product-price">¥2,500</p>
            <p class="product-stock">残りわずか</p>
        </div>
        <div class="product-item">
            <p class="product-name">商品C</p>
            <p class="product-price">¥980</p>
            <p class="product-stock">在庫あり</p>
        </div>
        <div class="product-item sold-out">
            <p class="product-name">商品D</p>
            <p class="product-price">¥3,200</p>
            <p class="product-stock">品切れ</p>
        </div>
        <div class="product-item">
            <p class="product-name">商品E</p>
            <p class="product-price">¥1,200</p>
            <p class="product-stock">在庫あり</p>
        </div>
    </div>
</body>
</html>
