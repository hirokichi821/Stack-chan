# AI ｽﾀｯｸﾁｬﾝ 複数wifiから接続できるAPを探す版

ロボ8080さんのAIｽﾀｯｸﾁｬﾝをベースとして複数のwifiアクセスポイント設定から接続できるものを探す機能を追加しました。

SDカードの直下に下記のフォーマットでwifi.jsonを作成します。

{
  "timeout": 10,
  "accesspoint":
  [
    {
      "ssid": "AP001",
      "pasword": "11111"
    },
    {
      "ssid": "AP002",
      "pasword": "222222"
    },
    {
      "ssid": "AP003",
      "pasword": "333333"
    }
  ]
}
