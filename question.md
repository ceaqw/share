# python课后题

## 第003讲：变量和字符串（上）
0. Python3 虽然支持中文作为变量名，但有些大牛却不赞同这么做，你觉得他们的依据是什么？

1. 以下哪个变量命名不正确？为什么？

      （A）MM_520  （B）_MM520_  （C）520_MM  （D）_520_MM  （E）我M爱M你

2. 你觉得下面代码出错的原因是什么？
    ```python
    >>> print(x)
    Traceback (most recent call last):
    File "<pyshell#1>", line 1, in <module>
        print(x)
    NameError: name 'x' is not defined
    ```

3. 你觉得下面代码中，print() 函数会打印什么内容？
    ```python
    >>> x = 520    
    >>> x = 880
    >>> print(X)
    ```

4. 你觉得下面代码中，print() 函数会打印什么内容？
    ```python
    >>> x, y, z = 3, 4, 5
    >>> x, y, z = y, x, z
    >>> print(x, y, z)
    ```

5. print("小甲鱼常说："Good good study, day day up!"")
    ```python
    print("小甲鱼常说："Good good study, day day up!"")
    ```

6. 请填充下面图片中红色部分的代码，让 print() 函数可以按照要求打印字符串。
    ![](https://xxx.ilovefishc.com/forum/201910/24/174459mlkagm212aa4k6ku.jpg)

## 第004讲：变量和字符串（下）

0. 请问下面代码有没有毛病，为什么？
    ```python
    >>> input = "I love FishC.com"
    >>> print(input)
    I love FishC.com
    ```

1. 请问下面代码为什么会出错，应该如何解决？
    ```python
    >>> print("C:\Users\goodb\Desktop")
    SyntaxError: (unicode error) 'unicodeescape' codec can't decode bytes in position 2-3: truncated \UXXXXXXXX escape
    ```

2. 如果要为一个函数写说明文档，那么你觉得应该使用哪种字符串比较合适？

3. 请问是 '123' 大还是 256 大？

4. 请写出下面几个表达式的结果。

    A. '123' + 256

    B. '123' + '256'

    C. '123' * 3

    D. '123' - '12'

