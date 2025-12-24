# Old Reddit Plus

OldReddit専用Tampermonkey用ユーザースクリプト
画面上部のサブレディットリンクを左部フロートサイドバーに移行させます
-------
A Tampermonkey userscript for Old Reddit that moves the subreddit list to a left sidebar

## Screenshot / 動作サンプル

![sample](sample.jpg)

## Features / 機能

- サブレディット一覧を左サイドバーに移動 / Moves subreddit list to left sidebar
- Old Redditのインターフェースを維持 / Maintains Old Reddit interface
- Tampermonkeyで簡単にインストール可能 / Easy installation with Tampermonkey
-------
- Moves subreddit list to left sidebar
- Maintains Old Reddit interface
- Easy installation with Tampermonkey

## 使用権限やAPIなど

- 閲覧しているredditへのCSS注入権限, ブラウザのlocalstorageへの設定内容の保存
- Reddit-API不使用
- スクリプトによる個人情報の取得の取得およびネットワークへのアクセスは一切ありません
-------
- CSS injection permission for Reddit pages, saves settings to browser's localStorage
- Does not use Reddit API
- No personal information collection or network access by this script

## Installation / インストール方法

1. [Tampermonkey](https://www.tampermonkey.net/)をブラウザにインストール
2. [Greasyfork](https://greasyfork.org/ja/scripts/559896-oldredditplus)からインストール、または `src/oldredditplus.js` をTampermonkeyに追加
3. Old Redditにアクセス
**注意:** www.reddit.comの旧UI設定でも利用可能(テストは主にこちらで行っています)
-------
1. Install [Tampermonkey](https://www.tampermonkey.net/) on your browser  
2. Install this script from [Greasyfork](https://greasyfork.org/ja/scripts/559896-oldredditplus) or add `src/oldredditplus.js` to Tampermonkey  
3. Access Old Reddit  
**Note:** Also works with www.reddit.com's old UI setting (primarily tested on this)  

## Usage / 使い方

インストール後、Old Reddit (old.reddit.comまたはwww.reddit.comの旧UI表示設定) にアクセスすると自動的に有効化されます
--------
The script automatically activates when you access Old Reddit (old.reddit.com or www.reddit.com with old UI setting)  

## Requirements / 動作環境

- インターネットブラウザ (テストしたのはFirefox, Brave)
- ユーザースクリプトマネージャー(テストしたのはTampermonkey)
- Old Reddit UI (old.reddit.com or www.reddit.com with old UI setting)  
  旧UIのReddit (old.reddit.comまたは旧UI設定のwww.reddit.com)

## License

MIT

## Author

Merlinsencho