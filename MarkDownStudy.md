MarkDown ���� ����
=====
- [���� ����Ʈ](https://gist.github.com/ihoneymon/652be052a0727ad59601)
# 1. ��ũ�ٿ� ����
1.1. ���Headers
---------
- ū����

    This is an H1
    =========

This is an H1
* ��� �˾Ƴ� �� : # �̷��� H1 �۸Ӹ� ������ ==�ϸ� ���� �ȵ�!
========
- ��������

    This is an H2
    -------

This is an H2
-------
- �۸Ӹ� : 1~6���� ����

    # This is an H1
    ## This is an H2
    ###### This is an H3
    �˾Ƴ� �� : �۸Ӹ� ������ ��� ===, ---ǥ�ø� �ϸ� �ȵȴ�. �ؽ�Ʈ ������ ����.

1.2. BlockQuote
------
�̸��Ͽ��� ����ϴ� > ���ο빮��

    > This is a first bq.
    >   > This is a second bq.
    >   >   > This is a third bq.

> This is a first bq.
>   > This is a second bq.
>   >   > This is a third bq.
�� �ȿ��� �ٸ� ��ũ�ٿ� ��� ���԰���
> ### This is a Header3.
>   > - This is a list.
>   >   >   This is a code.

1.3. ���
-----
- ### �����ִ� ���(��ȣ)
���ڿ� �� ���

    1. ù��°
    2. �ι�°
    3. ����°

1. ù��°
2. �ι�°
3. ����°
##### � ��ȣ�� �Է��ص� ������������ ���ǵ�

    1. ù��°
    3. �ι�°
    2. ����°

1. ù��°
3. �ι�°
2. ����°

- ### �������� ���(*, +, - ����)

    * 1
        * 2
            * 3
    + 1
        + 2
             +3
    - 1
        - 2
            - 3
 * 1
    * 2
         * 3

+ 1
    + 2
         +3
 - 1
     - 2
         - 3  
ȥ���ؼ� ��뵵 ����
���±��� ���� -�� *���� �˰� ����ϰ� �־���...����..
- 1
    * 2
        + 3    

1.4. �ڵ�
-----
### 1.4.1 �鿩����
4�� ���� or ������ �鿩���� �ϸ� �鿩���� ���� ���� ���� �� ���� �ڵ�

    �̷��� �ڵ� �����ϸ� �ȴ� �ϳ׿�..
    �׷��� �� �� ���� ������ ����� �ν� �ȵȴ� ��
    �η��η� ���ƴ�.

### 1.4.2 �ڵ��
2���� ��� ����

- ```<pre><code>{code}</code></pre>```  �̿���

����

    <pre>
    <code>
    printf("��ũ�ٿ��");
    </code>
    </pre>

<pre>
<code>
printf("��ũ�ٿ� ����);
</code>
</pre>

- �ڵ���ڵ�("```") �̿���

    ```
    printf("�ڵ������");
    ```

```
�ڵ������
```

1.5 ���� ```<hr/>```
----
�Ʒ� ���� ��� ������ �����. ������ ������ �뵵�� �����

```
* * *
***
*****
- - -
---------
```

- ���� ��

* * *
***
*****
- - -

1.6 ��ũ
---
- ���� ��ũ

```
[Google][googlelink]
[googlelink]: https://google.com "go google"
```
[Google][googlelink]
[googlelink]: https://google.com "go google"

- �ܺθ�ũ

```
[Google](https://google.com, "google link")
```
[Google](https://google.com, "google link")

- �ڵ�����

```
�Ϲ����� URL Ȥ�� �̸����ּ� ��ũ ����
* �ܺθ�ũ: <https://example.com/>
* �̸��ϸ�ũ: <address@example.com>
```

�Ϲ����� URL Ȥ�� �̸����ּ� ��ũ ����
* �ܺθ�ũ: <https://example.com/>
* �̸��ϸ�ũ: <address@example.com>

1.7 ����
-----

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```

> ���� �߰��� ��� �� ��� **����** �ϴ� �� ����

1.8. �̹���
---

```
![Alt text](/path/to/img.jpg)
```
![Alt text](https://camo.githubusercontent.com/202c9ae1d457d6109be6c4cf13db9cac5fd708a6/687474703a2f2f6366696c65362e75662e746973746f72792e636f6d2f696d6167652f32343236453634363534334339423435333243374230)

�ǳ�?