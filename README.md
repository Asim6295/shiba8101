# shiba8101
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="calculate.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awes.7.1/css/all.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
    <style>
        body{
            background-color: aqua;
        }
    </style>
</head>
<body>
    <div class="container col-12">
        <div class="container bg-black w-50 mt-4 rounded" >
            <div class="row">
            <div class="col-12 bg-black ">
            <input class="col-12" type="text" id="inp" placeholder="enter the name">
            </div>
            </div>
              <div class="row ">
                <div class="col-3 bg-secondary rounded text-align-center">
                    <input type="button" class="cl " name="" id="one" onclick="fun1()" placeholder="button" value="1">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" class="cl" name="" id="two" onclick="two1()" placeholder="button" value="2">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" class="cl" name="" id="three" onclick="three1()" placeholder="button" value="3">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="clear" onclick="clear1()" placeholder="button"value="clear">
                </div>
            </div>
               <div class="row mt-3">
                <div class="col-3 bg-secondary rounded">
                    <input type="button" class="cl" name="" id="four" onclick="four1()" placeholder="button" value="4">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="five" onclick="five1()" placeholder="button" value="5">
                </div>
                 <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="six" onclick="six1()" placeholder="button" value="6">
                </div>
                 <div class="col-3 bg-secondary rounded">
            <input type="button" name="" class="cl " id="back" onclick="back()" placeholder="button" value="Del">
                </div>
            </div>
             <div class="row mt-3">
                 <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" class="cl" id="seven" onclick="seven1()"  placeholder="button" value="7">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" class="cl" name="" id="button" onclick="fun()" placeholder="button" value="8">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="nine" onclick="nine1()" placeholder="button" value="9">
                </div>
                 <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="minus" onclick="minus1()" placeholder="button" value="-">
                </div>   
            </div>
            <div class="row mt-3">
               <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="zero" onclick="zero1()" placeholder="button" value="0">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="mul" onclick="mul1()" placeholder="button" value="*">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="divide" onclick="divide1()" placeholder="button" value="/">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="plus" onclick="plus1()" placeholder="button" value="+">
                </div>
            </div>
             <div class="row mt-3">
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="doub" onclick="double()" placeholder="button" value="00">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <button class="cl" id="par" onclick="par()" value="">%</button>
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="dot" onclick="dot()" placeholder="button"value=".">
                </div>
                <div class="col-3 bg-secondary rounded">
                    <input type="button" name="" class="cl" id="equal" onclick="equal1()" placeholder="button"value="=">
                </div>
            </div>
          </div>
    <script src="calculator.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
