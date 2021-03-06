# EA03_Product_結合試験項目書

## EA0301-UC01-T01_商品検索（検索結果1件以上）

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 検索条件入力フォームに、商品名、商品ID、商品コードのいずれかを入力し"検索する"ボタンを押下する
1. 検索結果が表示される。併せて、詳細な検索条件入力フォームも表示される※ 検索条件入力フォームが未入力の場合は、全件表示される

## EA0301-UC01-T02_商品検索（検索結果0件）

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 検索条件入力フォームに、商品名、商品ID、商品コードのいずれかを入力し"検索する"ボタンを押下する
1. 「検索条件に該当するデータがありませんでした。」メッセージが表示される。併せて、詳細な検索条件入力フォームも表示される

## EA0301-UC01-T03_商品検索（検索エラー）

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 検索条件入力フォームに、バリデーションエラーが発生するデータを入力し"検索する"ボタンを押下
1. "検索条件に誤りがあります。"メッセージが表示される。

## EA0301-UC01-T03_規格確認のポップアップを表示

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 商品の一覧が表示
1. 規格確認ボタンをクリック → ポップアップが表示
1. 戻るボタンをクリック → ポップアップが消える

## EA0301-UC01-T04_ポップアップから規格編集画面に遷移

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 商品の一覧が表示
1. 規格確認ボタンをクリック → ポップアップが表示
1. 規格の編集ボタンをクリック → 規格確認画面に遷移

## EA0301-UC02-T01_CSVダウンロード（CSVダウンロード）

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. "CSVダウンロード"プルダウンより"CSVダウンロード"を選択する
1. CSVがダウンロードされる（ファイル名：product_yyyymmddhhmmss.csv）

## EA0301-UC02-T02_CSVダウンロード（出力項目設定）

1. 商品管理 → 商品マスター → 基本情報設定 → CSV出力項目設定
1. 商品管理＞商品マスターへ遷移
1. "CSVダウンロード"プルダウンより"出力項目設定"を選択する（EA0301-UC01-T01の場合のみ可）
1. 基本情報設定＞CSV出力項目設定へ遷移（その後のテストは、基本情報設定のテストにて実施）

## EA0310-UC01-T01_商品規格の登録（新規作成）（規格が1件以上登録済み）

1. 商品管理 → 商品マスター → 商品登録（商品規格）
1. 商品管理＞商品マスターへ遷移
1. "規格"リンクを押下する
1. 商品マスタ＞商品登録(商品規格) へ遷移
1. プルダウンより規格を選択して"商品規格の設定"ボタンを押下する
1. 選択した規格に登録されている分類行数分結果が表示される（選択した規格が複数の場合は分類を掛け合わせた行数分結果が表示される）
1. 規格・分類行分登録フォームを入力、"登録"チェックボックスにチェックを入れ"登録"ボタンを押下する
1. 登録が完了する
1. 登録完了メッセージが表示される
1. "商品規格の設定"ボタンが非表示になり、"商品規格を初期化"ボタンが表示、押下可能になる

## EA0310-UC01-T02_商品規格の登録（新規作成）（規格が0件）

1. 商品管理 → 商品マスター → 商品登録（商品規格）
1. 商品管理＞商品マスターへ遷移
1. "規格"リンクを押下する
1. 商品マスタ＞商品登録(商品規格) へ遷移
1. "商品規格の設定"ボタンを押下する
1. "リスト内の項目を選択してください。"メッセージが表示される

## EA0310-UC02-T01_商品規格の登録（更新）（規格の変更）

1. 商品管理 → 商品マスター → 商品登録（商品規格）
1. 商品管理＞商品マスターへ遷移
1. "規格"リンクを押下する
1. 商品マスタ＞商品登録(商品規格) へ遷移
1. "商品規格を初期化"ボタンを押下する
1. アラートウィンドウ表示
1. メッセージ確認後に"OK"ボタンを押下する
1. 作成した商品規格が削除される
1. 削除完了メッセージが表示される
1. "商品規格を初期化"ボタンが非表示になり、"商品規格の設定"ボタンが表示、押下可能になる

## EA0310-UC02-T02_商品規格の登録（更新）（商品規格の変更）

1. 商品管理 → 商品マスター → 商品登録（商品規格）
1. 商品マスタ＞商品マスターへ遷移
1. "規格"リンクを押下する
1. 商品マスタ＞商品登録(商品規格) へ遷移
1. 商品規格の登録フォームを入力、"更新"ボタンを押下する
1. 更新が完了される
1. 更新完了メッセージが表示される

