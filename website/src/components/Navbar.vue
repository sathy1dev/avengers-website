<template>
    <div class="navigation">
           <div class="navlogo">
            <img src="../assets/logo.png" alt="logo">
            </div>
        <nav class="nvabar">
         
            
            <ul>
                <li class="starting"><a href="#"></a>Home</li>
                <li><a href="#"></a>About Us</li>
                <li><a href="#"></a>Gallery</li>
                <li><a href="#"></a>Contact us</li>
            </ul>
           
            
        </nav>
    </div>
    
</template>

<style>
    .navigation
    {
        grid-column: 1 / 13;
        /*background: violet;*/
        height: 119px;
        display: flex;
        justify-content: space-between;
        align-items: center; 
        }
    
    .navlogo
    {
        height: inherit;
        }
    .navlogo > img
    {
        width: 150px;
        height: 119px;
       
    }
    .nvabar
    {
       
        grid-column: 7 / 13;
        display: flex;
        height: inherit;
        /*background: chartreuse;*/
        justify-content: center;
        align-items: center;
    }
    .start
    {
        color: rgb(185, 68, 68);
        }
    .nvabar li
    {
       display: inline-block;
      padding: 43px;
       font-family: 'Poppins';
        font-size: 20px;
        color: #f2f2f2d3;
    
   }
        
    .nvabar li:hover{
        color: white;

        }
    li:hover
    {
        border-bottom: 2px solid red;
        }

       
</style>