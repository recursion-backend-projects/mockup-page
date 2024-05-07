# モックアップページ

## 概要

ECサイトのデザインです。

開発時は、各ページのデザインを参考に進めてください。

各ページの関係性は、[画面遷移図](https://www.figma.com/file/4hgHQpmcFOFqZtoYaTyfX1/E-Commerce-Webapp-with-Stripe-Sync?type=design&node-id=0%3A1&mode=design&t=cnquVWjGlfXtCY0Q-1)を確認してください。

画面遷移図のアクセスには、作成者の承認が必要です。

### 注意事項

モックアップページの作成には、[Tailwind CSS](https://tailwindcss.com/)と[flowbite](https://flowbite.com/)を使用しています。

デザインの作成およびメンバー間での認識合わせが目的のため、CDNを使用しています。

実際の開発時には、CDNを使用しないでください。

具体的には、以下のようなコードを利用しないでください。

```
    <!-- 以下は、開発用コード -->
    <!-- メインのリポジトリでは、使用しないでください。 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/2.3.0/flowbite.min.css"
      rel="stylesheet"
    />
```

```
    <!-- 以下は、開発用コード -->
    <!-- メインのリポジトリでは、使用しないでください。 -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/flowbite/2.3.0/flowbite.min.js"></script>
```

## ログインページ

### 対象ファイル

[login.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/auth/login.html)

### イメージ

![login-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/f24decd9-2204-466a-99d8-5e575872bd53)

## メール再送信ページ

### 対象ファイル

[mail-resend.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/auth/mail-resend.html)

### イメージ

![mail-resend-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/34662733-7f0f-471f-a016-e2a3b489d556)

## メール送信通知ページ

### 対象ファイル

[mail-send-message.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/auth/mail-send-message.html)

### イメージ

![mail-send-message-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/f875d45d-70b4-402b-8f88-d7e21dc4cdbc)

## パスワード再発行ページ

### 対象ファイル

[password-reissue.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/auth/password-reissue.html)

### イメージ

![password-reissue-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/58d70a87-79ef-4a75-959a-020221192f08)

## パスワード再設定ページ

### 対象ファイル

[password-reset.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/auth/password-reset.html)

### イメージ

![password-reset-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/8493849f-e739-4f6a-b39c-de4765301061)

## アカウント作成ページ

### 対象ファイル

[register.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/auth/register.html)

### イメージ

![register-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/7e6bec0e-4553-438a-8181-3309206d319a)

## アカウント情報編集ページ

### 対象ファイル

[account-info-edit.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/account-info-edit.html)

### イメージ

![account-info-edit-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/19eb6cba-8ba9-400e-bd76-9dc5c53c860a)

## アカウント情報ページ

### 対象ファイル

[account-info.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/account-info.html)

### イメージ

![account-info-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/cb2753b7-c9fb-48b9-ad28-c594d3ed29bf)

## カートリストページ

### 対象ファイル

[cart-list.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/cart-list.html)

### イメージ

![cart-list-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/629cedbc-57ff-40f1-b2d9-6c9ec6f9480b)

## チャットページ

### 対象ファイル

[chat.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/chat.html)

### イメージ

![chat-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/380c1653-7267-4d9b-8678-46ac8d82a6a0)

## お問い合わせページ

### 対象ファイル

[contact-form.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/contact-form.html)

### イメージ

![contact-form-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/09540a05-876f-4455-9817-4e3d0837dbde)

## お気に入りページ

### 対象ファイル

[favorite-list.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/favorite-list.html)

### イメージ

![favorite-list-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/fa06a3f6-49e0-4e27-b3c7-7f7b3fdfe115)

## ホームページ

### 対象ファイル

[home.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/home.html)

### イメージ

![home-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/005589cb-8bf9-4113-802f-047b2c4cc43c)

## 商品詳細ページ

### 対象ファイル

[product-detail.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/product-detail.html)

### イメージ

![product-detail-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/d3af97e1-1f46-47ff-9dac-fa3264832e1d)

## 商品リストページ

### 対象ファイル

[product-list.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/product-list.html)

### イメージ

![product-list-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/ea254673-d06e-42cb-ae33-f980ea52e634)

## 購入履歴ページ

### 対象ファイル

[purchase-history.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/purchase-history.html)

### イメージ

![purchase-history-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/afbfa152-a61a-4cc4-9368-f027b5a7ef65)

## レビュー記入ページ

### 対象ファイル

[review-entry.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/review-entry.html)

### イメージ

![review-entry-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/f6872c07-9016-49e9-a8d3-5b7fe6a61594)

## レビューリストページ

### 対象ファイル

[review-list.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/review-list.html)

### イメージ

![review-list-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/69ebff3b-8a31-4113-8ca9-3eeb39e88fc2)

## ウィッシュリストページ

### 対象ファイル

[wish-list.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/component/wish-list.html)

### イメージ

![wish-list-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/ed7c0744-62e1-490f-910e-0e0270a6ed9c)

## 商品情報の編集ページ

### 対象ファイル

[product-edit.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/management/product-edit.html)

### イメージ

![product-edit-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/fafc6b34-4988-4a01-ac0b-d85ca653279e)

## 商品管理ページ

### 対象ファイル

[product-management.html](https://github.com/recursion-backend-projects/mockup-page/blob/main/src/views/management/product-management.html)

### イメージ

![product-management-html](https://github.com/recursion-backend-projects/mockup-page/assets/119317071/2f41a9d4-aafe-4945-9319-8ad904ec1aa6)

