## 4. 初めてのRuby
* パソコンに付いている制御装置をコンソールという
* print メソッドでメッセージをコンソールに改行なしで表示する
* puts メソッドでメッセージをコンソールに改行ありで表示する

ではこれから、Rubyを書いてみましょう。

```ruby
print "Hello, World"
```

テキストエディタを開き、hello.rbという名前で、  
保存してみましょう。

実行してみましょう。
パソコンを制御する装置であるコンソールに *ruby hello.rb* と書いてみましょう。

```shell
$ ruby hello.rb
Hello, World%
```

と表示されたでしょうか。

おめでとうございます。
これが初めてのRubyプログラムです。

今のプログラムは、Rubyに print という、
コンソールに改行なしで文字を出力する命令(メソッド)です。

---

似たようなメソッドにputsというメソッドがあります。

先ほどのように hello_puts.rb を作ってみましょう。

```ruby
puts "Hello, World"
```

と書き、

```shell
$ ruby hello_puts.rb
Hello, World
$ 
```

となったでしょうか

少し挙動が違うでしょう。  
実は、  
print メソッドは改行なし、putsメソッドは改行ありのコンソールに出力を行うメソッドなのです。

この用にRubyには似たようなメソッドがたくさんあります。
これはRubyが *多様性は善* という思想を持つためです。

--- 
#### コラム
今回は、様々な言語の慣例となっているHello, Worldと表示させましたが、  
実際はどんな文字でもかまいません。
