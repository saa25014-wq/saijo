<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>名水の街・愛媛県西条市</title>
    <style>
        /* 全体のリセットと基本スタイル */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', Meiryo, sans-serif;
            line-height: 1.8;
            color: #333;
            background-color: #f7f9fa;
        }
        
        /* ヘッダーデザイン */
        header {
            background: linear-gradient(135deg, #1d70b8 0%, #00a3af 100%);
            color: #fff;
            text-align: center;
            padding: 4rem 1rem;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        header h1 {
            font-size: 2.8rem;
            font-weight: 700;
            letter-spacing: 0.1em;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        header p {
            margin-top: 1rem;
            font-size: 1.1rem;
            opacity: 0.9;
        }

        /* コンテンツ幅の制限 */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 3rem 1.5rem;
        }

        /* セクション共通スタイル */
        section {
            background-color: #fff;
            padding: 2.5rem;
            margin-bottom: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.05);
        }
        h2 {
            font-size: 1.8rem;
            color: #1d70b8;
            border-left: 5px solid #00a3af;
            padding-left: 0.8rem;
            margin-bottom: 1.5rem;
        }

        /* 紹介文 */
        .intro-text {
            font-size: 1.1rem;
            text-indent: 1em;
            margin-bottom: 1rem;
            text-align: justify;
        }

        /* 画像エリア */
        .image-container {
            text-align: center;
            margin: 2rem 0;
        }
        .city-image {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.1);
        }
        .image-caption {
            font-size: 0.9rem;
            color: #666;
            margin-top: 0.8rem;
        }

        /* リスト（魅力紹介） */
        .spots-list {
            list-style: none;
        }
        .spots-list li {
            position: relative;
            padding-left: 1.8rem;
            margin-bottom: 1.2rem;
            font-size: 1.05rem;
        }
        .spots-list li::before {
            content: "✦";
            position: absolute;
            left: 0;
            color: #00a3af;
            font-size: 1.2rem;
            line-index: 1;
        }
        .spots-list strong {
            color: #1d70b8;
            font-size: 1.1rem;
        }

        /* テーブル */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1rem;
            background-color: #fff;
        }
        th, td {
            padding: 1rem;
            border-bottom: 1px solid #e0e0e0;
            text-align: left;
        }
        th {
            background-color: #f0f7fa;
            color: #1d70b8;
            width: 25%;
            font-weight: 600;
        }
        td {
            font-size: 0.95rem;
        }

        /* ボタンエリア */
        .button-group {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            flex-wrap: wrap;
            margin-top: 3rem;
        }
        .btn {
            display: inline-block;
            padding: 1rem 2rem;
            font-size: 1.05rem;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            transition: all 0.3s ease;
            text-align: center;
            min-width: 250px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
        }
        /* ボタン1: 公式サイト（青系） */
        .btn-official {
            background-color: #1d70b8;
            color: #fff;
        }
        .btn-official:hover {
            background-color: #15528a;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(29, 112, 184, 0.3);
        }
        /* ボタン2: 観光協会（オレンジ・緑系などアクセント） */
        .btn-external {
            background-color: #e07a5f;
            color: #fff;
        }
        .btn-external:hover {
            background-color: #c9654b;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(224, 122, 95, 0.3);
        }

        /* フッター */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 4rem;
            font-size: 0.9rem;
        }

        /* レスポンシブ対応 */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2.2rem;
            }
            section {
                padding: 1.5rem;
            }
            th, td {
                display: block;
                width: 100%;
            }
            th {
                border-bottom: none;
                padding-bottom: 0.2rem;
            }
            td {
                padding-top: 0.2rem;
                padding-bottom: 1rem;
            }
            .button-group {
                flex-direction: column;
                align-items: center;
            }
            .btn {
                width: 100%;
            }
        }
    </style>
