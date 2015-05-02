
<p>当网页内容过长，你浏览到底部需要回到顶部时，是不是希望“一键直达”呢？scrollUp 就是这样一款插件，它能够让用户滚动条滚动到一定的位置时（可设置），右下角出现“滚动到顶部”的按钮，点击后，页面就是慢慢的滚动到顶部，而不是硬生生的直接回到顶部，提高了用户体验。</p>
<p>scrollUp 还提供了 3 种主题，在 css 文件夹下。当然你可以自定义。</p>
<h2>使用方法</h2>
<h3>引入文件</h3>
<pre class="brush:xml">&lt;script src="js/jquery.min.js"&gt;&lt;/script&gt;
&lt;script src="js/jquery.scrollUp.min.js"&gt;&lt;/script&gt;</pre>
<h3>JavaScript</h3>
<pre class="brush:js">$(function () {
&nbsp;&nbsp; &nbsp;$.scrollUp();
});</pre>
<h2>参数</h2>
<table class="table">
<thead>
<tr>
<th>参数</th>
<th>说明</th>
</tr>
</thead>
<tbody>
<tr>
<td>scrollName</td>
<td>绑定 id，默认为 scrollUp</td>
</tr>
<tr>
<td>topDistance</td>
<td>滚动条距离顶部多少距离时出现按钮，单位为 px，默认为 300</td>
</tr>
<tr>
<td>topSpeed</td>
<td>滚动到顶部的时间，单位为 ms，默认为 300</td>
</tr>
<tr>
<td>animation</td>
<td>按钮出现、隐藏的方式，可选 fade（淡入淡出）、slide（滑块）或 none（无）</td>
</tr>
<tr>
<td>animationInSpeed</td>
<td>按钮出现的时间</td>
</tr>
<tr>
<td>animationOutSpeed</td>
<td>按钮隐藏的时间</td>
</tr>
<tr>
<td>scrollText</td>
<td>按钮内的文字，默认为 Scroll to top</td>
</tr>
<tr>
<td>activeOverlay</td>
<td>是否显示参考线，值为十六进制颜色值或 false，默认为 false</td>
</tr>
</tbody>
</table>
<h2>自定义</h2>
<p>你可以通过 CSS 自定义按钮，让按钮更适合你的项目。例如：</p>
<pre class="brush:css">#scrollUp {
&nbsp;&nbsp; &nbsp;bottom: 20px;
&nbsp;&nbsp; &nbsp;right: 20px;
&nbsp;&nbsp; &nbsp;padding: 10px 20px;
&nbsp;&nbsp; &nbsp;background: #555;
&nbsp;&nbsp; &nbsp;color: #fff;
}</pre>
