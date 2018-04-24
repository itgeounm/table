# table
Responsive tables <br/>
Break "long" tables to make them more accessible on mobile devices<br/>
Requirements: bootstrap 3.7<br/> 
Table structure: columns AND rows names<br/>
Works on iphones and ipads<br/>

Source table:<br/>

<table class="table table-hover table-striped " summary="Upcoming Sessions">

<tr style="background-color: #ba0c2f; color: white;">
<td>Number of...</td>
<td name="tname_c_source" class="alert alert-success">Column 1</td>
<td name="tname_c_source">Column 2</td>
<td name="tname_c_source">Column i</td>
</tr>

<tr>
<td name="tname_rn_source">Row1</td>
<td name="tname_r0">11</td>
<td name="tname_r1">12</td>
<td name="tname_r2">1i</td>
</tr>
<tr>
<td name="tname_rn_source">Row2</td>
<td name="tname_r0">21</td>
<td name="tname_r1">22</td>
<td name="tname_r2">2i</td>
</tr>
<tr>
<td name="tname_rn_source">Row3</td>
<td name="tname_r0">31</td>
<td name="tname_r1">31</td>
<td name="tname_r2">3i</td>
</tr>
<tr>
<td name="tname_rn_source">Row4</td>
<td name="tname_r0">41</td>
<td name="tname_r1">42</td>
<td name="tname_r2">4i</td>
</tr>
<tr></tr>

</table>
Result table: <br/><br/>
<table class="table table-hover table-striped " summary="Upcoming Sessions">
<tr background-color: #ba0c2f; color: white; >
<td name="tname_c_source">Column 1</td>
</tr>
<tr>
<td name="tname_rn_source">Row1</td>
<td name="tname_r0">11</td>
</tr>
<tr>
<td name="tname_rn_source">Row2</td>
<td name="tname_r0">21</td>
</tr>
<tr>
<td name="tname_rn_source">Row3</td>
<td name="tname_r0">31</td>
</tr>
<tr>
<td name="tname_rn_source">Row4</td>
<td name="tname_r0">41</td>
</tr>
<tr style="background-color: #ba0c2f; color: white;">
<td name="tname_c_source">Column 2</td>
</tr>
<tr>
<td name="tname_rn_source">Row1</td>
<td name="tname_r0">11</td>
</tr>
<tr>
<td name="tname_rn_source">Row2</td>
<td name="tname_r0">21</td>
</tr>
<tr>
<td name="tname_rn_source">Row3</td>
<td name="tname_r0">31</td>
</tr>
<tr>
<td name="tname_rn_source">Row4</td>
<td name="tname_r0">41</td>
</tr>
<tr style="background-color: #ba0c2f; color: white;">
<td name="tname_c_source">Column i</td>
</tr>
<tr>
<td name="tname_rn_source">Row1</td>
<td name="tname_r0">11</td>
</tr>
<tr>
<td name="tname_rn_source">Row2</td>
<td name="tname_r0">21</td>
</tr>
<tr>
<td name="tname_rn_source">Row3</td>
<td name="tname_r0">31</td>
</tr>
<tr>
<td name="tname_rn_source">Row4</td>
<td name="tname_r0">41</td>
</tr>

</table>



