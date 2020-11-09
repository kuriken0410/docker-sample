<h1 align="center">Todoリストマネージャーアプリ</h1>

## :globe_with_meridians: Todoリストマネージャーアプリとは
- Dockerを使うための試用アプリケーションです。
- 実施したいことを登録することで、登録したタスクをリスト管理できます。

![キャプチャ動画](https://i.gyazo.com/16869abb8973e20db746da77cf1268e4.gif)

## :globe_with_meridians: 機能一覧
- 実施したいタスクの登録機能。
- 登録したタスクの削除機能。

## :globe_with_meridians: 使用した技術、言語、ツールなど
<a><img src="https://user-images.githubusercontent.com/39142850/71774533-1ddf1780-2fb4-11ea-8560-753bed352838.png" width="70px;" /></a> <!-- rubyのロゴ -->
<a><img src="https://user-images.githubusercontent.com/39142850/71774548-731b2900-2fb4-11ea-99ba-565546c5acb4.png" height="60px;" /></a> <!-- RubyOnRailsのロゴ -->
<a><img src="https://user-images.githubusercontent.com/39142850/71774768-d064a980-2fb7-11ea-88ad-4562c59470ae.png" height="65px;" /></a> <!-- jQueryのロゴ -->

- 言語
    - サーバーサイド: Ruby
    - フロント: SASS, HTML (HAML), JavaScript (jQuery)
- アプリケーションフレームワーク: Ruby on Rails
- データベース: PostgreSQL
- ソースコード管理: Github
- コードレビューツール: Sider　Rubocop
- デプロイ: heroku 
    - https://fierce-mountain-70409.herokuapp.com

## :globe_with_meridians: インストール方法
1.このリポジトリを複製<br>
`$ git clone https://github.com/kuriken0410/todo-app`

2.インストールしたリポジトリに移動<br>
`$ cd todo-app`

3.gemをアプリケーションに適用<br>
`$ bundle install`<br>

4.DBの作成&反映<br>
`$ rails db:create`<br>
`$ rails db:migrate`<br>

5.アプリケーションの起動<br>
`$ rails s`<br>
:point_right:`http://localhost:3000`

## :globe_with_meridians: データベース設計
### tasksテーブル
|Column|Type|Options|
|------|----|-------|
|title|string||
