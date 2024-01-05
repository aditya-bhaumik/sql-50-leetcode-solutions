Table: <code>Views</code>
<pre><table>
  <tr>
    <th> Column Name </th>
    <th> Type </th>
  </tr>
  <tr>
    <td> article_id </td>
    <td> int </td>
  </tr>
  <tr>
    <td> author_id </td>
    <td> int </td>
  </tr>
  <tr>
    <td> viewer_id </td>
    <td> int </td>
  </tr>
  <tr>
    <td> view_date </td>
    <td> date </td>
  </tr>
</table>
  There is no primary key (column with unique values) for this table, the table may have duplicate rows.
Each row of this table indicates that some viewer viewed an article (written by some author) on some date. 
Note that equal author_id and viewer_id indicate the same person.
</pre>
Write a solution to find all the authors that viewed at least one of their own articles.
Return the result table sorted by <code>id</code> in ascending order.
The result format is in the following example.

<h2>Example 1:</h2>
<pre>
<h3>Input:</h3> 
Views table:
<table>
  <tr>
    <th> article_id </th>
    <th> author_id  </th>
    <th> viewer_id </th>
    <th> view_date </th>
  </tr>
  <tr>
    <td>1</td>
    <td>3</td>
    <td>5</td>
    <td>2019-08-01</td>
  </tr>
  <tr>
    <td>2</td>
    <td>7</td>
    <td>7</td>
    <td>3029-08-01</td>
  </tr>
  <tr>
    <td>4</td>
    <td>7</td>
    <td>1</td>
    <td>2019-07-22</td>
  </tr>
</table>

<h3>Output:</h3> 
<table>
  <tr>
  <th>id</th>
  </tr>
  <tr>
    <td>4</td>
  </tr>
  <tr>
    <td>7</td>
  </tr>
</table>
