# Ex.08 Design of a Standard Calculator
## Date:20/04/2024

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

## PROGRAM 
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Changing Background Color</title>
</head>
<body>
  <script>
   
    const colors = ["#ff0000", "#ffff00", "#00ff00", "#0000ff", "#800080"];

    
    function changeBackgroundColor() {
      const randomIndex = Math.floor(Math.random() * colors.length);
      const newColor = colors[randomIndex];
      document.body.style.backgroundColor = newColor;
    }

   
    changeBackgroundColor();

    
    setInterval(changeBackgroundColor, 100);
  </script>
</body>
</html>

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
<body style="padding-top: 120px;">
    <div class="row mx-auto text-center" style="width: 24rem;background-color:navajowhite;border-radius: 30px;">
        <div class="my-4 mx-auto text-center text-danger" style="width: 24rem;">KISHORE NARAYANAN (212223110023)</div>
         <div class="col-12 "><input type="text" name="" id="output" style="width: 100%;height: 50px;border-radius: 25px;"></div> ![Screenshot 2024-04-27 113839](https://github.com/KISHORENARAYANANSR/Calc/assets/148202102/466a3629-e78f-406d-ac8c-9d32f8bf09f3)

            <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)" >(</div> 
            <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div> 
            <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div> 
            <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i>
</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">7</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">8</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">9</div> 
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">*</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">4</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">5</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">6</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">-</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">1</div> 
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">2</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">3</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">+</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
<div class="m-3 col-2 btn btn-success rounded-4" btn-success onclick="fn(this)">.</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">%</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">/</div> 
<div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)">=</div>
</div>
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-27 113839](https://github.com/KISHORENARAYANANSR/Calc/assets/148202102/eaf3f0d5-effd-4a62-aedd-8ab81c28b305)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
