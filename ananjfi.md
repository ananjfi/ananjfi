<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    .container div{
        margin:10px;
    }
    .container div a{
        color:black;
        border:1px solid rgb(210, 141, 250);
        background: rgb(244, 225, 255);
        border-radius: 5px;        
    }
    .container div a:hover{
        color:  rgb(183, 69, 248);
    }
    .signin-form{
        box-sizing: border-box;
        border:1px solid rgb(189, 189, 189) ;
        border-radius: 10px;
        background: rgb(240, 240, 240);
        width:50%;
        direction: rtl;
    }
    .divs{
        padding:10px;        
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
        width:auto;
        margin: 20px;   
    }
    input{
        width: 100%;
        margin:0.5rem;
    }
    input:hover{
        background: rgb(247, 247, 247);
    }
    input[type="reset"]{
        background: rgb(24, 250, 3);
    }
    input[type="submit"]{
        background:rgb(24, 250, 3);
        
    }
    input[type="reset"]:hover , input[type="submit"]:hover{
        background: rgb(22, 221, 4);
    }
    </style>
</head>
<body>
    <header class="container">
        <nav>
            <div>
                <a href="boot.html"><i class="fa fa-home"> صفحه اصلی </i></a>
            </div>
        </nav>
    </header>
    <header >
        <div class="signin-form container">
            <section class="divs">
                <forn>
                    <div>
                        <label> شماره موبایل خود را وارد کنید : </label>
                        <input type="tel"/>
                    </div>
                    <div>
                        <label> کد ارسال شده را وارد کنید : </label>
                        <input type="number"/>
                    </div>
                    <div>
                        <input type="reset" />
                        <input type="submit"/>
                    </div>
                </forn>
            </section>
        </div>
    </header>
</body>
</html>
