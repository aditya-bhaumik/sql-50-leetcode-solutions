<h2><a href="https://leetcode.com/problems/find-customer-referee/description/">584. Find Customer Referee</a></h2>
<h3>Easy</h3>
<hr>

Table: <code>Customer</code>
<pre><table>
  <tr>
    <th> Column Name </th>
    <th> Type </th>
  </tr>
  <tr>
    <td> id </td>
    <td> int </td>
  </tr>
  <tr>
    <td> name </td>
    <td> varchar </td>
  </tr>
  <tr>
    <td> referee_id </td>
    <td> int </td>
  </tr>
</table>
In SQL, id is the primary key column for this table.
Each row of this table indicates the id of a customer, their name, and the id of the customer who referred them
 
</pre>
Find the names of the customer that are not referred by the customer with id = 2.

Return the result table in any order.

The result format is in the following example.
 

<h2>Example 1:</h2>
<pre>
<h3>Input:</h3> 
Customer table:
<table>
  <tr>
    <th>id</th>
    <th>name</th>
    <th>referre_id</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Will</td>
    <td>Null</td>
  </tr>
    <tr>
    <td>2</td>
    <td>Jane</td>
    <td>Null</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Alex</td>
    <td>2</td>
  </tr>
    <tr>
    <td>4</td>
    <td>Bill</td>
    <td>Null</td>
  </tr>
    <tr>
    <td>5</td>
    <td>Zack</td>
    <td>1</td>
  </tr>
</table>

<h3>Output:</h3> 
<table>
  <tr>
  <th>name</th>
  </tr>
  <tr>
    <td>Will</td>
  </tr>
  <tr>
    <td>Jane</td>
  </tr>
  <tr>
    <td>Bill</td>
  </tr>
  <tr>
    <td>Zack</td>
  </tr>
</table>

</pre>
