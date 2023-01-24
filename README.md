# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:

Create a new django project and app.

### Step 2:

Type code in views and urls.py

### Step 3:

create HTML files according to your places

### Step 4:

Give deatils about that places in html file

### Step 5:

Run the server

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>MAT MAP</title>
    </head>
    <body>
        <img src="/static/images/map.png" width ="490" height="500" usemap="#matmap" alt>
        <MAP name="matmap">
             <AREA shape="RECT" coords="232,285,262,304"
                   href = "/vadakunathantemple/" Title="vadakunathantemple" alt>
             <AREA shape="RECT" coords="345,77,400,99"
                   href = "/nehrupark/" Title="nehrupark" alt>
             <AREA shape="RECT" coords="266,399,226,383"
                   href = "/thrissurground/" Title="thrissurground" alt>
             <AREA shape="RECT"  coords="467,240,463,265"
                   href = "/swarajround/"   Title="swarajround" alt>
             <AREA shape="RECT"  coords="262,14,236,17"
                   href = "/northtower/"  Title="northtower" alt>
         
        </MAP>

    </body>
</html>
```


## Output:
![thrissurmap](https://user-images.githubusercontent.com/118753139/214388131-835a7a8e-0984-4e9b-bf49-b56408c6d2f8.png)
![htm](https://user-images.githubusercontent.com/118753139/214388155-9b21823c-316d-457b-bf4b-939ec9732a66.png)


## Result:
Thus a website is developed to display details about the places around my house.
