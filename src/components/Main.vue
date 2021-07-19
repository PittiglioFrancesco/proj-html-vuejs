<template>
  <div>

    <!-- behind the wheel -->
    <div class="row self-container">
        <div class="col-6">
            <h1>Get Behind The Wheel</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</p>
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh.</span>
        </div>
        <div class="col-6">
            <div class="card">
                <h1 class="text-center">First Lesson Free!</h1>
                <p class="text-center">When you make a block booking with us your first lesson is included free.</p>
                <form action="">
                    <input class="d-block" type="text" placeholder="Your Name*">
                    <input class="d-block" type="text" placeholder="Email*">
                    <input class="d-block" type="text" placeholder="Telefono">
                    <input class="d-block" type="text" placeholder="Location">
                    <div class="d-flex justify-content-center">
                        <button class="button-form">Request a callback</button>
                    </div>
                </form>
            </div>
        </div>
    </div>

    

  </div>
</template>

<script>
export default {

}
</script>

<style>

.self-container{
    padding: 0 5%;
}

.card{
    background-color: whitesmoke;
    padding: 40px 20px;
    position: absolute;
    top: 500px;
}

h1{
    color: #79b27b;
}

p{
    max-width: 500px;
    color: gray;
}

input{
    background-color: #F7F7F7;
    border: 1px solid lightgray;
    border-radius: 5px;
    width: 100%;
    margin-bottom: 30px;
    padding: 10px 5px;
}

.button-form{
    background-color: #79b27b;
    color: #fff;
    border: 0px;
    padding: 10px 20px;
    border-radius: 20px;
    text-transform: uppercase;
}

</style>