</head>
<body>

    <!-- ページ最上部の大見出し -->
    <header>
        <h1>愛媛県 西条市</h1>
        <p>〜 石鎚の恵み、名水が育む感動 of 街 〜</p>
    </header>

    <div class="container">

        <!-- 西条市の魅力・特徴（3文以上） -->
        <section>
            <h2>西条市について</h2>
            <p class="intro-text">
                愛媛県東部に位置する西条市は、西日本最高峰である「石鎚山（いしづちさん）」の麓に広がり、豊かな自然と四国屈指の工業地帯が調和した美しい街です。
            </p>
            <p class="intro-text">
                市内各所から湧き出る「うちぬき」と呼ばれる清らかな自噴水は、日本の名水百選にも選ばれており、市民の生活や様々な産業を古くから支え続けています。
            </p>
            <p class="intro-text">
                また、日本一のお祭り好きとも称される活気あふれる秋の伝統「西条まつり」や、独自の製法で守り継がれてきた幻の後発酵茶「石鎚黒茶」など、独自の歴史と豊かな食文化が現代に息づいています。
            </p>

            <!-- 配布された写真の表示エリア（ファイル名を修正しました） -->
            <div class="image-container">
                <img src="kurocha_2.jpg" alt="石鎚黒茶" class="city-image">
                <p class="image-caption">西条市が誇る伝統の幻のお茶「石鎚黒茶」</p>
            </div>
        </section>

        <!-- 観光スポットや名産品の紹介（3つ以上の箇条書き） -->
        <section>
            <h2>西条市の見どころ・名産品</h2>
            <ul class="spots-list">
                <li>
                    <strong>霊峰 石鎚山（いしづちさん）</strong><br>
                    西日本最高峰（標高1,982m）を誇り、日本百名山の一つに数えられます。四季折々のダイナミックな渓谷美や紅葉が楽しめ、登山客に絶大な人気を誇ります。
                </li>
                <li>
                    <strong>名水「うちぬき」</strong><br>
                    石鎚山系の伏流水が地中から自然に湧き出る清水です。街の至る所に水汲み場があり、いつでも美味しい名水を無料で味わうことができます。
                </li>
                <li>
                    <strong>西条まつり</strong><br>
                    毎年10月に開催される西条市最大のお祭りです。150台以上の豪華絢爛な「だんじり」や「みこし」が街を練り歩き、その熱気と美しさは見る者を圧倒します。
                </li>
                <li>
                    <strong>幻のお茶「石鎚黒茶（いしづちくろちゃ）」</strong><br>
                    独自の二段階発酵技術で作られる、全国的にも非常に珍しい伝統的な後発酵茶です。すっきりとした独特の酸味と、深みのある琥珀色が特徴の逸品です。
                </li>
            </ul>
        </section>

        <!-- 市の情報をまとめた表（table） -->
        <section>
            <h2>市の基本情報</h2>
            <table>
                <tr>
                    <th>所在地</th>
                    <td>愛媛県西条市明屋敷164番地（市役所）</td>
                </tr>
                <tr>
                    <th>人口</th>
                    <td>約103,000人</td>
                </tr>
                <tr>
                    <th>特産品</th>
                    <td>うちぬき（名水）、石鎚黒茶、愛宕柿（あたごがき）、西条のり、ハダカムギ</td>
                </tr>
                <tr>
                    <th>アクセス</th>
                    <td>
                        【鉄道】JR予讃線「伊予西条駅」下車（松山駅から特急で約1時間）<br>
                        【車】松山自動車道「いよ西条IC」より各方面へ
                    </td>
                </tr>
            </table>
        </section>

        <!-- 外部リンクボタン（2種類） -->
        <div class="button-group">
            <a href="https://www.city.saijo.ehime.jp/" class="btn btn-official" target="_blank" rel="noopener noreferrer">
                西条市 公式サイトを開く
            </a>
            <a href="https://www.saijo-imadoki.jp/" class="btn btn-external" target="_blank" rel="noopener noreferrer">
                西条市観光物産協会 を開く
            </a>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 Saijo City Information Page. All Rights Reserved.</p>
    </footer>

</body>
</html>
