<template>
  <div>
    <div class="navbar-brand">
    <a class="navbar-item" href="http://localhost:3000/test">
      <img src="https://cdn2.iconfinder.com/data/icons/education-4-1/256/Homework-512.png" width="50" height="500">
    </a>
    </div> 

    <div class="n">
    <h1>Do your Homework</h1>
    </div>

    <div class="k">
      "Do your homework" will assist students with their homework. However, we cannot guarantee whether the answers/grades you will recieve for your homework to be perfect.
    </div>

    <div class="columns">
  <div class="column">
    <a href ='http://localhost:3000/test'>
    <button type="button">Home</button>
    </a>
  </div>
  <div class="column">
    <a href='http://localhost:3000/information'>
  <button type="button"> Contact Information</button>
  </a>
  </div>
  <div class="column">
    <a href="http://localhost:3000/pack">
  <button type="button">Packs</button>
  </a> 
  </div>
  </div>

  </div>
</template>

<script>
export default{
  methods:{
    hello: function(a,b){
      alert("a+b");
    },
  }
}

</script>

<style scoped>
.n{
    color:black;
     background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQsT2bjQpqaanqr2gJAZFVav85LJWoUiBeWP7Y0Ue-Fwr4Gii1k);
    text-align: center;
    font-size: 30px;
    padding: 20px;
}

.k{
    color:#000000;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQsT2bjQpqaanqr2gJAZFVav85LJWoUiBeWP7Y0Ue-Fwr4Gii1k);
    text-align: center;
    font: 20px;
    padding:15px;
    padding-bottom: 30px;
}

.navbar-brand{
    text-align:left
}

.columns {
    background-color: #FFC0CB ;
    color:#000000;
    text-align: center; 
}

.column{
    color: #000000;
    border-width: 2px; 
    border-color: black; 
    padding-bottom: 30px; 
}

button{
  padding: 15px; 
  background-color: #ffffff;
  color: black; 
  width: 200px; 
}

</style>