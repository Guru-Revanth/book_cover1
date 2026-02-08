# Ex.05 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
  <title>Book Cover</title>
  <style>
    body {
      background-color: #eee;
      font-family: Arial, sans-serif;
    }
    .cover {
      width: 400px;
      height: 600px;
      background: linear-gradient(to bottom right, #a30000, #b3d766);
      color: white;
      padding: 30px;
      position: relative;
      margin: 50px auto;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }
    .title {
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      margin-top: 40px;
      line-height: 1.5;
    }
    .subtitle {
      text-align: center;
      margin-top: 20px;
      font-style: italic;
      font-size: 14px;
    }
    .edition {
      margin-top: 60px;
      font-weight: bold;
    }
    .author {
      position: absolute;
      bottom: 30px;
      left: 30px;
      font-weight: bold;
    }
    .college {
      position: absolute;
      bottom: 30px;
      right: 30px;
      font-weight: bold;
    }
    .photo {
      position: absolute;
      right: 30px;
      top: 359px;
      border: 3px solid white;
      width: 100px;
      height: 120px;
    }
    .photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="title">
      A Brief History Of Time<br>
      
    </div>
    <div class="subtitle">
        from the big bang to black holes
    <div class="edition">second edition</div>
    <div class="photo">
      <img src="stephen hawking.jpg" alt="Author">
    </div>
    <div class="author">Stephen hawking</div>
    <div class="college">SEC</div>
  </div>
</body>
</html>
```

# OUTPUT:

<img width="1542" height="941" alt="image" src="https://github.com/user-attachments/assets/0e406044-789b-4cdd-be46-18400c5b4d05" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
