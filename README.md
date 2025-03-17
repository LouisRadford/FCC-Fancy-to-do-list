# FCC-Fancy-to-do-list
HTML and CSS Code

** start of undefined **

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>Styled To-Do List</title>
    <link href='styles.css' rel='stylesheet'/>
</head>
<body>
<h1>My To-Do List</h1>
<ul class='todo-list'>
<li>
    <input id="gaming" type="checkbox"/>
    <label for="gaming">Explore gaming keyboards</label>
    <ul class="sub-item">
    <li><a class="sub-item-link" href="https://www.google.com" target="_blank">Store link</a></li>
</ul>
</li>
<li>
    <input id="report" type="checkbox"/>
    <label for="report">Finish Building my Report</label>
    <ul class="sub-item">
    <li><a class="sub-item-link" href="https://www.google.com" target="_blank">View Report</a></li>
</ul>
</li>
<li>
    <input id="Phone" type="checkbox"/>
    <label for="Phone">Renew Phone Contract</label>
    <ul class="sub-item">
    <li><a class="sub-item-link" href="https://www.google.com" target="_blank">View Phones Warrenty</a></li>
</ul>
</li>
<li>
    <input id="Cake" type="checkbox"/>
    <label for="Cake">Order Monkey's Birthday Cake</label>
    <ul class="sub-item">
    <li><a class="sub-item-link" href="https://www.google.com" target="_blank">Birthday Cakes</a></li>
</ul>
</li>
    
    <ul class='sub-item'>
    </li>
</body>

</html>

** end of undefined **

** start of undefined **

body {
    background: rgba(85, 107, 47, 0.178) no-repeat;
    font-family: Arial, sans-serif;
}

#main {
    background-color: darkolivegreen;
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
    border: solid 3px mintcream;
    border-radius: 10px;
}

.todo-list {
    list-style-type: none;
}

h1 {
    text-align: center;
    margin: 20px;
    padding: 5px;
}

a {
    text-decoration: none;
    color: rgb(51, 108, 155);
}


.sub-item-link:visited {
    color: rgb(114, 170, 216);
}

.sub-item-link:hover {
    color: saddlebrown;
}

.sub-item-link:focus {
    outline: darkolivegreen;
}

.sub-item-link:active {
    color: rgb(214, 104, 25);
}


.todo-list > li {
    margin-bottom: 20px;
    margin-right: 40px;
    padding: 5px;
    border: dotted 3px ivory;
    border-radius: 10px;
    background-color: rgb(237, 243, 238)
}


** end of undefined **

