# エンジニアの本棚

![エンジニアの本棚](https://github.com/user-attachments/assets/c6ade347-9724-4237-a11d-53feddba6077)


エンジニアのためのバーチャル本棚による書籍管理アプリ 

表紙で本棚を管理し、進捗・メモ・検索・並び替えもできる  
（デモURL・スクリーンショット・技術構成・機能一覧・あり）

---

## サービス概要
<img width="266" height="53" alt="image" src="https://github.com/user-attachments/assets/69275507-f1c2-4b84-9b9e-09573b7f838d" />

- **エンジニアの本棚**は、エンジニアが読んだ本・読みたい本を「表紙画像」で直感的に管理できるバーチャル本棚アプリです。
- 購入した本などを登録していくことで、お気に入りの本がたくさん並ぶ、世界に一つだけの本棚を作ることができます。
- 書籍検索・所有する書籍をバーチャルな自分の本棚へ登録・ドラッグ＆ドロップ並び替え・進捗管理・メモなど、実用的な機能を多数搭載。
- クラウドサーバーデプロイ済み。
- エンジニアでなくても利用可。

---

## デモ


<img width="1792" height="1009" alt="image" src="https://github.com/user-attachments/assets/64375357-87e1-4ff5-8b26-07a78ed815fe" />

<img width="1774" height="1007" alt="image" src="https://github.com/user-attachments/assets/6bcc0061-5e0f-4f82-8f2a-fb5f2f60aecd" />


<img width="1779" height="1008" alt="image" src="https://github.com/user-attachments/assets/7e324127-6ea2-446f-a22b-6b0a9752c948" />



#### [デプロイ先URL]([https://your-app-url.fly.dev](https://engineers-bookshelf.fly.dev/)) : https://engineers-bookshelf.fly.dev/
※デモ用アカウント: test@example.com / password

---

## 使用技術

<img width="514" height="246" alt="image" src="https://github.com/user-attachments/assets/b3baa01d-84fa-48e3-aecc-1bbf63372ace" />

- **フロントエンド**: React, TypeScript, Tailwind CSS, Inertia.js
- **バックエンド**: Laravel 12.x, PHP 8.4
- **DB**: PostgreSQL
- **API連携**: 楽天ブックスAPI
- **認証**: Laravel Fortify (2要素認証対応)
- **インフラ**: Docker, Fly.io

  
#### Version

- Node.js: v22.0.0
- npm: 10.5.1
- PHP: 8.4.16
- Composer: 2.9.2
- Laravel: 12.44.0
- Docker: 23.0.5
- Docker Compose: v2.17.3


---

## テーブル設計


<img width="1116" height="316" alt="image" src="https://github.com/user-attachments/assets/ade09ecc-2ff6-4e6a-8cbb-7adcacdd8ce7" />


---

## 主な機能一覧

- ユーザー登録・ログイン・2要素認証
- **バーチャル本棚UI**  
  - 表紙画像で本棚を可視化
  - レスポンシブ対応
  - 木目調デザイン
- **本棚の並び替え**  
  - ドラッグ＆ドロップで自由に順序変更
- **書籍検索・登録**  
  - 楽天ブックスAPIでISBN/キーワード検索→ワンクリック登録
- **進捗管理**  
  - スライダーで0～100%を直感的に編集・保存
- **メモ管理**  
  - 書籍ごとに学びや気づきを記録・編集
- **画像出力**  
  - 本棚の状態を画像としてプレビュー＆ダウンロード
- **書庫（アーカイブ）機能**  
  - 本棚から一時的に非表示にできる（データ保持）
- **エラー通知・バリデーション**

---

## 画面イメージ

### バーチャル本棚


自分の本棚（ドラッグで並び替え）
<img width="1239" height="754" alt="image" src="https://github.com/user-attachments/assets/aef0bb7a-da79-403d-9e76-d07ad84ac481" />



### 書籍詳細・進捗・メモ


進捗・メモを表示するボタンを有効化

<img width="356" height="79" alt="image" src="https://github.com/user-attachments/assets/a118872a-b132-45b5-b4e5-8ba3e4fa3b66" />

詳細確認ボタンを表示
<img width="1115" height="309" alt="image" src="https://github.com/user-attachments/assets/ca222bd1-0427-4476-bbc3-45dcfbc3a8dd" />

進捗・メモへのリンクボタン

<img width="219" height="78" alt="image" src="https://github.com/user-attachments/assets/f9866a1b-3129-49df-aec0-ceb6f7b87d15" />


進捗・メモを見る

<img width="1198" height="707" alt="image" src="https://github.com/user-attachments/assets/40e51bd5-0c84-4802-b425-15fcd9955af0" />


編集する
<img width="1094" height="688" alt="image" src="https://github.com/user-attachments/assets/b4f77ddc-f50e-43c0-8815-b0b751b08601" />

保存完了
<img width="1048" height="513" alt="image" src="https://github.com/user-attachments/assets/647b321b-a109-4b02-88db-c03fa576f6e0" />




### 書籍検索・API連携

書籍検索
<img width="1778" height="1007" alt="image" src="https://github.com/user-attachments/assets/0e6fe937-f725-4637-a73a-c9363cf6ea61" />

登録済み書籍一覧
<img width="3554" height="2898" alt="books-list" src="https://github.com/user-attachments/assets/4b903e1f-1607-4d0d-9e95-ebde3b062bf3" />



---



