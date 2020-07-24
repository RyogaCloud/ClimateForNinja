# ClimateForNinja
C4Cで作成したコードを格納するリポジトリ

### Server_NodeRED.json
- クライアントからデータを受信し、データベースに格納
- Http/Getリクエストで外気と室内の気温をJSON形式で返す

### Front_NodeRED.json
- ログイン処理や新規登録処理
- ServerからHttp/GetリクエストでJSON形式のデータを受信し、グラフとJSONで表示