<template>
  <div>
  <header>
    <!--   <img src="" alt=""> -->
   <ul class="Header">
       <li >
           Products
       </li>
       <li>
           Customers
       </li>
       <li>
           Services
       </li>
       <li>
           Careers
       </li>
       <li> 
           Supports
       </li>
   </ul>
  </header>
  
  </div>
</template>

<script>
export default {

    name:'Sample',
    
}
</script>

<style closed>
*
{
margin: 0;
padding: 0;
    }
header
{
width: 100%;

}
.Header
{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    background: blue;
    font-size: 25px;
    font-weight: bold;
    padding: 20px;
    }
ul li
{
    
 list-style: none;
 text-decoration: none;
 
 color: rgb(228, 8, 8);

    }

</style>