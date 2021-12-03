### Q1

```HTML
    <html lang="en">
    <head>
      <title>Document guvi</title>
    </head>
    <body>
      <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </div>
      <div>
        Guvi Geek Network
      </div>
    </body>
    </html>
```

### Q2

```HTML
<html lang="en">
<head>
  <title>Document guvi</title>
</head>
<body>
  <div>
    Lorem ipsum dolor sit amet consectetur adipisicing elit.
    <div>
      Guvi Geek Network
    </div>
  </div>
</body>
</html>
```
### Q3

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>Please give us your contact details. We will get back to you.</p>
    <h3>Contact form</h3>
    <form action="https://example.com" method="GET">
        <label for="fname">First Name:</label><br>
        <input type="text" id="fname" name="fname" required><br>
        <label for="lname">Last Name:</label><br>
        <input type="text" id="lname" name="lname" required><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="mobile">Mobile No:</label><br>
        <input type="tel" id="mobile" name="mobile" pattern="[0-9]{10}" required><br>
        <div>
            <p>Choose best time to contact: </p>
            <input type="checkbox" id="time1" name="time1" value="morning">
            <label for="time1">Morning</label><br>
            <input type="checkbox" id="time2" name="time2" value="afternoon">
            <label for="time2">Afternoon</label><br>
            <input type="checkbox" id="time3" name="time3" value="evening">
            <label for="time3">Evening</label>
        </div> <br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```
### Q4

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>Below are skills required for a web dev: </p>
    <ul>
        <li>Programming Language
            <ul>
                <li>JavaScript
                    <ol>
                        <li>Angular</li>
                        <li>React</li>
                        <li>Vue.js</li>
                    </ol>
                </li>
                <li>Python
                    <ol>
                        <li>Django Framework</li>
                        <li>Flask Framework</li>
                    </ol>
                </li>
                <li>Java
                    <ol>
                        <li>Spring</li>
                        <li>Maven</li>
                        <li>Hibernate</li>
                    </ol>
                </li>
            </ul>
        </li>
        <li>Database
            <ul>
                <li>MySQL</li>
                <li>MongoDB</li>
                <li>Cansandra</li>
            </ul>
        </li>
    </ul>
</body>
</html>
```
### Q5

```HTML
<a href="https://google.com" target="_blank">google</a>
```
### Q6

```HTML
<form action="https://example.com" method="GET">
  <div>
      <p>Employee Status:</p>
      <input type="radio" id="salaried" name="emp_status" value="salaried">
      <label for="salaried">Salaried</label><br>
      <input type="radio" id="business" name="emp_status" value="business">
      <label for="business">Own business</label><br><br>
      <input type="submit" value="Submit">
  </div>
</form>
```
