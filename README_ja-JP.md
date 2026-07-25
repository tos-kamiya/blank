# blank

Linux の画面をすぐに暗くするための小さなスクリプト集です。

## Requirements

- Bash
- GNOME on Wayland: `gnome-session-inhibit` and `busctl`
- X11: `xset`

## Usage

画面を暗くします。

```bash
./blank
```

画面の自動暗転を一時的に抑止します。動画再生や読書など、画面を見続ける場合に使用します。

```bash
./awake
```

`awake` は実行中のみ有効です。終了するには `Ctrl+C` を押してください。実行中は、起動からの経過時間を標準エラー出力に表示します。

英語のドキュメントは [README.md](README.md) を参照してください。

## License

This project is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
