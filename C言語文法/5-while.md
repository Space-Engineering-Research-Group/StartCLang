# while

```c
#include<stdio.h>
#include<stdbool.h>

void main(void) {
    while(true){
        printf("This is infinity loop\n");
    }
}
```

これは無限に続くループ処理です

もし、このまま実行してしまうと無限にprintfしてプログラムが終了しなくなります

じゃあ、どうすればいいのかというと、

```c
#include<stdio.h>
#include<stdbool.h>

void main() {
    int i = 0;
    while(true){
        i++;
        printf("This is 5 loops\n");
        if(i == 5){
            break;
        }
    }
    return;
}
```

実行結果
```
This is 5 loops
This is 5 loops
This is 5 loops
This is 5 loops
This is 5 loops
```

このように`break`というwhileやforを強制終了させる文を追加します

すると、5回で終わるプログラムができます

```c
while(a < 5 && b < 10)
```

このように条件を追加して`break`を使わずにする方法もあります