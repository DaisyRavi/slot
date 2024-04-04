# Ex03 Time Table
## Date:

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
<html>
	<head>
		<title>Daisy R Time Table</title>
	</head>
	<body align="center">
        <img src="/static/logo.png" height="200" width="800" >
	<table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
        <caption> SLOT TIME TABLE-Daisy R(212223220016)</caption>
		<tr bgcolor="Light blue" align="center">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
                        <th>Wednesday</th>
			<th>Thursday</th>
			<th>Friday</th>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light blue">8-10</th>
			<td>WEB</td>
			<td>Machine Learning</td>
			<td>Chemistry</td>
			<td>DE</td>
			<td>Machine Learning</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light Blue">10-12</th>
			<td>Calculus And Matrix</td>
			<td>Python</td>
			<td>FREE SLOT</td>
			<td>FREE SLOT</td>
			<td>Calculus And Matrix</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="LIght blue">12-1</th>
			<td colspan="5" align="center">LUNCH</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light Blue">1-3</th>
			<td>Creative Skill</td>
			<td>Chemistry</td>
			<td>Python</td>
			<td>FREE SLOT</td>
			<td>Computer Network</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light Blue">3-5</th>
                        <td>DE</td>
			<td>FREE SLOT</td>
			<td>Computer Network</td>
			<td>WEB</td>
			<td>FREE SLOT</td>
			
	</table>
    <br>
    <table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
        <tr bgcolor="Light Blue" align="center">
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">1.</th>
            <td>19AI301</td>
            <td>Python of Programing</td>
        </tr align="center">
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">2.</th>
            <td>19AI414</td>
            <td>Fundamentals of Web application Development(FWAD)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">3.</th>
            <td>19CS406</td>
            <td>Computer Network</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">4.</th>
            <td>19EE404</td>
            <td>Digital Electronics(DE)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">5.</th>
            <td>19EY702</td>
            <td>Creative skills for communications(CSFC)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">6.</th>
            <td>19MA201</td>
            <td>Calculus And Matrix Algebra</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">7.</th>
            <td>19CY205</td>
            <td>Chemistry</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">8.</th>
            <td>19AI410</td>
            <td>Machine Learning</td>
        </tr>

    </table>
	</body>
</html>

## OUTPUT
![alt text](<slot time table-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
