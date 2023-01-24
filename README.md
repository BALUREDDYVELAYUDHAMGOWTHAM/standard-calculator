# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
After cloning the repository url,crete a folder called static.


### Step 2:
In that folder create another folder called html

### Step 3:
in htmlfolder create a file called calc.html,in calc.html write the html code.

### Step 4:
Run the code by giving command python3 manage.py runserver 0:8000.

### Step 5:
Then copy the code and appload the screenshots in README.md.At last, git push your information.
### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```python
calci.html
<!DOCTYPE html>
<html>
    <head>
        <title>SEC Demo on Calculator</title>
        <style type="text/css">
        table{
            border: 1px solid orange(17, 16, 16);
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid orange(15, 13, 13);
            padding: 20px 30px;
            font-size: 32px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:lightseagreen;
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:limegreen;">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="clearall" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```

## OUTPUT:

![image](images/calculator.png)

## HTML validation

![image](images/validatehtml.png)

## CSS validation

![image](images/cssvalidation.png)

## Result:
I successfully designed a web application for a standard calculator.