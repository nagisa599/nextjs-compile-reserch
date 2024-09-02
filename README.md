# nextjs-compile-reserch

このリポジトリーは Nextjs のコンパイルにかかる時間を調査するリポジトリーです

# 使用方法

```bash
# node_moduleをinstall
npm i
```

trace ファイルを nextjs のプロジェクトの.next フォルダーの trace ファイルをコピー、プロジェクト直下にコピー

```bash
# 実行コマンド
node trace-to-tree.mjs trace
```

> [!NOTE]
> trace ファイルは、直接パスを指定してもよい
