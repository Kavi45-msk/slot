# Ex03 Time Table
## Date:04.03.2024

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
	<head>
		<title>
			SoftWare Companies
		</title>
	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="lightgray">
			<caption>SLOT TIME TABLE- Kavi M S (212223220044) </caption>
            <br>
			<tr>
				<th bgcolor="yellow"> Day/Time </th>
				<th bgcolor="yellow"> Monday </th>
				<th bgcolor="yellow"> Tuesday </th>
                <th bgcolor="yellow"> Wednesday </th>
                <th bgcolor="yellow"> Thursday </th>
                <th bgcolor="yellow"> Friday </th>
                <th bgcolor="yellow"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="sky blue"> 8-10 </td>
                <td> Free SLOT </td>
                <td> ENG </td>
                <td> FWAD </td>
                <td> CHEM </td>
                <td> EMBD </td>
                <td> MATH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 10-12 </th>
				<td> BEEE </td>
                <td> FWAD </td>
                <td> PHY </td>
                <td> MATH </td>
                <td> FUND OF C </td>
                <td> ENG </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 1-3 </th>
                <td> FWAD </td>
                <td> OS </td>
                <td> CRT SKILLS </td>
                <td> BEEE </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 3-5 </td>
                <td> FUND OF C </td>
                <td> PHY </td>
                <td> ML </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19EE305 </td>
                    <td align="center"> Basic electrical,electronics and measurement engineering (BEEE) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> Fundamentals of web applications (FWAD) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19AI304 </td>
                    <td align="center"> Fundamentals of C programming (FUND OF C) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19EN101 </td>
                    <td align="center"> English (ENG) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19AI404 </td>
                    <td align="center"> Inroduction to Machine learning (ML)</td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19PH214 </td>
                    <td align="center"> Physics (PHY) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19CS504 </td>
                    <td align="center"> Operating System (OS) </td>
                </tr>
                <tr>
                    <th align="center"> 8. </td>
                    <td align="center"> 19EY702 </td>
                    <td align="center"> Creative skills for communication (CRT SKILLS) </td>
                </tr>
                </table>
	</body>
</html>
```

## OUTPUT
![Screenshot 2024-03-18 223526](https://github.com/Kavi45-msk/slot/assets/147457752/e50ba2c9-bc46-464c-84fe-36707a3cade5)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
