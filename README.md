
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
body
{
  background-color: green;
  
  margin: 60px 40px 70px 100px;
}
h1
{
  text-align: center;
  text-shadow: 4px;
  text-decoration-style: inherit;
  color: red;
  padding: 10px;

}
h2
{
  text-align: right;
  color: #988;
  border: 1px solid blue;
  margin-left: 170px;
}

.col-md-4 {
  float: left;
  width: 30%;
  padding: 10px;
  height: 300px;
  border: 1px solid black;
  margin-right: 15px;
  margin-bottom: 15px;
  overflow: auto; 
}
.col-lg-4 {
  float: left;
  width: 30%;
  padding: 10px;
  height: 300px;
  border: 1px solid black;
  margin-right: 15px;
  margin-bottom: 15px;
  overflow: auto; 
}
.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 992px) {
  .column {
    width: 100%;
  }
  body
  {
    background-color: green;
  }
  h2
  {
    text-align: right;
    color: #988;
    border: 1px solid blue;
    margin-left: 170px;
  }
}
@media screen and (min-width: 768px) and (max-width: 991px) {
  .column {
    width: 100%;
  }
   body
  {
    background-color: brown;
  }
  h2
  {
   text-align: right;
   color: #988;
   border: 1px solid blue;
   margin-left: 250px;
   border :border-box;
  }
 #tag
  {
    text-align: right;
    color: #988;
    border: 1px solid blue;
    margin-left: 625px;
    border :border-box;
  }
  h1
  {
    text-align: center;
    color: green;
    padding: 10px;
  }
  .col-md-4 
  {
    float: left;
    width: 47.8%;
    padding: 10px;
    height: 300px;
    border: 1px solid black;
    margin-right: 15px;
    margin-bottom: 15px;
    overflow: auto; 
   }
  .col-lg-4 
   {
     float: left;
     width: 97.8%;
     padding: 10px;
     height: 300px;
     border: 1px solid black;
     margin-right: 15px;
     margin-bottom: 15px;
     overflow: auto; 
   }   
   }
@media screen and (max-width: 767px) {
  .column {
    width: 100%;
  }
  h2
  {
   text-align: right;
   color: #988;
   border: 1px solid blue;
   margin-left: 170px;
  }
   body
  {
    background-color: maroon;
    text-align: center;
  }
  h1
{
  text-align: center;
  text-shadow: 4px;
  text-decoration-style: inherit;
  color: blue;
  padding: 10px;

}
  .col-md-4 {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px;
  border: 1px solid black;
  margin-right: 15px;
  margin-bottom: 15px;
  overflow: auto; 
  text-align: center;
}
  .col-lg-4 {
  float: left;
  width: 50.1%;
  padding: 10px;
  height: 300px;
  border: 1px solid black;
  margin-right: 15px;
  margin-bottom: 15px;
  text-align: center;
}
}
</style> 
</head>
<body>

<h1>Trees</h1>
<div class="container-fluid">
<div class="row">
  <div class="col-md-4" style="background-color:yellow;">
    <h2>Banyan Tree</h2>
    <p>A banyan tree is a huge, evergreen tree, commonly found in countries around Asia and it is the national tree of India. It grows in a special type of soil which provides it with the nutrients it needs in order to grow and develop. India is also the home to some of the oldest banyan trees ever. Since it is a big tree, it has a lot of branches that provide it with the support it needs. The leaves of the tree are quite big as well causing Indians to use it as plates. The wood of this lead is used to make doors, furniture and much more.</p>
  </div>
  <div class="col-md-4" style="background-color:orange;">
    <h2>Neem Tree</h2>
    <p>A neem tree is an evergreen, fast growing tree that is commonly found in Asia (especially south and Southeast Asia). In these nations, it is considered a household staple. The trunk of the neem tree is straight and rough, reaching the height of almost 100 feet. The wood of the tree is commonly used for furniture making, whereas the overall tree is used for medicinal purposes, fertilizers, and much more.</p>
  </div>
  <div class="col-lg-4" style="background-color:lightgreen;">
    <h2  id="tag">Mahogany Tree</h2>
    <p>A mahogany tree is an evergreen, medium sized tree that is native to southern Florida, but it can also found in the Caribbean islands and southern Asia. This tree has a thin trunk, which is sturdy. The color of the wood is rich brown with a few hints of light brown. The wood obtained from the trees is quite precious and is often used for furniture, boats, musical instruments, and casket.</p>
  </div>
</div>
</div>
</body>
</html>
