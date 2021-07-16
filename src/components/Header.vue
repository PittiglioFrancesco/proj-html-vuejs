<template>
  <div>

    <div class="row justify-content-between align-items-center line1 self-container">
        <div class="col"><span>We have a 95% Successful Pass Rate</span></div>
        <div class="left-text col"><i class="fas fa-phone-alt"></i><span>Give us a call to book your tuition! 1-800-555-555</span></div>
    </div>

    <div class="row bgc-black0-5">
        <nav class="self-container">
            <ul class="d-flex align-items-center">
                <li><a href="#"><img src="../assets/avada-drivers-logo-2x.png" alt=""></a></li>
                <li><a href="#">home</a></li>
                <li><a href="#">about</a></li>
                <li><a href="#">prices</a></li>
                <li><a href="#">courses<span class="new">new</span></a></li>
                <li><a href="#">locations</a></li>
                <li><a href="#">blog</a></li>
                <li><a href="#"><span class="rounded-pill">book now</span></a></li>
            </ul>
        </nav>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.self-container{
    padding: 0 10%;
}

// Header prima parte
div{
    margin: 0;
}

.line1{
    background-color: #353637;
    color: #929AA3;
    height: 50px;
    width: 100%;
}

.left-text{
    text-align: right;
}

// navbar
.bgc-black0-5{
    background-color: rgba(0, 0, 0, 0.5);
    // position: absolute;
    // width: 100%;
}

ul{
    list-style: none;
    height: 150px;
    width: 100%;
}

li{
    display: inline;
}

a{
    text-decoration: none;
    color: white;
    margin-right: 50px;
    text-transform: uppercase;
    :hover{
        text-decoration: none;
    }
}

li a img{
    margin-right: 100px;
}

.rounded-pill{
    background-color: #79b27b;
    padding: 5px 10px;
}

.new{
    background-color: #79b27b;
    padding: 1px 2px;
    font-size: 10px;
}

// sistemare il colore di new e del bottone, 
// allineare il new con courses,
// fontawesome non funziona

</style>