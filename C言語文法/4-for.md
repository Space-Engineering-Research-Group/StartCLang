# for

```c
#include<stdio.h>
int main() {
    int i;
    for(i = 0; i < 5; i++) {
        printf("Hello\n");
    }
    return 0;
}
```

実行結果

```
Hello
Hello
Hello
Hello
Hello
```

これは5回Helloを出力するプログラムです

```c
for(i = 0; i < 5; i++)
```

これをひとつずつ解説すると

```c
i = 0;
```

でiをい初期化してiのはじめる数字を決めています

```c
i < 5
```

で５未満かという条件を指定しています。この条件がなければ無限ループします

```c
i++;
```

これはインクリメントといってiの変数を1ずつ増という意味です

最後に{}の中にループさせたいコードを書きます。ここではprintfを用いています。