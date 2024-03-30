<img src="https://res.cloudinary.com/monday-platform/image/upload/v1687508245/board_views_images/logos/1687508245192_546ddd78-f911-1be8-ace5-26033aa68ede.png" width="100">

# Loop HTML-5

###  HTML structure - المبنى الاساسي
```html
<html>
    <head>
    
    </head>
    <body>


    </body>
</html>
```
------------------------------------------------
### ```<h1> - <h6>``` Headers عنوان 
```html
<h1> LOOP </h1>  اكبر عنوان
<h2> LOOP </h2>
<h3> LOOP </h3>
<h4> LOOP </h4>
<h5> LOOP </h5>
<h6> LOOP </h6> اصغر عنوان
```
------------------------------------------------
### ```<p>``` Paragraph فقرة 
```html
<p> This is my first paragraph in html </p>
```
------------------------------------------------
### ```<img>``` Image صورة 
```html
<img src="رابط الصورة"/>
```
------------------------------------------------
### ```<a>``` Add Link اضافة رابط
```html
<a href="رابط الموقع"> 
    Press Me
</a>
```
------------------------------------------------

### ```<ol> + <ul>``` Lists قائمة  
###### ```<ul>```  قائمة غير مرتبه
```html
<ul>  
    <li>Vanilla</li>     · Vanilla
    <li>Milk</li>        · Milk
    <li>Chocolate</li>   · Chocolate
    <li>Eggs</li>        · Eggs
</ul>  
```

###### ```<ol>```  قائمة مرتبه
```html
<ol> 
  <li> Break Eggs </li>        1. Break Eggs
  <li> Mix Eggs & Milk </li>   2. Mix Eggs & Milk
  <li> Add Chocolate </li>     3. Add Chocolate 
  <li> Add Vanilla </li>       4. Add Vanilla
</ol> 

```
------------------------------------------------
### ```<div>``` Divide
```html
<div id="LoopDiv">
    <h1> Loop <h1>
    <p> Loop is a social-driven hi-tech incubator that invests in people</p>
    <img src="رابط الصورة"/> 
</div>

```
------------------------------------------------
------------------------------------------------
------------------------------------------------
#### CSS
1. Create new file "style.css"
2. Add ```<link>``` inside the ```<head>```
 ```<link rel="stylesheet" href="style.css">```
3. Add your styling
```css
body 
{
  background-color: blue;
}

h1
{
    color: red;
    font-size: 20px;
}
```
