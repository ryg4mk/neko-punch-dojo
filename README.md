# 猫パンチ道場 / NekoPunchDojo

ONE TAKE GAME #010  
タイトル：猫パンチ道場  
英字名：NekoPunchDojo  
Model：GPT-5.6 Sol

スマートフォン縦画面向け、60秒の猫パンチ反射神経スコアアタック。左下・右下のパンチボタン（PCではA/Dキー）で対応するパンチゾーンの対象を叩きます。対象の直接タップは無効です。

- **OK**：毛糸玉、ネズミ、ボール、羽根、魚、虫
- **NG**：おやつ、ごはん皿、子猫、飼い主の手。叩かず通過させます。
- **PERFECT**：ゾーン中心に近い位置でパンチすると150点（通常100点）、肉球演出。
- **コンボ**：10連続ごとに倍率が0.2ずつ増加（上限2倍）。ミスでリセット。
- **3ミス制**：空振り・OK見逃し・NG誤打などでミス。3回で終了。
- **60秒ルール**：60秒完走、または3ミスで結果画面へ。
- **BEST**：ブラウザのlocalStorageに保存。

## GitHub Pages公開

`index.html`、`style.css`、`game.js`をリポジトリ `neko-punch-dojo` のルートにアップロードし、Settings → Pages → Deploy from a branch → main / (root) を選択。公開先は `https://<ユーザー名>.github.io/neko-punch-dojo/`。

外部ライブラリ・画像・音源・フォントなし。効果音はWeb Audio API。音が出ない環境でもプレイできます。
