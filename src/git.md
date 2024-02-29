# Gitのナレッジ

## switch
| コマンド | 説明 |
| --- | --- |
| git switch <branch> | ブランチを切り替える |
| git switch -c <branch> | 新しいブランチを作成して切り替える |
| git switch -C <branch> | ブランチを上書きして切り替える |
| git switch -d <branch> | ブランチを切り替える(変更を保存せず) |
| git switch -f <branch> | 強制的に新しいブランチに切り替える |
| git switch - | 一個前のブランチに切り替える |

## restore
| コマンド | 説明 |
| --- | --- |
| git restore <file> | ファイルを元に戻す |
| git restore --staged <file> | Staging状態のファイルを元に戻す(git addした後のファイルを元に戻す) |
| git restore '*.txt' | 拡張子を指定してファイルを元に戻す |
| git restore -s <commit hash> <file> | 指定したコミットの状態に戻す |

