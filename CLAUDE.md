# 生成AIを用いた文書翻訳アプリ

Amplify と Dify を使って、文書翻訳アプリを構築します。


# 技術構成

- フロントエンド: React
- バックエンド: Amplify
- AI: Dify

AmplifyのStorageにファイルをアップロードしたあとに、Lambdaをトリガーして、DifyのAPIを呼び出し、翻訳結果を取得します。

翻訳が終了するとそれをStorageに保存し、フロントエンドで表示します。
