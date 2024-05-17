# yuminnk-nextjs-template

このリポジトリは `npx create-next-app` を使用して作成されたNext.jsボイラープレートプロジェクトで、TypeScript開発に特化しています。GTS（Google TypeScript Style）、commitlint、husky、およびJestなどの基本的な開発ツールが含まれています。

## 目次

- [はじめに](#はじめに)
- [スクリプト](#スクリプト)
- [使用技術](#使用技術)
- [プロジェクト構造](#プロジェクト構造)
- [コントリビュート](#コントリビュート)
- [ライセンス](#ライセンス)

## はじめに

このプロジェクトを開始するには、以下の手順に従ってください：

1. **リポジトリをクローン**:
    ```sh
    git clone https://github.com/yourusername/yuminnk-nextjs-template.git
    cd yuminnk-nextjs-template
    ```

2. **依存関係をインストール**:
    ```sh
    yarn install
    ```

3. **開発サーバーを実行**:
    ```sh
    yarn dev
    ```
    アプリケーションは `http://localhost:3000` で利用可能になります。

## スクリプト

プロジェクトで実行できるスクリプトは次のとおりです：

- `yarn dev`: 開発サーバーを実行します。
- `yarn build`: 本番用アプリケーションをビルドします。
- `yarn start`: 本番サーバーを起動します。
- `yarn lint`: GTSを使用してコードをリントします。
- `yarn test`: Jestを使用してテストを実行します。
- `yarn test:watch`: ウォッチモードでテストを実行します。
- `yarn postinstall`: GitフックのためにHuskyを設定します。
- `yarn lint-staged`: ステージングされたファイルにESLintを実行します。

## 使用技術

- **Next.js**: `14.0.4`
- **TypeScript**: `5.3.3`
- **GTS (Google TypeScript Style)**: `5.2.0`
- **Commitlint**: `18.4.4`
- **Husky**: `8.0.3`
- **Jest**: `29.7.0`

## プロジェクト構造

プロジェクト構造は標準のNext.jsセットアップに従い、リントおよびテストのための追加設定が含まれています：

```
/yuminnk-nextjs-template
├── /components        # Reactコンポーネント
├── /pages             # Next.jsページ
├── /public            # 静的アセット
├── /styles            # CSSスタイル
├── /tests             # Jestテスト
├── .eslintrc.js       # ESLint設定
├── .gitignore         # Gitの無視ルール
├── commitlint.config.js # Commitlint設定
├── jest.config.js     # Jest設定
├── package.json       # プロジェクトの依存関係とスクリプト
├── tsconfig.json      # TypeScript設定
└── yarn.lock          # Yarnロックファイル
```

## コントリビュート

コントリビュートは歓迎します！コントリビュートするには：

1. リポジトリをフォークします。
2. 新しいブランチを作成します： `git checkout -b feature-branch`。
3. 変更を加えてコミットします： `git commit -m 'Add some feature'`。
4. ブランチにプッシュします： `git push origin feature-branch`。
5. プルリクエストを開きます。

コードがプロジェクトのリントおよびテスト基準に従っていることを確認してください。

## ライセンス

このプロジェクトはMITライセンスの下でライセンスされています。詳細は [LICENSE](LICENSE) ファイルを参照してください。

このテンプレートを必要に応じてカスタマイズしてください！