## EA0302-UC05-T01_商品の確認

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. "確認"リンクを押下する
1. フロント画面商品詳細画面（ユースケースID：）に遷移（その後のテストは、フロント画面のテストにて実施）

## EA0302-UC05-T02_商品の複製

1. 商品管理 → 商品マスター → 商品更新
1. 商品管理＞商品マスターへ遷移
1. "複製"リンクを押下する
1. アラートウィンドウ表示
1. メッセージ確認後に"OK"ボタンを押下する
1. 新しい商品ID、内容は複製元の登録内容のまま、「非公開」状態で商品の登録が完了する
1. 商品登録画面に遷移、複製完了メッセージが表示される

## EA0302-UC05-T03_商品の削除

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. "削除"リンクを押下する
1. アラートウィンドウ表示
1. メッセージ確認後に"OK"ボタンを押下する
1. 削除が完了する
1. 削除完了メッセージが表示される。検索結果は保持される。

## EA0302-UC05-T04_商品の一括削除(正常)

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 受注データが紐付いていない商品を複数選択する
1. "完全に削除"ボタンをクリックする
1. 確認ダイアログが表示される
1. "完全に削除"ボタンをクリックする
1. 処理が完了する
1. "完了"ボタンをクリックする
1. 検索結果一覧が更新される
1. 選択した商品は削除されて一覧に表示されない

## EA0302-UC05-T04_商品の一括削除(削除エラー)

1. 商品管理 → 商品マスター
1. 商品管理＞商品マスターへ遷移
1. 受注データが紐付いていない商品を複数選択する
1. 受注データが紐付いている商品を複数選択する
1. "完全に削除"ボタンをクリックする
1. 確認ダイアログが表示される
1. "完全に削除"ボタンをクリックする
1. 処理が完了する
1. 受注データが紐付いている商品を削除できなかったというエラーメッセージが表示される
1. "完了"ボタンをクリックする
1. 検索結果一覧が更新される
1. 選択した商品のうち受注データが紐付いていない商品は削除されて一覧に表示されない
1. 選択した商品のうち受注データが紐付いている商品は削除されずに一覧に表示される

## EA0302-UC01-T01_商品登録（新規作成）（非公開で登録）

1. 商品管理 → 商品登録
1. 商品管理＞商品登録へ遷移
1. 商品登録フォームを入力、「非公開」を選択し、"商品を登録"ボタンを押下する
1. 登録が完了する
1. 商品登録画面に遷移、登録完了メッセージが表示される
1. "規格設定"、"確認"、"複製"、"削除"ボタンが押下可能になる

## EA0302-UC01-T02_商品登録（新規作成）（公開で登録）

1. 商品管理 → 商品登録
1. 商品管理＞商品登録へ遷移
1. 商品登録フォームを入力、「公開」を選択し、"商品を登録"ボタンを押下する
1. 登録が完了
1. 商品登録画面に遷移、登録完了メッセージが表示される
1. "規格設定"、"確認"、"複製"、"削除"ボタンが押下可能になる
1. フロント画面に表示される（その後のテストは、フロント画面のテストにて実施）

## EA0302-UC01-T03_商品編集（更新）（商品規格が未登録）

1. 商品管理 → 商品マスター → 商品管理 → 商品登録
1. 商品管理＞商品マスターへ遷移
1. 商品画像、商品名のリンクを押下する
1. 商品管理＞商品登録へ遷移
1. 商品登録（新規作成）と同じ商品登録フォームが表示される。
1. 入力し"商品を登録"ボタンを押下す
1. 更新が完了する
1. 登録完了メッセージが表示される

## EA0302-UC01-T04_商品登録（更新）（商品規格が登録済）

1. 商品管理 → 商品マスター → 商品管理 → 商品登録
1. 商品管理＞商品マスターへ遷移
1. 商品画像、商品名のリンクを押下する
1. 商品管理＞商品登録へ遷移
1. 商品規格で規格
1. 商品登録フォームが表示されるただし、分類ごとに個別に登録した「商品種別」「販売価格」「通常価格」「在庫数」「商品コード」「販売制限数」「お届け可能日」「商品送料」は表示されない。
1. それ以外の商品登録フォームを入力し、"商品を登録"ボタンを押下する
1. 登録が完了
1. 登録完了メッセージが表示される

## EA0302-UC01-T05_商品登録（登録）（タグを商品に追加する）
1. 製品管理→製品登録
1. リストタグをクリックして開きます
1. リスト内の3つのタグをクリックします
1. 他の製品登録フォームを入力し、「製品登録」ボタンを押します
1. 登録完了
1. 登録完了メッセージが表示されます
1. 選択した3つのタグを確認する

