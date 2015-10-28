#Table
* Table: `<table>`
* Row by row first, then column(data) by column
* Table Row: `<tr>`
* Table Data: `<td>`
* Table Headeing: `<th>`
```
<table>
    <td>
        <th>0,1</th>
        <th>0,2</th>
    </td>
    <tr>
        <td>1,1</td>
        <td>1,2</td>
    </tr>
    <tr>
        <td>2,1</td>
        <td>2,2</td>
    </tr>
</table>
```
* COLumn SPAN attribute for `td`: `colspan`
* ROW SPAN attribute for td: `rowspan`
```
<table>
    <th>
        <td colspan="2">0,0</td>
    </th>
    <tr>
        <td>1,1</td>
        <td>1,2</td>
    </tr>
    <tr>
        <td>2,1</td>
        <td>2,2</td>
    </tr>
</table>
```