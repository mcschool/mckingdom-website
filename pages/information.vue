<template>
<div>
  
  <TestComponent></TestComponent>

<div class="field">
  <label class="label">Name</label>
  <div class="control">
    <input class="input" type="text" placeholder="Text input">
  </div>
</div>

<div class="field">
  <label class="label">Username</label>
  <div class="control has-icons-left has-icons-right">
    <input class="input is-success" type="text" placeholder="Text input" value="bulma">
    <span class="icon is-small is-left">
      <i class="fas fa-user"></i>
    </span>
    <span class="icon is-small is-right">
      <i class="fas fa-check"></i>
    </span>
  </div>
  <p class="help is-success">This username is available</p>
</div>

<div class="field">
  <label class="label">Email</label>
  <div class="control has-icons-left has-icons-right">
    <input class="input is-danger" type="email" placeholder="Email input" value="hello@">
    <span class="icon is-small is-left">
      <i class="fas fa-envelope"></i>
    </span>
    <span class="icon is-small is-right">
      <i class="fas fa-exclamation-triangle"></i>
    </span>
  </div>
  <p class="help is-danger">This email is invalid</p>
</div>

<div class="field">
  <label class="label">Subject</label>
  <div class="control">
    <div class="select">
      <select>
        <option>Select dropdown</option>
        <option>Science</option>
        <option>Math</option>
        <option>English</option>
        <option>Individual and Societies</option>
      </select>
    </div>
  </div>
</div>

<div class="field">
  <label class="label">Message</label>
  <div class="control">
    <textarea class="textarea" placeholder="Textarea"></textarea>
  </div>
</div>

<div class="field">
  <div class="control">
    <label class="checkbox">
      <input type="checkbox">
      I agree to the <a href="#">terms and conditions</a>
    </label>
  </div>
</div>

<div class="field">
  <div class="control">
    <label class="radio">
      <input type="radio" name="question">
      Yes
    </label>
    <label class="radio">
      <input type="radio" name="question">
      No
    </label>
  </div>
</div>

<div class="field is-grouped">
  <div class="control">
    <button class="button is-link">Submit</button>
  </div>
  <div class="control">
    <button class="button is-link is-light">Cancel</button>
  </div>
</div>
</div>



</template>

<script>

import TestComponent from "~/components/TestComponent"
export default{

    data (){
        const subjects=[
            {
                name: "English: 1000 yen ",
            },
         
             {
                name: "Math",
            },
           
             {
                name: "Science",
            },
      
            {
                name: "Individual and Societies",
            },
          
            
        ]
        return {
            subjects:subjects,
        }
    },
    components: { TestComponent }
    
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
}

.column{
    color: #000000;
    padding: 10px; 
    border-width: 2px; 
    border-color: black; 
}

.email {
    font-weight:bold;
    padding-left: 30px;
}

.button{
 text-align : center; 
}
.field{
    padding-top:30px;
    padding-left: 10px;
    padding-right: 10px;
    padding-bottom: 15px; 
}

</style>