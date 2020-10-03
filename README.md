# waibibabo
歪比巴卜加密算法

在线加密解密：<https://passkou.github.io/waibibabo/>

<h1 style="color: #c33; text-align: center">规格说明</h1>
<p>所有字符使用 <b>UTF-8</b> 编码。</p>
<p>一个字节用 <b>四个字</b> 表示（“歪比巴卜”四个字）。</p>
<p>例子：</p>
<p>小写英文字母“a”，编码后对应的十六进制是<code>0x61</code>。</p>
<p>二进制表示如下：</p>
<p><code>01100001</code></p>
<p>每两位bit为一组，分割如下：</p>
<p><code>01</code> <code>10</code> <code>00</code> <code>01</code></p>
<p>按照下面的转换表即可获得对应密文：</p>
<table>
<thead><th>二进制</th><th>密文</th></thead>
<tbody>
  <tr><td>0b00</td><td>歪</td></tr>
  <tr><td>0b01</td><td>比</td></tr>
  <tr><td>0b10</td><td>巴</td></tr>
  <tr><td>0b11</td><td>卜</td></tr>
</tbody>
</table>
<p>对应密文：<code>比巴歪比</code></p>