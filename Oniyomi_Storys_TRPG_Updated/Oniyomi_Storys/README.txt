Oniyomi Storys - Webサイト一式
================================

■ ファイル構成
index.html              トップページ
assets/style.css        全ページ共通デザイン
assets/script.js        スマートフォン用メニュー、コピーライト年の更新
works/novels.html       複数の小説をまとめた一覧ページ
works/novel-01.html     「ロスト・フラグメント」詳細ページ
works/novel-02.html     「結ぼれ心と恋結び」詳細ページ
works/novel-03.html     「風光絶佳は君と笑う」詳細ページ
works/trpg.html         クトゥルフ神話TRPG第6版の作品一覧ページ
works/trpg-01.html      Project『Trilogy』詳細ページ
works/trpg-02.html      Trash and Error 詳細ページ
works/trpg-03.html      浮世の星を見残して 詳細ページ
works/trpg-04.html      命のイス Re:Game Set 詳細ページ
works/trpg-05.html      クリスマスローズを君に 詳細ページ
works/trpg-06.html      HAPPY END DYSTOPIA 詳細ページ
works/world.html        世界観・設定資料ページ

■ PCで確認する
index.html をブラウザで開いてください。トップページから小説一覧へ進み、各小説の詳細ページに移動できます。

■ 公開前に変更する箇所
- 3作品の紹介文・あらすじ・作品情報を実際の内容に合わせて編集
- 小説が4作品以上になったら、novels.html の作品カードを複製し、novel-04.html などの詳細ページを作成
- 小説の紹介文・あらすじ・作品情報を実際の内容に合わせて編集
- TRPG作品は作品一覧・個別ページを登録済み。新作は下記の手順で追加
- 仮の日付や制作状況を実際の情報に変更
- 必要に応じて利用規約、プライバシーポリシー、問い合わせ先を追加

■ 公開方法
HTML/CSS/JavaScriptだけで動く静的サイトです。Netlify、GitHub Pages、Cloudflare Pagesなどの静的ホスティングサービスにアップロードして公開できます。サービスの現在の仕様や無料枠は公開時に公式案内をご確認ください。

■ 注意
作品名として「ロスト・フラグメント」「結ぼれ心と恋結び」「風光絶佳は君と笑う」を登録済みです。紹介文やあらすじは未入力のため、実際の内容に合わせて編集してください。
Google Fontsの読み込みにはインターネット接続が必要です。読み込めない場合も代替フォントで表示します。


■ TRPG作品の追加方法
- works/trpg.html の <div class="work-grid"> 内にある <article class="work-card"> を複製し、作品名・番号・詳細ページへのリンクを変更します。
- 既存の works/trpg-06.html などを複製して trpg-07.html にし、作品名、BOOTH URL、必要な作品情報を編集します。
- すべての作品はクトゥルフ神話TRPG第6版として登録されています。プレイ人数・時間・推奨技能・あらすじなどは、確かな情報を確認してから掲載してください。
- 各作品の詳細ページには、提供されたBOOTH URLを設定済みです。
