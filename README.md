AIM:
To develop a website to display the cover page design of a book

Design Steps:
Step 1:
Write your own steps here.

Step 2:
Create a static file directory and mention the changes in settings.

Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

Step 4:
Write down the code for book cover using HTML and CSS.

Step 5:
Add images and other contents using CSS record a screenshot of it.

Code:
cover.html:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title> CODING FOR BEGINNER</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("vasanth\ cv.jpg");
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:white;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BEGINNER FRIENDLY</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>EASY WAY TO LEARN CODING</h1></div>
               <h3 class="sub-text">Learn python in 6 months</h3>
                    <h3 class="sub-text">written by Dr. Vasanth</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;second
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="vasanth.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;vasanth &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>

## Output:
![Screenshot (34)](https://github.com/vtgvasanth/cover-page-design/assets/128463280/b29c396c-3f3b-46e8-a6a7-97a2ddb695df)
![Screenshot (33)](https://github.com/vtgvasanth/cover-page-design/assets/128463280/d1feb0d7-48b4-4935-9c58-1c142c27bfc4)


## Result:
program executed successfully

