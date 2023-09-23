# Radicast-pkg

[Radicast](https://github.com/P-man2976/radicast) を [vercel/pkg](https://github.com/vercel/pkg) を使用して単一実行ファイル化したリポジトリです。Radicastについての詳しい説明は [P-man2976/radicast](https://github.com/P-man2976/radicast) を参照してください。

## ダウンロードと実行

### Windows (x64, amd64)

[https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-win-x64.zip](https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-win-x64.zip) からzipファイルをダウンロード・解凍し、解凍したフォルダでPowerShellから以下コマンドを実行してください。

```ps1
.\radicast.exe
```

### Linux (x64, amd64)

```bash
curl -L https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-linuxstatic-x64.tar.gz | tar xzvf -
./radicast-linuxstatic-x64/radicast
```

### Linux (ARM64)

```bash
curl -L https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-linuxstatic-arm64.tar.gz | tar xzvf -
./radicast-linuxstatic-arm64/radicast
```

### Linux (ARMv7)

```bash
curl -L https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-linuxstatic-armv7.tar.gz | tar xzvf -
./radicast-linuxstatic-armv7/radicast
```

### macOS (Intel)

```bash
curl -L https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-mac-x64.tar.gz | tar xzvf -
xattr -d com.apple.quarantine ./radicast-pkg-mac-x64/radicast
./radicast-pkg-mac-x64/radicast
```

### macOS (Apple Silicon)

```bash
curl -L https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-mac-arm64.tar.gz | tar xzvf -
./radicast-pkg-mac-arm64/radicast
```

### Alpine

```bash
curl -L https://github.com/P-man2976/radicast-pkg/releases/latest/download/radicast-pkg-alpine-x64.tar.gz | tar xzvf -
./radicast-alpine-x64/radicast
```

その他のプラットフォーム・アーキテクチャ向けのビルドは [リリースページ](https://github.com/P-man2976/radicast-pkg/releases) にあります。
