 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website </title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
            box-sizing: border-box;
            list-style: none;
            text-decoration: none;
        }
        .contaner{
            width: 100%;
        }
        .nav{
            width: 100%;
            background-color: gray;
        }
        .nav ul{
            display: flex;
            padding: 10px;
        }
        .nav ul li a{
            padding: 10px;
            margin-left: 12px;
            color: white;
         }
        .nav ul li a:hover{
            background-color: rgb(218, 67, 67);
        }

         /* nav bar disign end  ho gya*/
         .photo{
            height: 500px;
            
            background-image: url( https://tse1.mm.bing.net/th?id=OIP.ME4spB_1_Z35k0kDZzYB1QHaE5&pid=Api&P=0&h=220);
             background-repeat: no-repeat;
            backdrop-filter:invert(10px);
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            gap: 20px;

         }
         .text{
            font-size: 5rem;
            color: rgb(255, 30, 0);
         }
         /* image part ho gya */
         .contaner1{
            width: 1100px;
            margin: auto;
            margin-top: 100px;
            
            display: flex;
            flex-direction: column;
            gap: 50px;
            justify-content: center;
            align-items: center;

         }
         .textcontant h1{
            text-align: center;
            color: red;
         }
         .textcontant p{
            text-align: center;
            padding: 30px;
         }
         .contaner2{
            width: 1100px;
            margin: auto;
            margin-top: 100px;
            display: flex;
            justify-content: space-around;
            gap: 30px;
         }
         .photo-secation{
            height: 400px;
            width: 30%;
            /* border: 1px solid; */
         }
         .photo-secation img{
            height: 100%;
            width: 100%;
         }
         .photo-secation p{
            text-align: center;
         }
         /* fonr ka css */
         .main{
            height: 250px;
            width: 450px;
            border: solid red 5px;
            margin: auto;
            margin-top: 200px;
            background-color: aqua;
            border-radius: 10px;
        }
        .main1{
            margin-left: 35px;
        }
        input{
            margin: 10px;
            border-radius: 4px;
            height: 35px;
        }
    </style>
</head>
<body>
     <h4 style="margin: 15PX; color: rgb(218, 48, 48);">LOGO YOURCOMPANYNAME</h4>
    <div class="contaner">
        <div class="nav">
            <ul>
                <li><a href="#" style="background-color: rgb(211, 85, 85);">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Service</a></li>
                <li><a href="#">Contacts</a></li>
                <li><a href="#gotam">Login</a></li>
            </ul>
        </div>
    </div>
    <!-- nav bar end ho gya yha -->
    <div class="contaner photo">
        <div class="text">
                <P>WELCOME TO</P>
                <p style="font-size: 60px; margin-left: 140px;">ROSHAN VERMA</p>
        </div>
    </div>
    <!-- image part ho gya -->
    <div class="contaner1">
        <div class="textcontant">
            <h1>OUR TEAM LEADERS</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corrupti laudantium cumque totam qui? Ex, porro provident enim eum aliquam facilis vero placeat iusto quaerat quis at voluptate nam earum soluta repudiandae optio odio aperiam, fugiat molestias accusantium praesentium saepe delectus vitae nisi? Voluptates recusandae quaerat facere amet, repellendus rem quisquam!</p>
        </div>
    </div>
    <div class="contaner2">
        <div class="photo-secation">
            <img src="https://tse2.mm.bing.net/th?id=OIP.9iP5hfylm0iGQPmS8s1cOgHaE8&pid=Api&P=0&h=220" alt="photo man">
            <p>Roshan kumar verma</p>
        </div>
        <div class="photo-secation">
            <img src=" https://tse3.mm.bing.net/th?id=OIP.51JUhK_39dVGFXUCAouzmwHaK7&pid=Api&P=0&h=220" alt=" photo man">
            <p>Satish kumar karn</p>
        </div>
        <div class="photo-secation">
            <img src="https://tse2.mm.bing.net/th?id=OIP.1H4TjeN5dyNQdkXtz-q7IwHaE2&pid=Api&P=0&h=220" alt="photo man">
            <p>Amit kumar kayatha</p>
        </div>
    </div>
    <div>
        <div class="main">
            <form action="">
                <div class="main1">
                    <label for="">Name:-</label>
                    <input type="text" placeholder="User Name"><br>
                    <label for="" id="gotam">Email:-</label>
                    <input type="email" placeholder="User Email"><br>
                    <label for="">Passw:-</label>
                    <input type="password" placeholder="User Password"><br>
                    <input type="submit" value="submit" style="margin-left: 130px ; height: 45px; width: 100px; background-color: red; color: white;">
                </div>
              
            </form>
        </div>
    </div>
    <div style="background-color: red;(233, 27, 27, 0); margin-top: 130px; text-align: center; padding: 20px; margin: bottom: 20px;">
        <h1 style="color: white;"> Desing by :- Roshan kumar verma</h1>
    </div>
</body>
</html>
