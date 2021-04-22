<template>
 <div>   
   <h1>Hello My Name is Sachin Kumar </h1>
   <p>Enter The Text Below <p>
     <p>Hello This Is a Charecter Count Text box<p>
<input v-model="message" placeholder="Enter The Text Below Charecter Count">
<p>Message is: {{ message.length }}</p>


 </div>
  



</template>
<script>
export default {
  name: 'Count',
         data(){
           return {
             message: ""
           }
         }
}
</script>



