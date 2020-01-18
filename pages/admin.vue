<template>
 <div class="whole">
    <div data-v-32a8d6f4="" class="prev">
        <a data-v-32a8d6f4="" href="/draft" class="nuxt-link-active">
            <i data-v-32a8d6f4="" class="fa fa-arrow-left"><pseudo:before></pseudo:before></i> 戻る
        </a>
    </div>
   
 <div class="login">
    <form data-v-32a8d6f4="" class="form">
        <div data-v-32a8d6f4="" class="field">
            <label data-v-32a8d6f4="" class="label">LoginID</label>     
                <input data-v-32a8d6f4="" class="input">
        </div> 
        <div data-v-32a8d6f4="" class="field">
        <label data-v-32a8d6f4="" class="label">Password</label> 
                <input data-v-32a8d6f4="" class="input">
        </div> 
                    <br data-v-32a8d6f4=""> 
                            <div data-v-32a8d6f4="" class="field">
                              <button data-v-32a8d6f4="" class="button is-primary is-outlined">ログイン</button>
                            </div>
    </form>
 </div>

 </div>


</template>

<script>
    export default {}
</script>

<style>

.whole{
    background-image: linear-gradient(to right top, #000000, #1a1419, #25232f, #273547, #1c495b, #1c495b, #1c495b, #1c495b, #273547, #25232f, #1a1419, #000000);
    min-height: 100vh;
}

.prev{
    padding-top: 30px; 
    padding-left: 25px; 
}

.nuxt-link-active{
    font-size: 15px; 
    font-family: "Courier New", Courier, monospace; 
    color: #d1e8e2  ; 
    text-shadow: 0 0 15px #116466;
    padding-left: 20px;
    padding-top: 50px; 
}

.login{
    width: 350px; 
    box-sizing: border-box;
    margin: 0 auto; 
    box-sizing: inherit;
    padding-top: 250 px; 
}



.label {
    cursor: default;
    color: #d1e8e2;
    text-shadow: 0 0 15px #116466;
    margin-top: 40px;
}


</style> 