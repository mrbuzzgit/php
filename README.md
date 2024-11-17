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

## Section A - Basic Programming Instructions ([Link](https://github.com/mrbuzzgit/php/tree/851d14f9c0b166c2e0b8838d0184bdcc569da5a2/section_a))

1. INSTALLING SOFTWARE AND FILES
2. DOWNLOADING THE SAMPLE CODE
3. HOW PHP PAGES MIX HTML & PHP CODE
    
### 1. Variables, Expressions & Operators
#### VARIABLES
Variables store data that can change (or vary) each time a PHP page is requested. They use a name to represent a value that can change.
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


### 2. Control Structures
### 3. Functions
### 4. Object & Classes


