---
title: A Beginner Guide to Bootstrap (Part 2) - Login Page
author: Mike Chan
layout: post
category: bootstrap
---


## 1. Introduction

This would be our first section in introducing how to use bootstrap in real life example. At first, putting the neccessary CDN 
link of bootstrap within ```<head> ```. If you are not familar with how to include CDN of Bootstrap into your project, please refer to the first session of this series. Then, we can start making our loging page.

## 2. Container
As per the first section, we can put everything into a container for easy management. We can start off our first version of login page as below:

```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>
<body>
    <div id="login" class="container">
        

        <form>
            <div class="form-group">
                
                <input type="email" class="form-control" id="InputEmail" placeholder="Enter email">
                <input type="password" class="form-control" id="InputPassword" placeholder="Enter password">
                
            </div>
        </form>
    </div>
        

  
</body>
```
So, in our first example, we put a form-group into a container. A form-group is a kind of components in Bootstrap. For details, you can check out more from getbootstrap.com. The codes above would shows you something like below:

<span class="image"><img src="{{ 'assets/images/bootstrap21.png' | relative_url }}" alt="" /></span>
