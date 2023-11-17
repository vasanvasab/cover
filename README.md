# Ex.06 Book Front Cover Page Design
## Date:13.11.2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(255, 208, 0);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(background.jpg);
            background-size: cover;
            position: relative;
        }

        .insight {
            color: white;
        }

        .booktitle {
            font-family: 'Algerian', cursive;
            font-size: 30px;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            text-align: center; /* Center the subtitle text */
            position: relative;
            top: 40px;
        }

        .author {
            font-family: 'Algerian', cursive;
            position: absolute;
            bottom: 10px;
            right: 10px;
            color: rgb(0, 221, 255);
            font-size: 25px;
        }

        .mypic {
            position: relative;
            top: 270px; 
            left: 295px;
            width: 150px;
            height: 150px;
            border-radius: 50%; 
            background-size: cover;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">EXPERT INSIGHT</div>
        <div class="booktitle">
            <h1>THE HUNTER</h1>
        </div>
        <div class="author">
            KAVIVARSHINI
        </div>
        <div class="mypic">
            <img src="my.jpg" width="100" height="100" alt="">
        </div>
    </div>
</body>
</html>

```


## OUTPUT:
![OUTPUT-6](https://github.com/vasanvasab/cover/assets/143481226/f79d0f15-547e-450c-aa29-639e4c1ead4e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
