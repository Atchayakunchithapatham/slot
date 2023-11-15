# Ex03 Time Table
## Date:12.11.2023

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<title> my slot </title>
<body>
<center>
<img src="/static/logo.png" height="100" width="560">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpading="4" border="5" bgcolor="cyan">
<caption> <b> SLOT TIME TABLE - ATCHAYA K (23014009) </b> </caption>
<tr align="center">
	<th bgcolor="yellow"> Day/Time </th>
	<th bgcolor="yellow"> Monday </th>
	<th bgcolor="yellow"> Tuesday </th>
	<th bgcolor="yellow"> Wednesday </th>
	<th bgcolor="yellow"> Thursday </th>
	<th bgcolor="yellow"> Friday </th>
</tr>

<tr align="center">
	<th bgcolor="yellow"> 8-10 </th>
	<td> FREE SLOT </td>
	<td> ENG </td>
	<td> FWAD </td>
	<td> YOGA </td>
	<td> FREE SLOT </td>
</tr>

<tr align="center">
	<th bgcolor="yellow"> 10-12 </th>
	<td> CHE </td>
	<td> MAT </td>
	<td> FREE SLOT </td>
	<td> FWAD </td>
	<td> FREE SLOT </td>
</tr>

<tr align="center">
	<th bgcolor="yellow"> 12-1 </th>
	<td colspan="5" align="center"> L U N C H </td>
</tr>

<tr align="center">
	<th bgcolor="yellow"> 1-3 </th>
	<td> MAT </td>
	<td> CHE </td>
	<td> FREE SLOT </td>
	<td> ENG </td>
	<td> FWAD </td>
</tr>

<tr align="center">
	<th bgcolor="yellow"> 3-5 </th>
	<td colspan="2" align="center"> FREE SLOT </td>
	<td> SOFT SKILL  </td>
	<td> PYTHON </td>
	<td> PYTHON </td>
</tr>

</table>

<br>
<table align="center" cellspacing="2" cellpading="4" border="2">
<tr align="center">
	<th> S.NO </th>
	<th> SUBJECT CODE </th>
	<th> SUBJECT NAME </th>
</tr>

<tr align="center">
	<td align="center"> 1 </td>
	<td align="center"> 19AI414 </td>
	<td align="center"> Fundamental of Web Application (FWAD) </td>
</tr>

<tr align="center">
	<td align="center"> 2 </td>
	<td align="center"> 19AI301 </td>
	<td align="center"> Python Programming </td>
</tr>
<tr align="center">
	<td align="center"> 3 </td>
	<td align="center"> 19CY205 </td>
	<td align="center"> Principle of Chemistry in Engineering </td>
</tr>

<tr align="center">
	<td align="center"> 4 </td>
	<td align="center"> 19EN101 </td>
	<td align="center"> Communicative English </td>
</tr>

<tr align="center">
	<td align="center"> 5 </td>
	<td align="center"> 19EN616 </td>
	<td align="center"> Yoga And Meditation </td>
</tr>

<tr align="center">
	<td align="center"> 6 </td>
	<td align="center"> 19EY701 </td>
	<td align="center"> Soft skills </td>
</tr>

<tr align="center">
	<td align="center"> 7 </td>
	<td align="center"> 19MA201 </td>
	<td align="center"> Calculus and Matrix Alegebra </td>
</tr>
</br>
</table>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2023-11-15 093454.png>)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
