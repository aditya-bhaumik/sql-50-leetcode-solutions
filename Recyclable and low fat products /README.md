Table: <code>Products</code>
<pre><table>
  <tr>
    <th> Column Name </th>
    <th> Type </th>
  </tr>
  <tr>
    <td> product_id </td>
    <td> int </td>
  </tr>
  <tr>
    <td> low_fats </td>
    <td> enum </td>
  </tr>
  <tr>
    <td> recyclable </td>
    <td> enum </td>
  </tr>
</table>
product_id is the primary key (column with unique values) for this table.
low_fats is an ENUM (category) of type ('Y', 'N') where 'Y' means this product is low fat and 'N' means it is not.
recyclable is an ENUM (category) of types ('Y', 'N') where 'Y' means this product is recyclable and 'N' means it is not.
 
</pre>
Write a solution to find the ids of products that are both low fat and recyclable.

Return the result table in any order.

The result format is in the following example.

 

<h2>Example 1:</h2>
<pre>
<h3>Input:</h3> 
Products table:
<table>
  <tr>
    <th>product_id</th>
    <th>low_fats</th>
    <th>recyclable</th>
  </tr>
  <tr>
    <td>0</td>
    <td>Y</td>
    <td>N</td>
  </tr>
    <tr>
    <td>1</td>
    <td>Y</td>
    <td>Y</td>
  </tr>
  <tr>
    <td>2</td>
    <td>N</td>
    <td>Y</td>
  </tr>
    <tr>
    <td>3</td>
    <td>Y</td>
    <td>Y</td>
  </tr>
    <tr>
    <td>4</td>
    <td>N</td>
    <td>N</td>
  </tr>
</table>

<h3>Output:</h3> 
<table>
  <tr>
  <th>product_id</th>
  </tr>
  <tr>
    <td>1</td>
  </tr>
  <tr>
    <td>3</td>
  </tr>
</table>

Explanation: Only products 1 and 3 are both low fat and recyclable.
</pre>
