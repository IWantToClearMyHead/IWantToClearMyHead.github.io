### 字符串
什么是字符串？字符串看字义就是字符连成的串，英文称之为string。
比如我们把<strong>从放弃到入门</strong>放到内存中，应该如下。
<BLOCKQUOTE><PRE>
------------------------------------------
| 从 | 放 | 弃 | 到 | 入 | 门 |
------------------------------------------
</PRE></BLOCKQUOTE>
又由于计算机需要一个<strong>截止符</strong>\0，类似句号，用以标记结束。
<BLOCKQUOTE><PRE>
------------------------------------------
| 从 | 放 | 弃 | 到 | 入 | 门 | \0 |
------------------------------------------
</PRE></BLOCKQUOTE>
这里一个格子代表一个<strong>字符</strong>，如果以数组的形式来看，也可以叫做<strong>字符数组</strong>。
一个字符大小为一个字节(Byte)，也即八位(bit)，所以ASCII编码范围为
<a href="https://www.codecogs.com/eqnedit.php?latex=2^8" target="_blank"><pre xml:lang="latex">sqrt2</pre></a>






