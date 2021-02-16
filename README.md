<!DOCTYPE html>
<html>

<head>
        <title>Google</title>  
</head>

<style>
   body {
       margin: 0;
       display: flex;
       flex-direction: column;
   }

   #nav {
       display: flex;
       justify-content: flex-end;
       margin-top: 20px;
    
   }

   #nav a {
       margin-right: 20px;

   }

   #nav a.image {
       width: 22px;
       height: 22px;
       background: red;
       border-radius: 15px;
   }

   #middle {
       flex-grow: 1;
       display: flex;
       flex-direction: column;
       justify-content: center;
       align-items: center;
   }

   #photo {
       text-align:center;
    
   }

   a {
        text-decoration: none;
   }
   
   a:hover {
        text-decoration: underline;
   }

   #searchbar {
       text-align: center;
       margin-top: 17px;
   }

   #search {
       padding-top: 13px;
       padding-bottom: 18px;
       width: 550px;
       outline: 0;
       padding-left: 15px;
       border-radius: 17px;
       border: 1px solid #bbb8b8;
   }

   #search:hover {
       box-shadow:0 0 5px 1px rgb(94, 94, 94);
   }

   #buttons { 
       display: flex;
       justify-content: center;
       margin-top: 35px;
   }

   .button {
       margin-left: 10px;
       margin-right: 10px;
       padding: 5px 5px;
       cursor: pointer;
       height: 20px ;
       border-radius:3px;
       background: rgb(248, 248, 248);
       font-family:sans-serif;
       font-weight: 300 ;
   }

   .button:hover{
       box-shadow:0 0 2px 1px rgb(99, 99, 99)
   }

   #words {
       margin-top: 40px;
       text-align: center; 
   }

   #word-style {
       font-family: sans-serif;

   }

</style>

<body>

   <div id="nav">
        <a class="link1">Gmail</a>
        <a class="link2">Images</a>
        <a class="image"></a>
   </div>

  <div id="middle">

  </div>
  <div id="photo">
        <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">
   </div>
   
<div id="searchbar">

   <input id="search" type="text">
   
</div>

<div id="buttons">
           <div class="button">
                Google Search
      </div>
           <div class="button">
                I'm Feeling Lucky
           </div>
                </div>
                </div>

<div id="words">
          <div class="word-style">
        Google offered in: 
            <a href="">Latviešu</a>
            <a href="">Lietuviešu</a>
            <a href="">Русский</a>  
           </div>
           </div>

</body>

</html>
