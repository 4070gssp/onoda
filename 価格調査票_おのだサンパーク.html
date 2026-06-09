<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>競合店価格調査票 — おのだサンパーク店</title>
<style>
  :root {
    --navy: #1a2744;
    --teal: #0d7a6e;
    --teal-light: #e6f4f2;
    --amber: #e8940a;
    --amber-light: #fff8e6;
    --red: #d93025;
    --gray-100: #f5f6f8;
    --gray-200: #e8eaed;
    --gray-400: #9aa0a6;
    --gray-600: #5f6368;
    --gray-900: #202124;
    --white: #ffffff;
    --radius: 12px;
    --shadow: 0 2px 8px rgba(0,0,0,0.12);
  }

  * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
  
  body {
    font-family: 'Hiragino Sans', 'Hiragino Kaku Gothic ProN', 'Noto Sans JP', sans-serif;
    background: var(--gray-100);
    color: var(--gray-900);
    min-height: 100vh;
    padding-bottom: 80px;
  }

  /* Header */
  .header {
    background: var(--navy);
    color: white;
    padding: 16px 16px 12px;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 12px rgba(0,0,0,0.2);
  }
  .header-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 8px; }
  .header-title { font-size: 15px; font-weight: 700; letter-spacing: 0.03em; }
  .header-subtitle { font-size: 11px; color: rgba(255,255,255,0.6); margin-top: 1px; }
  .progress-bar-wrap { background: rgba(255,255,255,0.15); border-radius: 4px; height: 4px; }
  .progress-bar { background: var(--amber); height: 4px; border-radius: 4px; transition: width 0.4s ease; }
  .progress-label { font-size: 11px; color: rgba(255,255,255,0.7); margin-top: 5px; text-align: right; }

  /* Survey meta */
  .meta-panel {
    background: white;
    margin: 12px 12px 0;
    border-radius: var(--radius);
    padding: 14px;
    box-shadow: var(--shadow);
  }
  .meta-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .meta-field label { font-size: 11px; color: var(--gray-600); font-weight: 600; display: block; margin-bottom: 4px; }
  .meta-field input {
    width: 100%;
    border: 1.5px solid var(--gray-200);
    border-radius: 8px;
    padding: 9px 10px;
    font-size: 14px;
    font-family: inherit;
    outline: none;
    transition: border-color 0.2s;
  }
  .meta-field input:focus { border-color: var(--teal); }
  .meta-field.full { grid-column: 1 / -1; }

  /* Category tabs */
  .cat-scroll {
    overflow-x: auto;
    padding: 12px 12px 0;
    scrollbar-width: none;
    display: flex;
    gap: 8px;
  }
  .cat-scroll::-webkit-scrollbar { display: none; }
  .cat-tab {
    flex-shrink: 0;
    padding: 8px 14px;
    border-radius: 20px;
    border: 1.5px solid var(--gray-200);
    background: white;
    font-size: 13px;
    font-weight: 600;
    color: var(--gray-600);
    cursor: pointer;
    transition: all 0.2s;
    white-space: nowrap;
    position: relative;
  }
  .cat-tab.active {
    background: var(--navy);
    color: white;
    border-color: var(--navy);
  }
  .cat-tab .badge {
    position: absolute;
    top: -5px; right: -5px;
    background: var(--amber);
    color: white;
    font-size: 10px;
    font-weight: 700;
    border-radius: 10px;
    min-width: 18px;
    height: 18px;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0 4px;
  }

  /* Section */
  .section { padding: 12px; }

  /* Item cards */
  .item-card {
    background: white;
    border-radius: var(--radius);
    margin-bottom: 10px;
    box-shadow: var(--shadow);
    overflow: hidden;
    border-left: 4px solid var(--gray-200);
    transition: border-color 0.2s;
  }
  .item-card.filled { border-left-color: var(--teal); }
  .item-card.skipped { border-left-color: var(--gray-400); opacity: 0.7; }

  .item-head {
    display: flex;
    align-items: center;
    padding: 12px 12px 8px;
    gap: 8px;
  }
  .item-num {
    background: var(--gray-100);
    color: var(--gray-600);
    font-size: 11px;
    font-weight: 700;
    border-radius: 6px;
    padding: 2px 7px;
    flex-shrink: 0;
  }
  .item-name {
    font-size: 13px;
    font-weight: 600;
    line-height: 1.4;
    flex: 1;
  }
  .item-name-wrap { flex: 1; }
  .item-jan {
    font-size: 11px;
    color: var(--gray-400);
    font-family: 'SF Mono', 'Consolas', monospace;
    margin-top: 3px;
    letter-spacing: 0.03em;
  }
  .item-jan-label {
    font-size: 10px;
    color: var(--gray-400);
    font-weight: 600;
    margin-right: 2px;
  }

  .item-body { padding: 0 12px 12px; display: flex; gap: 10px; align-items: center; }
  
  .price-wrap {
    position: relative;
    flex: 1;
  }
  .price-wrap .yen {
    position: absolute;
    left: 11px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 15px;
    font-weight: 700;
    color: var(--teal);
    pointer-events: none;
  }
  .price-input {
    width: 100%;
    border: 1.5px solid var(--gray-200);
    border-radius: 8px;
    padding: 10px 10px 10px 28px;
    font-size: 18px;
    font-weight: 700;
    font-family: inherit;
    color: var(--gray-900);
    outline: none;
    transition: border-color 0.2s;
    -webkit-appearance: none;
  }
  .price-input:focus { border-color: var(--teal); background: var(--teal-light); }
  .price-input::placeholder { color: var(--gray-400); font-size: 14px; font-weight: 400; }
  .price-input.has-value { border-color: var(--teal); }

  .skip-btn {
    padding: 10px 12px;
    border-radius: 8px;
    border: 1.5px solid var(--gray-200);
    background: white;
    font-size: 12px;
    color: var(--gray-600);
    cursor: pointer;
    flex-shrink: 0;
    transition: all 0.2s;
  }
  .skip-btn.active {
    background: var(--gray-100);
    color: var(--gray-400);
    border-color: var(--gray-200);
  }

  .item-note {
    padding: 0 12px 10px;
    display: none;
  }
  .item-note.show { display: block; }
  .item-note input {
    width: 100%;
    border: 1.5px solid var(--gray-200);
    border-radius: 8px;
    padding: 8px 10px;
    font-size: 12px;
    font-family: inherit;
    outline: none;
    color: var(--gray-600);
  }
  .item-note input:focus { border-color: var(--amber); }

  .note-toggle {
    font-size: 11px;
    color: var(--amber);
    cursor: pointer;
    padding: 0 12px 10px;
    display: block;
    background: none;
    border: none;
    font-family: inherit;
    text-align: left;
  }

  /* Bottom actions */
  .bottom-bar {
    position: fixed;
    bottom: 0; left: 0; right: 0;
    background: white;
    border-top: 1px solid var(--gray-200);
    padding: 12px 16px;
    display: flex;
    gap: 10px;
    z-index: 100;
    box-shadow: 0 -4px 16px rgba(0,0,0,0.08);
  }
  .btn {
    flex: 1;
    padding: 13px;
    border-radius: var(--radius);
    border: none;
    font-size: 14px;
    font-weight: 700;
    font-family: inherit;
    cursor: pointer;
    transition: all 0.15s;
    letter-spacing: 0.02em;
  }
  .btn:active { transform: scale(0.97); }
  .btn-csv {
    background: var(--teal);
    color: white;
    flex: 2;
  }
  .btn-mail {
    background: var(--amber);
    color: white;
  }
  .btn-reset {
    background: var(--gray-100);
    color: var(--gray-600);
    flex: 0.8;
  }

  /* Toast */
  .toast {
    position: fixed;
    top: 80px;
    left: 50%;
    transform: translateX(-50%) translateY(-10px);
    background: var(--gray-900);
    color: white;
    padding: 10px 20px;
    border-radius: 24px;
    font-size: 13px;
    font-weight: 600;
    opacity: 0;
    transition: all 0.3s;
    pointer-events: none;
    white-space: nowrap;
    z-index: 200;
  }
  .toast.show {
    opacity: 1;
    transform: translateX(-50%) translateY(0);
  }

  /* Modal */
  .modal-overlay {
    display: none;
    position: fixed; inset: 0;
    background: rgba(0,0,0,0.5);
    z-index: 300;
    align-items: flex-end;
    justify-content: center;
  }
  .modal-overlay.show { display: flex; }
  .modal {
    background: white;
    border-radius: 20px 20px 0 0;
    padding: 24px 20px 40px;
    width: 100%;
    max-width: 480px;
    animation: slideUp 0.3s ease;
  }
  @keyframes slideUp { from { transform: translateY(40px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
  .modal h3 { font-size: 16px; font-weight: 700; margin-bottom: 8px; }
  .modal p { font-size: 13px; color: var(--gray-600); line-height: 1.6; margin-bottom: 20px; }
  .modal-btns { display: flex; gap: 10px; }
  .modal-btns .btn { flex: 1; }

  /* Stats chip */
  .stats-row {
    display: flex;
    gap: 8px;
    padding: 8px 12px 0;
    overflow-x: auto;
    scrollbar-width: none;
  }
  .stats-row::-webkit-scrollbar { display: none; }
  .stat-chip {
    flex-shrink: 0;
    background: white;
    border-radius: 8px;
    padding: 6px 10px;
    font-size: 11px;
    color: var(--gray-600);
    box-shadow: var(--shadow);
  }
  .stat-chip strong { color: var(--navy); font-size: 13px; }

  /* Empty state */
  .empty-state {
    text-align: center;
    padding: 40px 20px;
    color: var(--gray-400);
    font-size: 13px;
  }
</style>
</head>
<body>

<div class="header">
  <div class="header-top">
    <div>
      <div class="header-title">🏪 競合店価格調査票</div>
      <div class="header-subtitle">おのだサンパーク店</div>
    </div>
    <div id="totalCount" style="font-size:11px; color:rgba(255,255,255,0.7)">0 / 0 件</div>
  </div>
  <div class="progress-bar-wrap"><div class="progress-bar" id="progressBar" style="width:0%"></div></div>
  <div class="progress-label" id="progressLabel">入力中...</div>
</div>

<!-- 調査情報 -->
<div class="meta-panel">
  <div class="meta-grid">
    <div class="meta-field">
      <label>📅 調査日</label>
      <input type="date" id="surveyDate">
    </div>
    <div class="meta-field">
      <label>🏪 競合店名</label>
      <input type="text" id="storeName" placeholder="例: ○○スーパー">
    </div>
    <div class="meta-field full">
      <label>👤 調査担当者</label>
      <input type="text" id="surveyor" placeholder="担当者名を入力">
    </div>
  </div>
</div>

<!-- カテゴリータブ -->
<div class="cat-scroll" id="catTabs"></div>

<!-- 統計チップ -->
<div class="stats-row" id="statsRow"></div>

<!-- 商品リスト -->
<div class="section" id="itemList"></div>

<!-- 操作バー -->
<div class="bottom-bar">
  <button class="btn btn-reset" onclick="confirmReset()">🔄 リセット</button>
  <button class="btn btn-csv" onclick="downloadCSV()">📥 CSV保存</button>
  <button class="btn btn-mail" onclick="sendMail()">📧 メール</button>
</div>

<!-- トースト -->
<div class="toast" id="toast"></div>

<!-- リセット確認モーダル -->
<div class="modal-overlay" id="resetModal">
  <div class="modal">
    <h3>⚠️ データをリセット</h3>
    <p>入力した価格データをすべて削除します。<br>調査情報（日付・店名）は残ります。この操作は元に戻せません。</p>
    <div class="modal-btns">
      <button class="btn btn-reset" onclick="closeModal()">キャンセル</button>
      <button class="btn" style="background:var(--red);color:white;" onclick="doReset()">リセットする</button>
    </div>
  </div>
</div>

<script>
// ============================================================
// DATA: カテゴリー別商品マスタ
// ============================================================
const CATEGORIES = [
  {
    id: 'yonichihae',
    name: '洋日配',
    items: [
      { jan: '4901516004833', name: '九州乳業　みどり　1000ｍｌ' },
      { jan: '4908649110417', name: 'やまぐち県酪　酪農3.6牛乳　1000ｍｌ' },
      { jan: '4902705126558', name: '明治　おいしい牛乳　900ｍｌ' },
      { jan: '', name: 'ハローズの牛乳最安値' },
      { jan: '4902705096011', name: '明治　プロビオヨーグルトＲ－1ドリンク　112ｇ' },
      { jan: '4902705011625', name: '明治　ブルガリアヨーグルトＬＢ81プレーン　400ｇ' },
      { jan: '4908649931494', name: 'やまぐち県酪　そよ風ヨーグルト　380ｇ' },
      { jan: '4908649932132', name: 'やまぐち県酪　そよ風ヨーグルト　バニラ　360ｇ' },
      { jan: '4908011601314', name: '雪印　牧場の朝ヨーグルト　いちご　70ｇ×3' },
      { jan: '4908011601307', name: '雪印　牧場の朝ヨーグルト　生乳仕立て　70ｇ×3' },
      { jan: '45184888', name: 'グリコ　ＢＩＧプッチンプリン　160ｇ' },
      { jan: '4971666404098', name: 'グリコ　マイルドカフェオーレ　1000ｍｌ' },
      { jan: '4901516027573', name: 'みどり　成分無調整豆乳　1000ｍｌ' },
      { jan: '4902720150972', name: '森永　Mtレーニア　カフェラッテ　240ｍｌ' },
      { jan: '4902720151009', name: '森永　Mtレーニア　クリーミーラテ　240ｍｌ' },
      { jan: '4902720150989', name: '森永　Mtレーニア　エスプレッソ　240ｍｌ' },
      { jan: '4902720150996', name: '森永　Mtレーニア　ノンシュガー　240ｍｌ' },
      { jan: '4903308060621', name: '六甲バター　モッツァレラとろけるチーズ　250ｇ' },
      { jan: '4903308060546', name: '六甲バター　たっぷり18枚とろけるスライス　225ｇ' },
      { jan: '4903308060539', name: '六甲バター　たっぷり18枚スライスチーズ　225ｇ' },
      { jan: '4903308060010', name: '六甲バター　ベビーチーズ　プレーン　54ｇ' },
      { jan: '4903308060034', name: '六甲バター　カマンベール入りベビーチーズ　54ｇ' },
      { jan: '4903308060027', name: '六甲バター　アーモンド入りベビーチーズ　54ｇ' },
    ]
  },
  {
    id: 'kome',
    name: '米',
    items: [
      { jan: '4517292119458', name: '肥前糧食　さがびより　5ｋｇ' },
    ]
  },
  {
    id: 'tamago',
    name: 'たまご',
    items: [
      { jan: '4517292899015', name: '肥前糧食　たまご応援団　10玉入' },
      { jan: '4538151297025', name: 'しろたま' },
    ]
  },
  {
    id: 'frozen',
    name: '冷凍食品',
    items: [
      { jan: '4954018129122', name: 'イートアンド　羽根つき餃子　12個入り' },
      { jan: '4548779735434', name: '日清食品　スパ王喫茶店のたらこバター　360ｇ' },
      { jan: '4548779735410', name: '日清食品　スパ王喫茶店のナポリタン　360ｇ' },
      { jan: '4548779735427', name: '日清食品　スパ王喫茶店のミートソース　360ｇ' },
      { jan: '4901001397457', name: '味の素　ギョーザ　12個入' },
      { jan: '4901520172085', name: 'テーブルマーク　讃岐麺一番　肉うどん　340ｇ' },
      { jan: '4902130114779', name: 'ニチレイ　本格炒め炒飯　450ｇ' },
      { jan: '4902130114427', name: 'ニチレイ　特から　380ｇ' },
      { jan: '4573128560054', name: 'ピザレボ　極☆マルゲリータ' },
      { jan: '4901520212675', name: 'テーブルマーク　麺始讃岐うどん　250ｇ×5' },
      { jan: '4589594370295', name: 'ジョイフル　ジョイフルの塩唐揚げ　250ｇ' },
      { jan: '4589594370318', name: 'ジョイフル　ジョイフルのハンバーグてりやきソース' },
      { jan: '4589594370356', name: 'ジョイフル　ジョイフルのチーズインハンバーグデミグラス' },
      { jan: '4589594370349', name: 'ジョイフル　ジョイフルのチーズインハンバーグトマトソース' },
      { jan: '4589594370271', name: 'ジョイフル　ジョイフルのチキンステーキ　てりやきソース' },
      { jan: '4902150665138', name: 'ニッスイ　塩あじえだ豆　360ｇ' },
      { jan: '4532934002875', name: '餃子計画　食べたらやみつきになる餃子　36個' },
    ]
  },
  {
    id: 'wanicihae',
    name: '和日配',
    items: [
      { jan: '4965845000652', name: 'めん食　九州大地の茹でうどん　200ｇ' },
      { jan: '4965845002236', name: 'めん食　九州大地の茹でチャンポン　150ｇ' },
      { jan: '4965845003608', name: 'めん食　九州大地の焼きそば　150ｇ' },
      { jan: '4968245134101', name: '三浦製麺　瓦そば　140ｇ×4' },
      { jan: '4901160010174', name: 'おかめ仕立てミニ　45ｇ×3' },
      { jan: '4901160030103', name: 'おかめ仕立てひきわり　45ｇ×3' },
      { jan: '4965833337005', name: '三好食品工業　木綿豆腐　400ｇ' },
      { jan: '4965833337012', name: '三好食品工業　ソフト豆腐　400ｇ' },
      { jan: '4935033554830', name: '佐藤　もちもち絹厚揚げ　2枚入' },
      { jan: '4582375530116', name: 'やまとフーズ　佐賀職人手作りキムチ　180ｇ' },
      { jan: '4902519060451', name: 'フジミツ　仙崎ちくわ　4本' },
      { jan: '4901990044059', name: '東洋水産　3食焼きそば　150ｇ×3' },
      { jan: '4560279104077', name: '男前豆腐店　特濃ケンちゃん　90ｇ×3' },
      { jan: '4560279104688', name: '男前豆腐店　京まろとうふ　100ｇ×4' },
      { jan: '4902150373040', name: '宇部かま　魚ちく　3本束' },
      { jan: '4902150371596', name: '宇部かま　蒲さし（赤）　1本' },
      { jan: '4902150371572', name: '宇部かま　蒲さし（白）　1本' },
      { jan: '4901160020043', name: 'タカノフーズ　国産丸大豆納豆　40ｇ×3' },
      { jan: '4965833444673', name: '三好食品工業　すし揚げ　6枚' },
      { jan: '4953326010023', name: '木嶋製麺所　うどん　200ｇ' },
      { jan: '4953326020022', name: '木嶋製麺所　ちゃんぽん・焼きそば　150ｇ' },
    ]
  },
  {
    id: 'kashi',
    name: '菓子',
    items: [
      { jan: '4901330539832', name: 'カルビー　ポテトチップス九州しょうゆ　53ｇ' },
      { jan: '4901330504779', name: 'カルビー　ポテトチップスうすしお味　55ｇ' },
      { jan: '4901330513764', name: 'カルビー　ポテトチップスのりしお味　55ｇ' },
      { jan: '4901330524159', name: 'カルビー　ポテトチップス　コンソメパンチ　55ｇ' },
      { jan: '4901330578923', name: 'カルビー　じゃがりこじゃがバター　55ｇ' },
      { jan: '4901330576059', name: 'カルビー　じゃがりこ九州しょうゆ味　５２ｇ' },
      { jan: '4901330578916', name: 'カルビー　じゃがりこチーズ　５５ｇ' },
      { jan: '4903326110148', name: 'リスカ　コーンポタージュ　７５ｇ' },
      { jan: '4901330123338', name: 'カルビー　サッポロポテトバーベキュー味　７２ｇ' },
      { jan: '4901330123321', name: 'カルビー　サッポロポテトつぶつぶベジタブル　７２ｇ' },
      { jan: '4901330201678', name: 'カルビー　ベジたべるあっさりサラダ　５０ｇ' },
      { jan: '4901330106676', name: 'カルビー　かっぱえびせん　７７ｇ' },
      { jan: '4903333264230', name: 'ロッテ　チョコパイパーティーパック　９個' },
      { jan: '4903333258840', name: 'ロッテ　ガーナミルク　５０ｇ' },
      { jan: '4903333267774', name: 'ロッテ　ガーナホワイト　４５ｇ' },
      { jan: '4902201183093', name: 'ネスレ日本キットカット　１１枚' },
      { jan: '4903032243819', name: '有楽製菓　ブラックサンダーミニバー　１３９ｇ' },
      { jan: '4901620170578', name: '日清シスコ　シスコーン　マイルドチョコ　２００ｇ' },
      { jan: '4901620170257', name: '日清シスコ　シスコーン　フロスト　２２０ｇ' },
      { jan: '4901620171179', name: '日清シスコ　シスコーンサクサクリングチョコ　１５０ｇ' },
      { jan: '4901620171162', name: '日清　シスコーンサクサクハートいちご味　１３０ｇ' },
      { jan: '4901330748296', name: 'カルビー　フルグラ　７００ｇ' },
      { jan: '4901626055527', name: '三幸製菓　雪の宿サラダ　２０枚' },
      { jan: '4901626059914', name: '三幸製菓　雪の宿黒糖みるく味　２０枚' },
      { jan: '4901075010559', name: '越後製菓　ふんわり名人北海道チーズ　６６ｇ' },
      { jan: '4901075011006', name: '越後製菓　ふんわり名人きなこ餅　７５ｇ' },
      { jan: '4901313207871', name: '亀田製菓　ハッピーターン　９６ｇ' },
      { jan: '4901830164718', name: '三立お徳用源氏パイ　２４枚' },
    ]
  },
  {
    id: 'grocery',
    name: 'グロサリー',
    items: [
      { jan: '4902380188827', name: '日清オイリオ　ヘルシーオフ　９００ｇ' },
      { jan: '4902402144770', name: 'ハウス食品　うまかっちゃん　９４ＧＸ５Ｐ' },
      { jan: '4902560020824', name: 'はごろも　シーチキンマイルドＳＰ３　７０ｇ×３Ｐ' },
      { jan: '4901577042072', name: 'キユーピー　マヨネーズ　４５０ｇ' },
      { jan: '4901990324595', name: '東洋水産　ごつ盛りソース焼そば大盛　１７１ｇ' },
      { jan: '4902930040001', name: '大日本明治製糖　ばら印　上白糖　１ｋｇ' },
      { jan: '4901002133511', name: 'Ｓ＆Ｂ　ゴールデンカレー　甘口　１９８ｇ' },
      { jan: '4901002133528', name: 'Ｓ＆Ｂ　ゴールデンカレー　中辛　１９８ｇ' },
      { jan: '4901002133535', name: 'エスビー　ゴールデンカレー辛口　１９８ｇ' },
      { jan: '4901002133566', name: 'Ｓ＆Ｂ　ゴールデンハヤシライスソース　１９３ｇ' },
      { jan: '4902402844229', name: 'ハウス　完熟トマトのハヤシライスソース　１８４ｇ' },
      { jan: '4902204004098', name: 'キッコーマン　デルモンテトマトケチャップ　４６０ｇ' },
      { jan: '4901577046261', name: 'キユーピー　深煎りごまドレッシング　３８０ｍｌ' },
      { jan: '4901108013564', name: 'エバラ　黄金の味　甘口　３６０ｇ' },
      { jan: '4901108013588', name: 'エバラ　黄金の味　中辛　３６０ｇ' },
      { jan: '4901108013601', name: 'エバラ　黄金の味　辛口　３６０ｇ' },
      { jan: '4901108013632', name: 'エバラ　バリ旨焼肉のたれ　５８０ｇ' },
      { jan: '4901108001943', name: 'エバラ　すき焼のたれ　マイルド　５００ｍｌ' },
      { jan: '49698626', name: '日清　カップヌードル　７７ｇ' },
      { jan: '49698633', name: '日清　カップヌードル　シーフード　７４ｇ' },
      { jan: '49698640', name: '日清　カップヌードル　カレー　８６ｇ' },
      { jan: '4902105022122', name: '日清　焼そばＵＦＯ　１２８ｇ' },
      { jan: '4976640000013', name: '兵庫県手延素麺組合　揖保乃糸　素麺　上級品　３００Ｇ' },
      { jan: '4902105002674', name: '日清　どん兵衛きつねうどん　９５ｇ' },
      { jan: '4902105282670', name: '日清食品　日清のどん兵衛　肉うどん　８７ｇ' },
      { jan: '4902105004173', name: '日清　どん兵衛　天ぷらそば　１００ｇ' },
      { jan: '4902105002605', name: '日清　チキンラーメンどんぶり　８５ｇ' },
      { jan: '4902881048651', name: '明星食品　一平ちゃん夜店の焼そば　１３５ｇ' },
      { jan: '49685183', name: 'ミツカン　味ぽん　３６０ｍｌ' },
      { jan: '4902201424042', name: 'ネスレ　ネスカフェゴールドブレンド　８０ｇ' },
      { jan: '4901085617786', name: '伊藤園　香り薫るむぎ茶ティーバッグ　５４袋' },
      { jan: '4901085003800', name: '伊藤園　おーいお茶緑茶　600ｍｌ' },
      { jan: '4901085003800', name: '伊藤園　おーいお茶濃茶　600ｍｌ' },
      { jan: '4514603263213', name: 'アサヒ　三ツ矢サイダー　５００ｍｌ' },
      { jan: '4902102157810', name: 'コカ・コーラ　ジョージア　ブラック　５００ｍｌ' },
      { jan: '4902102157612', name: 'コカ・コーラ　ジョージア　カフェラテ　５００ｍｌ' },
      { jan: '4902102157599', name: 'コカ・コーラジョージア　深煎りプレッソ　５００ｍｌ' },
      { jan: '4902102141253', name: 'コカ・コーラ　やかんの麦茶　2Ｌ' },
      { jan: '4902102112079', name: 'コカコーラ　煌　烏龍茶　２Ｌ' },
      { jan: '4902102113625', name: 'コカコーラ　いろはす　２Ｌ' },
    ]
  },
];

// ============================================================
// STATE
// ============================================================
let currentCat = CATEGORIES[0].id;
let prices = {};   // { catId_itemIndex: { price, skip, note } }

// ============================================================
// INIT
// ============================================================
document.addEventListener('DOMContentLoaded', () => {
  // 今日の日付をデフォルト
  const today = new Date().toISOString().slice(0, 10);
  document.getElementById('surveyDate').value = today;

  // ローカルストレージから復元
  const saved = localStorage.getItem('priceData_onoda');
  if (saved) {
    try {
      const d = JSON.parse(saved);
      prices = d.prices || {};
      if (d.storeName) document.getElementById('storeName').value = d.storeName;
      if (d.surveyor) document.getElementById('surveyor').value = d.surveyor;
      if (d.date) document.getElementById('surveyDate').value = d.date;
    } catch(e) {}
  }

  renderTabs();
  renderItems(currentCat);
  updateProgress();
});

// ============================================================
// TABS
// ============================================================
function renderTabs() {
  const wrap = document.getElementById('catTabs');
  wrap.innerHTML = '';
  CATEGORIES.forEach(cat => {
    const btn = document.createElement('button');
    btn.className = 'cat-tab' + (cat.id === currentCat ? ' active' : '');
    const filled = cat.items.filter((_, i) => {
      const k = `${cat.id}_${i}`;
      return prices[k] && (prices[k].price !== '' || prices[k].skip);
    }).length;
    btn.innerHTML = cat.name + (filled > 0 ? `<span class="badge">${filled}</span>` : '');
    btn.onclick = () => switchCat(cat.id);
    wrap.appendChild(btn);
  });
}

function switchCat(catId) {
  currentCat = catId;
  renderTabs();
  renderItems(catId);
  renderStats(catId);
  document.getElementById('itemList').scrollTop = 0;
  window.scrollTo(0, 0);
}

// ============================================================
// ITEMS
// ============================================================
function renderItems(catId) {
  const cat = CATEGORIES.find(c => c.id === catId);
  const wrap = document.getElementById('itemList');
  wrap.innerHTML = '';

  cat.items.forEach((item, i) => {
    const k = `${catId}_${i}`;
    const data = prices[k] || { price: '', skip: false, note: '' };

    const card = document.createElement('div');
    card.className = 'item-card' + (data.skip ? ' skipped' : data.price !== '' ? ' filled' : '');
    card.id = `card_${k}`;

    card.innerHTML = `
      <div class="item-head">
        <span class="item-num">${i + 1}</span>
        <div class="item-name-wrap">
          <div class="item-name">${item.name}</div>
          ${item.jan ? `<div class="item-jan"><span class="item-jan-label">JAN</span>${item.jan}</div>` : ''}
        </div>
      </div>
      <div class="item-body">
        <div class="price-wrap">
          <span class="yen">¥</span>
          <input
            class="price-input${data.price !== '' ? ' has-value' : ''}"
            type="number"
            inputmode="numeric"
            pattern="[0-9]*"
            placeholder="税込価格を入力"
            value="${data.price}"
            ${data.skip ? 'disabled' : ''}
            data-key="${k}"
            onchange="setPrice('${k}', this.value)"
            oninput="setPrice('${k}', this.value)"
          >
        </div>
        <button class="skip-btn${data.skip ? ' active' : ''}" onclick="toggleSkip('${k}')" title="取扱なし/確認不可">
          ${data.skip ? '✓スキップ' : 'スキップ'}
        </button>
      </div>
      <button class="note-toggle" onclick="toggleNote('${k}')">📝 メモ追加</button>
      <div class="item-note${data.note ? ' show' : ''}" id="note_${k}">
        <input type="text" placeholder="メモ（特売・PB等）" value="${data.note || ''}"
          onchange="setNote('${k}', this.value)" oninput="setNote('${k}', this.value)">
      </div>
    `;
    wrap.appendChild(card);
  });

  renderStats(catId);
}

function toggleNote(k) {
  const el = document.getElementById('note_' + k);
  el.classList.toggle('show');
  if (el.classList.contains('show')) el.querySelector('input').focus();
}

// ============================================================
// DATA OPS
// ============================================================
function setPrice(k, val) {
  if (!prices[k]) prices[k] = { price: '', skip: false, note: '' };
  prices[k].price = val;
  updateCard(k);
  updateProgress();
  saveLocal();
}

function setNote(k, val) {
  if (!prices[k]) prices[k] = { price: '', skip: false, note: '' };
  prices[k].note = val;
  saveLocal();
}

function toggleSkip(k) {
  if (!prices[k]) prices[k] = { price: '', skip: false, note: '' };
  prices[k].skip = !prices[k].skip;
  if (prices[k].skip) prices[k].price = '';
  // Re-render current item
  const [catId, idx] = k.split('_');
  renderItems(catId);
  updateProgress();
  saveLocal();
}

function updateCard(k) {
  const data = prices[k] || {};
  const card = document.getElementById(`card_${k}`);
  if (!card) return;
  card.className = 'item-card' + (data.skip ? ' skipped' : data.price !== '' ? ' filled' : '');
  const inp = card.querySelector('.price-input');
  if (inp) inp.classList.toggle('has-value', data.price !== '');
  renderTabs();
}

// ============================================================
// PROGRESS
// ============================================================
function updateProgress() {
  let total = 0, done = 0;
  CATEGORIES.forEach(cat => {
    cat.items.forEach((_, i) => {
      total++;
      const k = `${cat.id}_${i}`;
      const d = prices[k];
      if (d && (d.price !== '' || d.skip)) done++;
    });
  });
  const pct = total > 0 ? Math.round(done / total * 100) : 0;
  document.getElementById('progressBar').style.width = pct + '%';
  document.getElementById('progressLabel').textContent = `${pct}% 完了 (${done}/${total}件)`;
  document.getElementById('totalCount').textContent = `${done} / ${total} 件`;
  renderTabs();
}

function renderStats(catId) {
  const cat = CATEGORIES.find(c => c.id === catId);
  const row = document.getElementById('statsRow');
  let total = cat.items.length, filled = 0, skipped = 0;
  const vals = [];
  cat.items.forEach((_, i) => {
    const k = `${catId}_${i}`;
    const d = prices[k];
    if (d && d.skip) skipped++;
    else if (d && d.price !== '') { filled++; vals.push(Number(d.price)); }
  });
  const remaining = total - filled - skipped;
  const avg = vals.length ? Math.round(vals.reduce((a, b) => a + b, 0) / vals.length) : null;

  row.innerHTML = `
    <div class="stat-chip">残り <strong>${remaining}</strong> 件</div>
    <div class="stat-chip">入力済 <strong>${filled}</strong> 件</div>
    <div class="stat-chip">スキップ <strong>${skipped}</strong> 件</div>
    ${avg !== null ? `<div class="stat-chip">平均 <strong>¥${avg.toLocaleString()}</strong></div>` : ''}
  `;
}

// ============================================================
// LOCAL STORAGE
// ============================================================
function saveLocal() {
  const data = {
    prices,
    storeName: document.getElementById('storeName').value,
    surveyor: document.getElementById('surveyor').value,
    date: document.getElementById('surveyDate').value,
  };
  try { localStorage.setItem('priceData_onoda', JSON.stringify(data)); } catch(e) {}
}

// ============================================================
// CSV DOWNLOAD
// ============================================================
function downloadCSV() {
  const date = document.getElementById('surveyDate').value || '';
  const store = document.getElementById('storeName').value || '';
  const surveyor = document.getElementById('surveyor').value || '';

  const rows = [
    ['調査日', '競合店名', '調査担当者', 'カテゴリー', 'JAN', '商品名', '税込価格', 'スキップ', 'メモ']
  ];

  CATEGORIES.forEach(cat => {
    cat.items.forEach((item, i) => {
      const k = `${cat.id}_${i}`;
      const d = prices[k] || { price: '', skip: false, note: '' };
      rows.push([
        date,
        store,
        surveyor,
        cat.name,
        item.jan,
        item.name,
        d.skip ? '' : d.price,
        d.skip ? '1' : '0',
        d.note || ''
      ]);
    });
  });

  const csv = rows.map(r => r.map(v => `"${String(v).replace(/"/g, '""')}"`).join(',')).join('\n');
  const bom = '\uFEFF'; // UTF-8 BOM for Excel
  const blob = new Blob([bom + csv], { type: 'text/csv;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  const fname = `価格調査_${store || 'result'}_${date || 'date'}.csv`;
  a.href = url;
  a.download = fname;
  a.click();
  URL.revokeObjectURL(url);
  showToast('📥 CSVをダウンロードしました');
}

// ============================================================
// MAIL
// ============================================================
function sendMail() {
  const date = document.getElementById('surveyDate').value || '未入力';
  const store = document.getElementById('storeName').value || '未入力';
  const surveyor = document.getElementById('surveyor').value || '未入力';

  let total = 0, filled = 0, skipped = 0;
  CATEGORIES.forEach(cat => {
    cat.items.forEach((_, i) => {
      total++;
      const k = `${cat.id}_${i}`;
      const d = prices[k];
      if (d && d.skip) skipped++;
      else if (d && d.price !== '') filled++;
    });
  });

  let body = `競合店価格調査レポート\n`;
  body += `═══════════════════════\n`;
  body += `調査日: ${date}\n`;
  body += `競合店名: ${store}\n`;
  body += `調査担当: ${surveyor}\n`;
  body += `入力状況: ${filled}件入力 / ${skipped}件スキップ / ${total - filled - skipped}件未入力\n\n`;

  CATEGORIES.forEach(cat => {
    const catItems = cat.items.filter((_, i) => {
      const d = prices[`${cat.id}_${i}`];
      return d && (d.price !== '' || d.skip);
    });
    if (catItems.length === 0) return;
    body += `【${cat.name}】\n`;
    cat.items.forEach((item, i) => {
      const k = `${cat.id}_${i}`;
      const d = prices[k];
      if (!d || (d.price === '' && !d.skip)) return;
      const priceStr = d.skip ? '取扱なし' : `¥${Number(d.price).toLocaleString()}`;
      const noteStr = d.note ? ` (${d.note})` : '';
      body += `  ${item.name}: ${priceStr}${noteStr}\n`;
    });
    body += '\n';
  });

  const subject = encodeURIComponent(`【価格調査】${store} ${date}`);
  const bodyEnc = encodeURIComponent(body);
  window.location.href = `mailto:?subject=${subject}&body=${bodyEnc}`;
  showToast('📧 メールアプリを開きます');
}

// ============================================================
// RESET
// ============================================================
function confirmReset() {
  document.getElementById('resetModal').classList.add('show');
}
function closeModal() {
  document.getElementById('resetModal').classList.remove('show');
}
function doReset() {
  prices = {};
  try { localStorage.removeItem('priceData_onoda'); } catch(e) {}
  closeModal();
  renderItems(currentCat);
  updateProgress();
  showToast('🔄 データをリセットしました');
}

// ============================================================
// TOAST
// ============================================================
function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 2800);
}

// Save on input changes to meta fields
['storeName', 'surveyor', 'surveyDate'].forEach(id => {
  document.getElementById(id).addEventListener('change', saveLocal);
});
</script>
</body>
</html>
