# Hack

LinkedListの値をずらっとprintする方法。
以下のように Node#__str__ を実装すれば良い。


```py
class Node:
    def __init__(self, val, next=None):
        self.val = val
        self.next = next
    def __str__(self):
        string = str(self.val)
        if self.next is not None:
            string += "->" + self.next.__str__()
        return string
  
> 使い方
> print(head_node)
> None->4->3->None
```




# Coding Cheat Sheet

- これはコーディングのチートシートである。
- 言語ごとの文法が頭の中で混ざってしまっているため、典型的な文法を中心にまとめる。


## Python

<details>
<summary> クラスの書き方</summary>

- 典型的なクラスの書き方
- コンストラクタ、メソッドのオーバーライドは不可能である
  - 同名のものが複数定義された場合最後のものが有効になる
- インスタンス変数は外部から、(オブジェクト.インスタンス変数)で取得できる
- コンストラクタの内部で、インスタンス変数を定義する場合には`self.`が必要である。

```
class Node:
    serial_number = 0                  # クラス定義直下で定義されるのはクラス変数(selfは付けない、インスタンス変数ではない!!!)
    
    @classmethod                       # クラスメソッド
    def get_current_number(cls):
        return cls.serial_number       # クラス変数の参照はcls.~またはself.~から。代入時はself.~ではなくcls.~で行う(self.~だとインスタンス変数が定義されてしまう)

    def __init__(self, value, next):
        self.value = value            # コンストラクタ/メソッドの内部からインスタンス変数を参照/定義する時にはselfが必要(Rubyは参照時は同名のローカル変数が存在しない限り省略可能だった)
        self.next = next
```

- コンストラクタ/メソッドの内部でインスタンス変数を定義するには、`self.が必須`
- コンストラクタ/メソッド内でインスタンス変数/メソッドにアクセスするには、`self.が必須`
- コンストラクタ/メソッド内でselfを付けずに変数を呼び出すと、それはローカル変数のみ探索する(インスタンス変数にはアクセスされない)

- returnのみ定義して返り値なしも可能
    
</details>

<details>
<summary> クラスの書き方</summary>
</details>






## Ruby

- コンストラクタ、メソッドのオーバーライドは不可能である

## Java
