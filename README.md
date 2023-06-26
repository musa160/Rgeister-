# Rgeister-
Register code using html
<!DOCTYPE html>
<html>
<head>
<title>Text Input Control</title>
<style>
*{
background-color:white;
}
</style>
</head>
<body>
<address>
      <a href="https://mail.google.com/mail/u/0/#inbox"> <img src="C:\Users\musa\Desktop\jaw_files\ebc.jpg" width="50" height="60" /></a> <br> 

</address>
<p>The pre tag preserves both spaces and line breaks:</p>
<!-- pre tag to preserve space and break as it is-->
<pre>
   <b><em>My Bonnie lies over the ocean.</em></b><!--bold and em-->

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.
   
   Oh, bring back my Bonnie to me.
</pre>

<form>
First name:  <input type="text" name="first_name" />
<br>
Last name:   <input type="text" name="last_name" /><br>
Password:    <input type="password" name="password"  /><br>
  <h5>Dept  </h5>
 <input type="checkbox" name="CS" value="on"> CS
<input type="checkbox" name="IT" value="on"> IT

 <h5>Sex  </h5>
 <input type="radio" name="subject" value="Male"> Male
<input type="radio" name="subject" value="Female"> Female  
<br>
 Select Country:<select value="Country" name="dropdown">
<option value="Afganistan" >Afganistan</option>
<option value="China">China</option>
<option value="Ethiopia"selected>Ethiopia</option>
<option value="USA">USA</option>

</select>

<br>
Description : <br />
<textarea rows="5" cols="50" name="description" placeholder="Enter description here...">
</textarea><br>
	<!--file upload --
	<input type="file" name="fileupload" accept="image/*" />-->
<br>
<input type="submit" name="submit" value="Submit" />
<input type="reset" name="reset"  value="Reset" />
</form><br>

<table>
<tr>
<td>15</td>
<td>15</td>
<td>30</td>
</tr>
<tr>
<td>45</td>
<td>60</td>
<td>45</td>
</tr>
<tr>
<td>60</td>
<td>90</td>
<td>90</td>
</tr>
</table>


<!--WidTh & spacing-->
<table width="400" cellpadding="10" cellspacing="5">
<tr>
<th width="150"></th>
<th>Withdrawn</th>
<th>Credit</th>
<th width="150">Balance</th>
</tr>
<tr>
<th>January</th>
<td>250.00</td>
<td>660.50</td>
<td>410.50</td>
</tr>
<tr>
<th>February</th>
<td>135.55</td>
<td>895.20</td>
<td>1170.15</td>
</tr>
</table>

<!--border & background-->

<table border="2" bgcolor="#efefef">
<tr>
<th width="150"></th>
<th>Withdrawn</th>
<th>Credit</th>
<th width="150" bgcolor="#cccccc">Balance</th>
</tr>
<tr>
<th>January</th>
<td>250.00</td>
<td>660.50</td>
<td bgcolor="#cccccc">410.50</td>
</tr>
<tr>
<th>February</th>
<td>135.55</td>
<td>895.20</td>
<td bgcolor="#cccccc">1170.15</td>
</tr>
</table>


<table>
<tr>
<th></th>
<th>ABC</th>
<th>BBC</th>
<th>CNN</th>
</tr>
<tr>
<th>6pm - 7pm</th>
<td rowspan="2">Movie</td>
<td>Comedy</td>
<td>News</td>
</tr>
<tr>
<th>7pm - 8pm</th>
<td>Sport</td>
<td>Current Affairs</td>
</tr>
</table>



</body>
</html>

