# Gitの勉強
- git add コマンドで、リポジトリに変更情報を追加する
	- このことをステージングと言う
	- git status コマンドでステージングの情報が確認できる
- git commit コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
	- git commit -m "${コミットコメント}" でコメント付きコミット
	- git log コマンドでコミットログが確認できる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる
	- git remote add origin git@github.com:${username}/${リポジトリ名} で、  
リモートリポジトリのorigin = GitHubの${リポジトリ名}のリポジトリを指すことにする、という設定をする
	- git push -u origin master でpush完了
