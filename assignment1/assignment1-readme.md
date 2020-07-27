#readme
TOC


### checklist:

- [ ] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [X] DOCTYPE
- [x] html
- [x]  head
- [ ] title
- [x] body
- [ ] main  
- [ ] h1
- [ ] h2
- [ ] h3
- [ ] p
- [ ] div
- [ ] span
- [ ] ul
- [ ] li
- [ ] img
- [ ] header - height 200px 
- [ ] section
- [ ] article
- [ ] nav
- [ ] aside
- [ ] footer - height 150px
- [ ] clear float class
- [ ] outer - 1020px max

### Initial Layout:


```
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>news</title>
<link href="css/style.css" rel="stylesheet" type="text/css">
</head>
<body>
<header></header>
<nav></nav>
<main>
</main>
  
<footer>  
</footer>  
</body>

</html>
```


### Wireframe Layout:

```
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>news</title>
<link href="css/style.css" rel="stylesheet" type="text/css">
</head>
<body>
<header>Affluent Bilby Classifieds</header>
<nav>-Home- -Blog- -Projects- -About- -Open Source-</nav>
<main>
<aside> </aside> 
  <section>
    <div></div><article></article><aside></aside>
  </section>  
    
</main>
  
<footer>  
</footer>  
</body>

</html>
```

### Adding a navigation bar

```
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>news</title>
<link href="css/style.css" rel="stylesheet" type="text/css">
</head>
<body>
<header>Affluent Bilby Classifieds</header>
<nav class="navbar navbar-inverse">
  <ul class="nav navbar-nav">
    <li><a href="#">Home</a></li>
    <li><a href="#">Projects</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Open-Source</a></li>
  </ul>
</nav>  
<main>
<aside> </aside> 
  <section>
    <div></div><article></article><aside></aside>
  </section>  
    
</main>
  
<footer>  
</footer>  
</body>

</html>
```


references
https://www.w3schools.com/bootstrap/bootstrap_navbar.asp
