
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
        <div class="container bg-black col-10  mt-4 rounded py-3" >
            <div class="row">
            <div class="col-12 bg-black py-3 ">
                <!-- <div class="col-10"> -->
            <input class="col-12 py-2" type="text" id="inp" placeholder="enter the number">
                <!-- </div> -->
                <!-- <div class="col-3">
            <input type="button" name="" class="col-12 rounded-5  cl   " id="back" onclick="back()" placeholder="button" value="Del">
                </div> -->
            </div>
            </div>
            <div class="row  ">
                <div class="col-3 bg-secondary rounded  py-3 ">
                    <input type="button" class="col-12 rounded-5  cl    "   name="" id="one" onclick="fun1()" placeholder="button" value="1">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" class="col-12 rounded-5  cl "  name="" id="two" onclick="two1()" placeholder="button" value="2">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" class="col-12 rounded-5  cl "  name="" id="three" onclick="three1()" placeholder="button" value="3">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="clear" onclick="clear1()" placeholder="button" value="clear">
                </div>
                <!-- <div class="col-32 bg-secondary rounded  py-3">
              <input type="button" name="" class="col-12 rounded-5  cl   " id="back" onclick="back()" placeholder="button" value="Del">
                </div> -->
            </div>
 <div class="row mt-3">
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" class="col-12 rounded-5  cl "  name="" id="four" onclick="four1()" placeholder="button" value="4">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="five" onclick="five1()" placeholder="button" value="5">
                </div>
                 <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="six" onclick="six1()" placeholder="button" value="6">
                </div>
                 <div class="col-3 bg-secondary rounded  py-3">
            <input type="button" name="" class="col-12 rounded-5  cl   " id="back" onclick="back()" placeholder="button" value="Del">
                </div>
            </div>
             <div class="row mt-3">
                 <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "   id="seven" onclick="seven1()"  placeholder="button"  value="7">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" class="col-12 rounded-5  cl "  name="" id="button" onclick="fun()" placeholder="button" value="8">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="nine" onclick="nine1()" placeholder="button" value="9">
                </div>
                 <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="minus" onclick="minus1()" placeholder="button" value="-">
                </div> 
            </div>
            <div class="row mt-3">
               <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="zero" onclick="zero1()" placeholder="button" value="0">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="mul" onclick="mul1()" placeholder="button" value="*">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="divide" onclick="divide1()" placeholder="button" value="/">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="plus" onclick="plus1()" placeholder="button" value="+">
                </div>
            </div>
             <div class="row mt-3">
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="doub" onclick="double()" placeholder="button" value="00">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <button class="col-12 rounded-5  cl "  id="par" onclick="par()" value="">%</button>
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="dot" onclick="dot()" placeholder="button" value=".">
                </div>
                <div class="col-3 bg-secondary rounded  py-3">
                    <input type="button" name="" class="col-12 rounded-5  cl "  id="equal" onclick="equal1()" placeholder="button" value="=">
                    <!-- <input type="button" name="" class="col-12 rounded-5  cl "  id="par" onclick="par()" placeholder="button"value="%"> -->
                </div>
            </div>
    </div>
    <script src="calculator.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    
