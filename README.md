# ClangFunction
関数

## 処理
sum_gokei()関数を作り、その中で計算を行う。

## コード
```
#include <stdio.h>

void sum_gokei(void);

int main(void) {
    sum_gokei();
    return 0;
}

void sum_gokei(void) {
    printf("%d\n", 5 * 8);
}
```

## 出力結果  
```
40
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | gcc 4.4.7 |
