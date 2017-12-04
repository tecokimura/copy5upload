# copy5upload
Go言語で書くデータアップロード補助ツール

実行すると設定ファイルを読み込む
./kimura/config.cnf
 > ルートディレクトリ
 > 出力先
./kimura/list.txt


Config {
    $list.txt or $list-svn.txt $list-git.txt
    $root_dir
    $output_dir
}


copy5upload

設定ファイルを読み込む
ルートディレクトリの確認
アウトプットディレクトリの確認
リストファイルの確認
（リビジョン、作者、日時、メッセージ）って行頭に全部あれば多分git
それ以外はSVNモード



異なるディレクトリをやりたい場合は考える


とりあえずはリストファイルにつき単一ディレクトリで考える

