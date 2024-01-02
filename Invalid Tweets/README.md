Table: <code>Tweets</code>
<pre><table>
  <tr>
    <th> Column Name </th>
    <th> Type </th>
  </tr>
  <tr>
    <td> tweet_id </td>
    <td> int </td>
  </tr>
  <tr>
    <td> content </td>
    <td> varchar </td>
  </tr>
</table>
</pre>
Write a solution to find the IDs of the invalid tweets. The tweet is invalid if the number of characters used in the content of the tweet is strictly greater than 15.
Return the result table in any order.
The result format is in the following example.

<h2>Example 1:</h2>
<pre>
<h3>Input:</h3> 
Tweets table:
<table>
  <tr>
    <th>tweet_id</th>
    <th>content</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Vote for Biden</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Let us make America great again!</td>
  </tr>
</table>

<h3>Output:</h3> 
<table>
  <tr>
  <th>tweet_id</th>
  </tr>
  <tr>
    <td>2</td>
  </tr>
</table>
