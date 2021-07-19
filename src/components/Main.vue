<template>
  <div>

    <!-- behind the wheel -->
    <div class="row self-container behind-wheel">
        <div class="col-6">
            <h2>Get Behind The Wheel</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</p>
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh.</span>
        </div>
        <div class="col-6">
            <div class="card">
                <h2 class="text-center">First Lesson Free!</h2>
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

    <!-- learn to drive -->
    <div class="row drive-learn">

        <div class="row align-items-center">
            <div class="col-6 left">
                <h2>Start Learning to Drive Today</h2>
                <h4>Give us a call to schedule your first driving lesson</h4>
            </div>
            <div class="col-6 right">
                <i class="fas fa-phone-alt"></i>
                <span class="number">1-800-555-555</span>
            </div>
        </div>

    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.self-container{
    padding: 0 5%;
}
.behind-wheel{
    height: 700px;
    .col-6{
        h2{
        color: #79b27b;
        margin: 40px 0;
        }

        p{
            max-width: 500px;
            color: gray;
            line-height: 2;
        }

        span{
            line-height: 2;
            color: gray;
        }
    }

    .card{
        background-color: whitesmoke;
        padding: 40px 20px;
        position: absolute;
        top: 500px;

        h2{
        color: #79b27b;
        }

        p{
        max-width: 500px;
        color: gray;
        line-height: 2;
        }

        form{

            input{
            background-color: #F7F7F7;
            border: 1px solid lightgray;
            border-radius: 5px;
            width: 100%;
            margin-bottom: 30px;
            padding: 10px 5px;
            }

            div{
                .button-form{
                background-color: #79b27b;
                color: #fff;
                border: 0px;
                padding: 10px 20px;
                border-radius: 20px;
                text-transform: uppercase;
                }
            }
        }
    }
}

.drive-learn{
    padding: 50px 5%;
    background-image: url("../assets/horizontal-cta-background.jpg");
    background-size: cover;
    .left{

        h2, h4{
            color: #fff;
        }
    }
    .right{

        .number{
            font-size: 25px;
            text-align: right;
            color: #fff;
        }
    }
}

</style>