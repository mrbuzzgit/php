DOWNLOAD THE CODE FOR THIS BOOK FROM

http://phpandmysql.com

# TABLE OF CONTENTS

## Introduction

1. STATIC VARIABLE VS DYNAMIC WEBSITES
2. PHP: THE LANGUAGE AND THE INTERPRETER
3. PERFORMING A TASK USING DIFFERENT DATA
4. WHAT IS A PHP PAGE?
5. WHAT IS MYSQL?
6. HISTORY OF PHP
7. HISTORY OF MYSQL
8. WHAT THIS BOOK COVERS
     - A. BASIC PROGRAMMING INSTRUCTIONS
     - B. DYNAMIC WEB PAGES
     - DATABASE DRIVEN WEBSITES
     - EXTENDING THE SAMPLE APPLICATION

## Section A - Basic Programming Instructions

1. INSTALLING SOFTWARE AND FILES
2. DOWNLOADING THE SAMPLE CODE
   - http://localhost/phpbook/section_a/intro/test.php
4. HOW PHP PAGES MIX HTML & PHP CODE
    
### 1. Variables, Expressions & Operators

#### VARIABLES
Variables store data that can change (or vary) each time a PHP page is requested. They use a **name** to represent a **value** that can change.

#### [CREATING AND ACCESSING VARIABLES](section_a/c01/variables.php)
```php
<?php 
$name  = 'Ivy';
$price = 5;
?>
<!DOCTYPE html>
<html>
  <head>
    <title>Variables</title>
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Welcome <?php echo $name; ?></h2>
    <p>The cost of your candy is 
       $<?php echo $price; ?> per pack.</p>
  </body>
</html>
```
![Screenshot 2024-11-17 120054](https://github.com/user-attachments/assets/2549ad7e-2d79-4d40-bce5-a42c4b7f52a5)

#### [UPDATING A VALUE IN A VARIABLE](section_a/c01/updating-variables.php)
```php
<?php 
$name  = 'Guest';
$name  = 'Ivy';
$price = 5;
?>
<!DOCTYPE html>
<html>
  <head>
    <title>Updating Variables</title>
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Welcome <?php echo $name; ?></h2>
    <p>The cost of your candy is 
       $<?php echo $price; ?> per pack.</p>
  </body>
</html>
```
![Screenshot 2024-11-17 120054](https://github.com/user-attachments/assets/6982909b-a145-4c47-b651-778769659bfa)

#### ARRAYS
A variable can also hold an **array** which stores a series of related values. Arrays are known as a **compound data type** because they can store more than one value.

#### ASSOCIATIVE ARRAYS
```php
$member = [
'name'    => 'Ivy',
'age'     => 32,
'country' => 'Italy',
];
```

#### [CREATING & ACCESSING ASSOCIATIVE ARRAYS](section_a/c01/associative-arrays.php)
```php
<?php 
$nutrition = [
    'fat'   => 16,
    'sugar' => 51,
    'salt'  => 6.3,
];
?>
<!DOCTYPE html>
<html>
  <head>
    <title>Associative Arrays</title>
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Nutrition (per 100g)</h2>
    <p>Fat:   <?php echo $nutrition['fat']; ?>%</p>
    <p>Sugar: <?php echo $nutrition['sugar']; ?>%</p>
    <p>Salt:  <?php echo $nutrition['salt']; ?>%</p>
  </body>
</html>
```
![Screenshot 2024-11-17 125420](https://github.com/user-attachments/assets/84ebd9e8-a23a-4d41-aee5-1ced63b8ee27)

#### INDEXED ARRAYS
```php
$shopping_list = ['bread', 'cheese', 'milk',];
```

#### [CREATING & ACCESSING INDEXED ARRAYS](section_a/c01/indexed-arrays.php)
```php
<?php 
$best_sellers = ['Chocolate', 'Mints', 'Fudge',
    'Bubble gum', 'Toffee', 'Jelly beans',];
?>
<!DOCTYPE html>
<html>
  <head>
    <title>Indexed Arrays</title>
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Best Sellers</h2>
    <ul>
      <li><?php echo $best_sellers[0]; ?></li>
      <li><?php echo $best_sellers[1]; ?></li>
      <li><?php echo $best_sellers[2]; ?></li>
    </ul>
  </body>
</html>
```
![Screenshot 2024-11-17 130022](https://github.com/user-attachments/assets/dfff6b41-afdc-4d51-b2f6-c5b1c94d9230)



### 2. Control Structures
### 3. Functions
### 4. Object & Classes


