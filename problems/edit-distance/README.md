<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

## 72. Edit Distance (Hard)

<p>Given two words <em>word1</em> and <em>word2</em>, find the minimum number of operations required to convert <em>word1</em> to <em>word2</em>.</p>

<p>You have the following 3 operations permitted on a word:</p>

<ol>
	<li>Insert a character</li>
	<li>Delete a character</li>
	<li>Replace a character</li>
</ol>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> word1 = &quot;horse&quot;, word2 = &quot;ros&quot;
<strong>Output:</strong> 3
<strong>Explanation:</strong> 
horse -&gt; rorse (replace &#39;h&#39; with &#39;r&#39;)
rorse -&gt; rose (remove &#39;r&#39;)
rose -&gt; ros (remove &#39;e&#39;)
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> word1 = &quot;intention&quot;, word2 = &quot;execution&quot;
<strong>Output:</strong> 5
<strong>Explanation:</strong> 
intention -&gt; inention (remove &#39;t&#39;)
inention -&gt; enention (replace &#39;i&#39; with &#39;e&#39;)
enention -&gt; exention (replace &#39;n&#39; with &#39;x&#39;)
exention -&gt; exection (replace &#39;n&#39; with &#39;c&#39;)
exection -&gt; execution (insert &#39;u&#39;)
</pre>


### Related Topics
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[Dynamic Programming](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### Similar Questions
  1. [One Edit Distance](https://github.com/openset/leetcode/tree/master/problems/one-edit-distance) (Medium)
  1. [Delete Operation for Two Strings](https://github.com/openset/leetcode/tree/master/problems/delete-operation-for-two-strings) (Medium)
  1. [Minimum ASCII Delete Sum for Two Strings](https://github.com/openset/leetcode/tree/master/problems/minimum-ascii-delete-sum-for-two-strings) (Medium)