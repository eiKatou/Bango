# Bango
晩御飯のレシピを検索するためのシステム

http://eikatou.bango.s3-website-ap-northeast-1.amazonaws.com/

# 何ができる？
- レシピを見ることができる（主に画像データ）
- レシピを材料から検索することができる

# 構成
AWSのS3上にHTMLを配置し、そこからAjaxでデータを取得する。データは、レシピの全データが入ったJSONである。JSONもAWSのS3上に置いておく。HTMLはVue.jsを利用する。