## EA0303-UC01-T01_規格登録（規格が1件以上登録済）

1. 商品管理 → 規格登録
1. 商品管理＞規格登録へ遷移
1. 登録入力フォームに、規格名を入力し"規格作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0303-UC01-T02_規格登録（規格が未登録）

1. 商品管理 → 規格登録
1. 商品管理＞規格登録へ遷移
1. "データはありません"メッセージが表示される
1. 登録入力フォームに、規格名を入力し"規格作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0303-UC02-T01_規格編集

1. 商品管理 → 規格登録
1. 商品管理＞規格登録へ遷移
1. "編集"リンクを押下する
1. "編集"リンクが非表示になり、"編集中"テキストが表示される
1. 規格名登録入力フォームに、編集中の規格名が表示される
1. "規格作成"ボタンを押下する
1. 更新が完了する
1. 保存完了メッセージが表示される
1. "編集中"テキストが非表示になり、"編集"リンクが表示、押下可能になる

## EA0303-UC03-T01_規格削除（分類が未登録の場合のみ可）

1. 商品管理 → 規格登録
1. 商品管理＞規格登録へ遷移
1. "削除"リンクを押下する
1. 削除が完了する
1. 削除完了メッセージが表示される

## EA0308-UC01-T01_規格表示順の変更（マウスで変更）

1. 商品管理 → 規格登録
1. 商品管理＞規格登録へ遷移
1. 変更する規格名マウスで選択、選択したまま上下に移動、選択を解除する
1. 変更が完了する

## EA0304-UC01-T01_分類登録（分類が1件以上登録済）

1. 商品管理 → 規格登録 → 分類登録
1. 商品管理＞規格登録へ遷移
1. "分類登録"リンクを押下する
1. 商品管理＞規格登録＞分類登録へ遷移※ 分類が1件以上登録されている場合は、規格名の後ろに登録件数が表示される
1. 登録入力フォームに、分類名を入力し"分類作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0304-UC01-T02_分類登録（分類が未登録）

1. 商品管理 → 規格登録 → 分類登録
1. 商品管理＞規格登録へ遷移
1. "分類登録"リンクを押下する
1. 商品管理＞規格登録＞分類登録へ遷移（の場合のみ可）※ 分類が未登録の場合は、規格名の後ろに 0 が表示される
1. "データはありません"メッセージが表示される
1. 登録入力フォームに、規格名を入力し"規格作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0304-UC02-T01_分類編集

1. 商品管理 → 規格登録 → 分類登録
1. 商品管理＞規格登録へ遷移
1. "分類登録"リンクを押下する
1. 商品管理＞規格登録＞分類登録へ遷移（の場合のみ可）※ 分類が1件以上登録されている場合は、規格名の後ろに登録件数が表示される
1. "編集"リンクを押下する
1. "編集"リンクが非表示になり、"編集中"テキストが表示される
1. 分類名登録入力フォームに、編集中の分類名が表示される
1. "分類作成"ボタンを押下する
1. 更新が完了する
1. 保存完了メッセージが表示される
1. "編集中"テキストが非表示になり、"編集"リンクが表示、押下可能になる

## EA0304-UC03-T01_分類削除

1. 商品管理 → 規格登録 → 分類登録
1. 商品管理＞規格登録へ遷移
1. "分類登録"リンクを押下する
1. 商品管理＞規格登録＞分類登録へ遷移（の場合のみ可）※ 分類が1件以上登録されている場合は、規格名の後ろに登録件数が表示される
1. "削除"リンクを押下する
1. アラートウィンド表示
1. 確認メッセージ後に"OK"ボタンを押下する
1. 削除が完了する
1. 削除完了メッセージが表示される

## EA0311-UC01-T01_分類表示順の変更（マウスで変更）

1. 商品管理 → 規格登録 → 分類登録
1. 商品管理＞規格登録へ遷移
1. "分類登録"リンクを押下する
1. 商品管理＞規格登録＞分類登録へ遷移（の場合のみ可）※ 分類が1件以上登録されている場合は、規格名の後ろに登録件数が表示される
1. 変更する分類名マウスで選択、選択したまま上下に移動、選択を解除する
1. 変更が完了する

