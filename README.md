# Ex.08 Design of a Standard Calculator
## Date:24-04-2024

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
    <head>
    <title>CALCULATOR</title>
    <script>
    function fn(e){
        if (e.innerHTML == '=') {
            output. value = eval (output.value);
        }
        else if (e.id == 'back') {
            v = output. value;
            output. value = v.substring(0, v.length - 1);
        }
        else if (e. innerHTML == 'C') {
            output. value = '';
        }
        else {
            output.value += e.innerHTML;
        }
    }
    </script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    </head>
    <body>
        <div class="bg-primary mx-auto text-center " style="width: 24rem;">Name:SUBASH RReg.no: 212223230218</div>
        <div class="bg-primary row mx-auto text-center" style="width: 24rem;" >
            <div class="col-12 my-4"><input type="text" name="" id="output" style="width: 100%;height: 50px;border-radius: 25px;"></div> 
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)" >(</div> 
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)">)</div> 
            <div class="m-3 col-2 btn btn-danger squared-4" onclick="fn(this)">C</div> 
            <div class="m-3 col-2 btn btn-danger squared-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i>
            </div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">7</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">8</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">9</div> 
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)">*</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">4</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">5</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">6</div>
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)">-</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">1</div> 
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">2</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">3</div>
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)">+</div>
            <div class="m-3 col-2 btn btn-success squared-4" onclick="fn(this)">0</div>
            <div class="m-3 col-2 btn btn-success squared-4" btn-success onclick="fn(this)">.</div>
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)">%</div>
            <div class="m-3 col-2 btn btn-dark squared-4" onclick="fn(this)">/</div> 
            <div class="m-3 col-11 btn btn-warning squared-4" onclick="fn(this)">=</div>
        </div>
    </body>
</html>

```
## OUTPUT:
![Screenshot 2024-04-29 135734](https://github.com/subashr1702/Calc/assets/147139828/f88e6933-bd00-4732-bfd9-da0be3078625)
![Screenshot 2024-04-29 135734](https://github.com/subashr1702/Calc/assets/147139828/4b5005fd-4970-41d5-99a7-af4eb469bf84)


## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
