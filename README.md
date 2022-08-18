# sign-up-form
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=\, initial-scale=1.0">
        <title>SIGN UP FORM </title>
        <style>
         .background photo{ 
             position: relative; 
             margin: 1%;
         }
         .first-text{
            position: absolute; 
            top: 17px;
            left:50px;
         }
     .a-box {
         position: absolute; 
         top: 17px;
         left: 150px;
         display: flex;
                         flex-direction: row;
                         height: 663px;
     
         }
         .background photo{
                         background-image:img src="istockphoto-1386672169-612x612.jpg" alt="background photo" srcset=""
             height=1000px;
             width="400px";
                         background-size: cover;
                         width: 10%;
                         display: flex;
                     }
            
            body{
                font-family: Arial, Helvetica, sans-serif;
                background-color: #F9FAFB;
            }
            *{
                margin: 0;
            }
            .a-box{
                display: flex;
                flex-direction: row;
                height: 663px;
            }

            .odin-section{
               
                background-size: cover;
                width: 40%;
            }
            .odin-section img{
                width: 20%;
            }
            .odin-section p{
                color: white;
                font-size: 14px;
                text-align: center;
                margin-top: 330px;
            }
            .odin-section p>a{
                color: white;
            }
            .odinlogo-box{
                background: rgb(0, 0, 0, 0.5);
                margin-top: 160px;
                padding: 10px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .odinlogo-box>span{
                color: white;
                font-family: 'Norse-Bold';
                font-size:5rem;
            }

            .form-section{
                padding: 100px 0px;
            }
            .form-section p{
                width: 60%;
                margin-bottom: 30px;
                margin-left: 20px;
            }
            .form>div{
                display: inline-block;
                margin-left: 60px;
            }

            input{
                display: block;
            }
            h4{
                color: #1F2937;
                margin-bottom: 15px;
                margin-left: 60px;
            }
            .form{
                background-color: #fff;
                padding: 10px 0px;
                margin-bottom: 30px;
                box-shadow: 0px 2px 5px rgb(201, 201, 201);
            }
            button{
                margin-left: 60px;
                padding: 10px 40px;
                background-color: #596D48;
                border: none;
                color: white;
                border-radius: 5px;
                margin-bottom: 30px;
                box-shadow: 0px 2px 5px rgb(201, 201, 201);
            }
            label{
                display: block;
                margin-bottom: 15px;
                font-size: 14px;
                font-weight: bold;
                color: #3b3b3b;
            }
            label input{
                border: 1px solid #E5E7EB;
                padding: 5px;
                width: 100%;
                border-radius: 2px;
            }
            label input:focus{
                border: 1px solid green;
                box-shadow: 0px 2px 5px #E5E7EB;
                outline: none;
            }
            form>p a{
                color: #596D48;
            }
        </style>
    </head>
    <body  style="background-color: yellowgreen;">
        <SECtion>
         <div class="Background photo">
             <img src="istockphoto-1386672169-612x612.jpg" alt="background photo" srcset=""
             height=1000px;
             width="550px">
             <h3 class="first-text" >
                 Photo credit: Khanchit Khirisutchalual
             </h3>
        <div class="a-box">
            <div class="odin-section">
                <div class="odinlogo-box">
                    <img src="odin-lined.png" alt="odin-line-logo">
                    <span>CHISOM</span>
                </div>
                <p> </p>
            </div>
            <div class="form-section">
                <p>
                    <b>
                        This is not just online service! You know you need something like this in your lifeto help you realize your deepest dreams. 
                        <br> Sign up <i>now</i> to get started.
                    </b>
                </p>

                <p>
                    <b>
                        You <i>know</i> you want to.
                    </b>
                </p>
                <form action="#">
                    <div class="form">
                        <h4>Let's do this!</h4>
                        <div>
                            <label for="fname">FIRST NAME
                                <input type="text" name="fname" id="fname" required>
                            </label>
                            <label for="email">EMAIL
                                <input type="email" name="email" id="email" required>
                            </label>
                            <label for="password">PASSWORD
                                <input type="password" name="password" class="error" required>
                            </label>
                        </div>
                        <div>
                            <label for="phone">LAST NAME
                                <input type="text" name="lname" id="lname" required>
                            </label>
                            <label for="phone">PHONE
                                <input type="tel" name="phone" id="phone" required>
                            </label>
                            <label for="cpassword">CONFIRM PASSWORD
                                <input type="password" name="cpassword" class="error" required>
                            </label>
                        </div>
                    </div>
                    <button type="submit" id="submit">Create Account</button>
                    <p>Already have an account? <a href="#">Log in</a></p>
                </form>
            </div>
        </div>
    </body>
</html> 
