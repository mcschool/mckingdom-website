<template>
<div>
<TestComponent></TestComponent>

<article class="message">
 
  <div class="message-body">
   Welcome to "Do your homework"! Are you stressed with constant homework and projects stressing you out!? Well, no worries, for this site will help any homework that can be done online (if worksheet, please send the online copy so we can proide answers)for everyone's benefit. The first 2 months only costs $10 dollars (after that, it will be $25). 
  </div>


</article>



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


.contact{
    text-align:center;
    padding:20px;
}
ul{
    padding:30px;
    text-align:center;

}
</style>