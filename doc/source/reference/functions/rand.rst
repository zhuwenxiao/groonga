.. -*- rst -*-

.. highlightlang:: none

rand
====

名前
----

rand - 乱数を生成する

書式
----
::

 rand([max])

説明
----

Groonga組込関数の一つであるrandについて説明します。組込関数は、script形式のgrn_expr中で呼び出すことができます。

rand() 関数は 0 から max の間の疑似乱数整数を返します。

引数
----

``max``

  返値の最大値を指定します。省略した場合は RAND_MAX が指定されたものとみなされます。

返値
----

0 と max の間の数を表すInt32型の値を返します。

例
--
::

 rand(10)
 3