## EA0305-UC01-T01_カテゴリ登録（カテゴリが1件以上登録済）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. 登録入力フォームに、カテゴリ名を入力し"カテゴリ作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0305-UC01-T02_カテゴリ登録（カテゴリが未登録）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. "データはありません"メッセージが表示される
1. 登録入力フォームにカテゴリ名を入力し"カテゴリ作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0305-UC02-T01_カテゴリ編集

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. "編集"リンクを押下する
1. "編集"リンクが非表示になり、"編集中"テキストが表示される
1. カテゴリ名登録入力フォームに、編集中のカテゴリ名が表示される
1. "カテゴリ作成"ボタンを押下する
1. 更新が完了する
1. 保存完了メッセージが表示される
1. "編集中"テキストが非表示になり、"編集"リンクが表示、押下可能になる

## EA0305-UC04-T01_カテゴリ削除（商品に選択されていない場合のみ可能）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. "削除"リンクを押下する
1. 削除が完了する
1. 削除完了メッセージが表示される

## EA0309-UC01-T01_カテゴリ表示順の変更（マウスで変更）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. 変更するカテゴリ名マウスで選択、選択したまま上下に移動、選択を解除する
1. 変更が完了する

## EA0305-UC04-T01_CSVダウンロード（CSVダウンロード）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. "CSVダウンロード"プルダウンより"CSVダウンロード"を選択する
1. CSVがダウンロードされる（ファイル名：category_yyyymmddhhmmss.csv）

## EA0305-UC04-T02_CSVダウンロード（出力項目設定）

1. 商品管理 → カテゴリ登録 → 基本情報設定 → CSV出力項目設定
1. 商品管理＞カテゴリ登録へ遷移
1. "CSVダウンロード"プルダウンより"出力項目設定"を選択する
1. 基本情報設定＞CSV出力項目設定へ遷移（その後のテストは、基本情報設定のテストにて実施

## EA0305-UC01-T03_カテゴリ登録（2階層以下）（2階層以下が1件以上登録済/4階層まで登録が可能）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. カテゴリ名を押下する
1. 商品管理＞カタログ登録＞カタログ登録(2階層以降)へ遷移（の場合のみ可）※ 2階層以降のカタログが1件以上登録されている場合は、右サイドメニューのカテゴリ名後ろに登録件数が表示される
1. 登録入力フォームに、カタログ名を入力し"カタログ作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0305-UC01-T04_カテゴリ登録（2階層以下）（2階層以下が未登録/4階層まで登録が可能）

1. 商品管理 → カテゴリ登録
1. 商品管理＞カテゴリ登録へ遷移
1. カタログ名を押下する
1. 商品管理＞カタログ登録＞カタログ登録(2階層以降)へ遷移（の場合のみ可）※ 2階層以降のカタログが1件以上登録されている場合は、右サイドメニューのカテゴリ名後ろに 0 が表示される
1. "データはありません"メッセージが表示される
1. 登録入力フォームに、カタログ名を入力し"カタログ作成"ボタンを押下する
1. 登録が完了する
1. 保存完了メッセージが表示される

## EA0306-UC01-T01_商品CSV登録

1. 商品管理 → 商品CSV登録
1. 商品管理＞商品CSV登録へ遷移
1. "ファイルを選択"ボタンを押下する
1. 拡張子が.csv、下部に登録されているフォーマットと項目数、必須/任意などが合致しているファイルを選択する
1. "CSVファイルのアップロード"ボタンを押下する
1. アップロード完了メッセージが表示される※ ファイル未選択、アップロード失敗時にはエラーメッセージが表示される

## EA0306-UC01-T02_雛形ファイルのダウンロード

1. 商品管理 → 商品CSV登録
1. 商品管理＞商品CSV登録へ遷移
1. "雛形ファイルダウンロード"ボタンを押下する
1. CSVがダウンロードされる（ファイル名：product.csv）※ ファイルの内容は、商品登録CSVファイルフォーマットに表示されている項目名が出力される

## EA0307-UC01-T01_カテゴリCSV登録

1. 商品管理 → カテゴリCSV登録
1. 商品管理＞カテゴリCSV登録へ遷移
1. "ファイルを選択"ボタンを押下する
1. 拡張子が.csv、下部に登録されているフォーマットと項目数、必須/任意などが合致しているファイルを選択する
1. "CSVファイルのアップロード"ボタンを押下する
1. アップロード完了メッセージが表示される※ ファイル未選択、アップロード失敗時にはエラーメッセージが表示される

## EA0307-UC01-T02_雛形ファイルのダウンロード

1. 商品管理 → カテゴリCSV登録
1. 商品管理＞カテゴリCSV登録へ遷移
1. "雛形ファイルダウンロード"ボタンを押下する
