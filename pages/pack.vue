<template>
<div>
<TestComponent></TestComponent>

<table>
  <tr>
    <th>Pack</th>
    <th>Price</th>
    <th>Information</th>  
  </tr>
  <tr>
    <td>Worksheet Pack</td>
    <td>$10</td>
    <td>A special pack to complete all your worksheets regarding problem solving (sent in pdf form) for 2 months for only $10!</td>
  </tr>
  <tr>
    <td>Essay Pack</td>
    <td>$15</td>
    <td>Start off with a $15 pack to have your essays completed for a duration of 3 months!</td>
  </tr>

  <tr>
    <td>Math Pack</td>
    <td>$20</td>
    <td>Pack that will complete all your math homework/assessments regarding their type. Try for $20 dollars for 3 months!</td>
  </tr>

  <tr>
    <td>Physics Pack</td>
    <td>$20</td>
    <td>Do you find physics the hardest science right now? Well this pack will help with all your physic asignments for $20 for 4 months!</td>
  </tr>

    <tr>
    <td>Biology Pack</td>
    <td>$20</td>
    <td></td>
  </tr>

    <tr>
    <td>Chemistry Pack</td>
    <td>$20</td>
    <td>Start off with a $15 pack to have your essays completed for a duration of 3 months!</td>
  </tr>

    <tr>
    <td>Individual and Societies Pack</td>
    <td>$20</td>
    <td>Start off with a $15 pack to have your essays completed for a duration of 3 months!</td>
  </tr>
  
</table>



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
.message-header{
    text-align: center; 
}

table {
  border: 1px solid black;
  padding-top:30px; 
  margin-top: 30px; 
  text-align: center; 
      width:80%; 
    margin-left:15%; 
    margin-right:15%;
    margin-bottom: 20px; 
  height: 100px; 

}

tr{
  border: 1px solid black; 
  
}

th{
  padding-left: 5px; 
}

td{
 padding-left: 5px; 
}



</style>