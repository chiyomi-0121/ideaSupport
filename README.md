# GitHub_URL
    'https://github.com/chiyomi-0121/ideaSupport.git'

# フォルダの構成
    'css/style.css'...CSS記述用
    'private/database.css'...データベース接続用
    'index.php'...トップ画面
    'preAssociation.php'...連想スタート画面
    'association.php'...連想画面
    'endAssociation.php'...連想終了画面
    'next.php'...画面遷移確認画面
    'preGroup.php' ...グループワークスタート画面
    'group.php'...グループワーク画面
    'endGroup.php'...グループワーク終了画面
    'result.php'...結果画面
    'sampledata.csv'...連想単語サンプルデータ

# 連想用データ詳細
    未記入

# データベースの構成
    allIdeas    
        id...アイデアID　primary INT AUTO_INCREMENT
        createTime...アイデア作成時間 TIME 
        content...アイデア内容 VARCHAR(255)
        createUser...作成ユーザ番号 INT