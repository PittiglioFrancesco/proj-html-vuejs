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
                <span class="number"><i class="fas fa-phone-alt"></i>1-800-555-555</span>
            </div>
        </div>
    <!-- sistemare il numero  -->
    </div>

    <div class="row corsi">
        <div class="col-6 left">
            <div class="card">
                <img src="../assets/new-corner.jpg" alt="triangle">
                <h2 class="text-center">Courses</h2>
                <span class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</span>
                <div class="d-flex justify-content-center"><button class="text-uppercase">course information</button></div>
            </div>
        </div>
        <div class="col-6 right">
            <div class="row">
                <div class="col-4">
                    <img src="../assets/courses-passplus-200x200.jpg" alt="">
                    <h4 class="text-center">Pass Plus</h4>
                    <div class="d-flex justify-content-center"><button class="corso-button">learn more</button></div>
                </div>

                <div class="col-4">
                    <img src="../assets/course-intensive-200x200.jpg" alt="">
                    <h4 class="text-center">Intensive Course</h4>
                    <div class="d-flex justify-content-center"><button class="corso-button">learn more</button></div>
                </div>

                <div class="col-4">
                    <img src="../assets/courses-instructor-200x200.jpg" alt="">
                    <h4 class="text-center">Instructors</h4>
                    <div class="d-flex justify-content-center"><button class="corso-button">learn more</button></div>
                </div>
            </div>
        </div>
    </div>

    <div class="row rates">
        <div class="col-4">
            <div class="card d-flex justify-content-center">
                <div class="circle d-flex justify-content-center align-items-center"><span>95%</span></div>
                <span class="text-center text-uppercase">pass rate</span>
            </div>
        </div>

        <div class="col-4">
            <div class="card d-flex justify-content-center">
                <div class="circle d-flex justify-content-center align-items-center"><span>100%</span></div>
                <span class="text-center text-uppercase">referral rate</span>
            </div>
        </div>

        <div class="col-4">
            <div class="card d-flex justify-content-center">
                <div class="circle d-flex justify-content-center align-items-center"><span>0%</span></div>
                <span class="text-center text-uppercase">accident rate</span>
            </div>
        </div>

    </div>

    <div class="row instructors">

        <div class="row align-items-center">
            <div class="col-8 left">
                <h2>Your Instructors</h2>
                <h4>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</h4>
            </div>
            <div class="col-4 right">
                <span class="button text-uppercase text-center">more about us</span>
            </div>
        </div>
    <!-- sistemare il numero  -->
    </div>

    <div class="row instructor-card">
        <div class="col">
            <div class="card d-flex justify-content-center">
                <img src="../assets/instructor-mikehart.jpg" alt="mikehart" class="my-3">
                <h3 class="text-center">Mike Hart</h3>
                <i></i><i></i><i></i>
                <span class="text-center">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</span>
            </div>
        </div>

        <div class="col john">
            <div class="card d-flex justify-content-center">
                <img src="../assets/instructor-johnsmith.jpg" alt="johnsmith" class="my-3">
                <h3 class="text-center">John Smith</h3>
                <i></i><i></i><i></i>
                <span class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
            </div>
        </div>

        <div class="col">
            <div class="card">
                <img src="../assets/instructor-angelahart.jpg" alt="angelahart" class="my-3">
                <h3 class="text-center">Angela Hart</h3>
                <i></i><i></i><i></i>
                <span class="text-center">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</span>
            </div>
        </div>

    </div>

    <div class="row justify-content-center testimonial">
        <h2 class="text-center">Testimonials</h2>
        <p class="text-center">Here’s what our happy drivers had to say about our services: </p>
        <img src="../assets/testimonial-kelly.png" alt="testimonial">
        <p class="text-center">Avada Driving School really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
        <span class="bold text-center">{{ array[index].nome }}</span>
        <span class="circle" @click="carousel(0)"></span>
        <span class="circle" @click="carousel(1)"></span>
        <span class="circle" @click="carousel(2)"></span>
        <span class="circle" @click="carousel(3)"></span>
        <span class="circle" @click="carousel(4)"></span>
    </div>

    <div class="row news">
        <div class="contenitore">
            <div class="row"><h2 class="text-center">Latest News</h2></div>
            <div class="row">
                <div class="col-6">
                <img src="../assets/blogpost-10and2-700x441.jpg" alt="news">
                <h3 class="text-center">What Car to Start With?</h3>
                <h6 class="text-center">February 7th, 2019 | <span>0 Comments</span></h6>
                <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing</p>
            </div>
            <div class="col-6">
                <img src="../assets/blog-choosecar-700x441.jpg" alt="news">
                <h3 class="text-center">What Car to Start With?</h3>
                <h6 class="text-center">February 7th, 2019 | <span>0 Comments</span></h6>
                <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing</p>
            </div>
            </div>
            <div class="row"><div class="button-news"><button class="text-uppercase">more from the blog</button></div></div>
        </div>
        <img src="../assets/latestnews-bottom.png" alt="bottom">
    </div>

    <div class="newsletter row">
        <h2 class="text-center">Sign up to our Newsletter</h2>
        <form action="">
            <input type="text" placeholder="">
            <div class="d-flex justify-content-center"><button class="text-uppercase">subscribe</button></div>
            <p class="text-center">(We do not share your data with anybody, and only use it for its intended purpose)</p>
        </form>
    </div>

    

  </div>
</template>

<script>
export default {
    data(){
        return{
            index: 0,
            array: [
            {
                img: "testimonial-grant.png",
                nome: "Grant Harvey"
            },
            {
                img: "testimonial-harold.png",
                nome: "Harold Green"
            },
            {
                img: "testimonial-kate.png",
                nome: "Kate Lewis"
            },
            {
                img: "testimonial-kelly.png",
                nome: "Kelly Johnson"
            },
            {
                img: "testimonial-sophia.png",
                nome: "Sophia Jones"
            }
            ]
        }
    },
    methods: {
        carousel(number){
            this.index = number;
        }
    }

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
        box-shadow: 10px 10px 10px 5px rgba($color: #000000, $alpha: 0.1);

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
    padding: 50px 5% 70px;
    background-image: url("../assets/horizontal-cta-background.jpg");
    background-size: cover;
    .left{

        h2, h4{
            color: #fff;
        }
    }
    .right{

        .number{
            padding-left: 50%;
            font-size: 25px;
            text-align: right;
            color: #fff;
            i{
                margin-right: 20px;
            }
        }
    }
}

.corsi{
    margin: 80px 0;
    padding: 0 5%;
    background-image: url("../assets/promise-background.jpg");
    background-size: cover;  
    .left{
        .card{
            border: 0px;
            border-radius: 10px;
            position: absolute;
            top: 1400px;
            width: 500px;
            box-shadow: 10px 10px 10px 5px rgba($color: #000000, $alpha: 0.1);
            // padding: 80px 40px;
            img{
                width: 30%;
            }

            h2{
                
            }
            span{
                color: gray;
                margin: 10px 40px;
            }
            div{
                margin-bottom: 30px;
                button{
                    margin: 20px 40px;
                    background-color: #79b27b;
                    color: white;
                    padding: 10px 20px;
                    border: 0;
                    border-radius: 30px;
                }
            }
        }
        
    }

    .right{
        margin-bottom: 30px;
        .row{
            .col-4{
                h4{
                    color: #90ABBC;
                    margin-top: 30px;
                }
                div{
                    margin-top: 10px;
                    button{
                        border: 3px solid #90ABBC;
                        border-radius: 30px;
                        background-color: #fff;
                        padding: 10px 20px;
                        text-transform: uppercase;
                        color: #90ABBC;
                    }
                }
            }
        }

    }
}

.rates{
    padding: 0 5%;
    .col-4{
        .card{
            width: 90%;
            height: 400px;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            border-top: 5px solid #79b27b;
            box-shadow: 10px 10px 10px 5px rgba($color: #000000, $alpha: 0.1);
            .circle{
                width: 100px;
                height: 100px;
                border: 10px solid gray;
                border-radius: 50%;
                margin: 0 36% 30px;
                color: gray;
            }
        }
    }
}

.instructors{
    padding: 50px 5% 70px;
    .left{
        h4{
            color: gray;
            line-height: 2;
        }
    }
    .right{

        .button{
            background-color: #79b27b;
            padding: 10px 100px;
            color: white;
            border-radius: 30px;
        }
    }
}

.instructor-card{
    padding: 0 5%;
    .col{
        .card{
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            border-bottom-left-radius: 10px;
            border-bottom-right-radius: 10px;
            border-top: 5px solid #79b27b;
            padding: 30px 30px 60px;
            bottom: -50px;
            box-shadow: 10px 10px 10px 5px rgba($color: #000000, $alpha: 0.1);
            img{
                width: 90%;
                margin-left: 20px;
            }
        }
    }
}

.testimonial{
    padding: 10% 20%;
    background-image: url(../assets/testimonial-background.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    color: gray;
    img{
        width: 30%;
        border-radius: 50%;
        margin-bottom: 50px;
        margin-top: 10px;
    }
    .bold{
        font-weight: bold;
        font-size: 25px;
    }
    .circle{
        width: 1px;
        padding: 5px 5px;
        border: 1px solid gray;
        border-radius: 50%;
        margin: 10px 5px;
    }
}

.news{
    padding: 0 5% 5%;
    background-image: url(../assets/latestnews-background.jpg);
    .contenitore{
        padding: 50px 100px;
        background-color: #fff;
        border-top-left-radius: 50px;
        border-top-right-radius: 50px;
        border-top: 5px solid #79b27b;
        .col-6{
            width: 50%;
            img{
                width: 100%;
            }
        }
        .button-news{
            display: flex;
            justify-content: center;
            button{
                margin-top: 50px;
                border-radius: 30px;
                padding: 10px 20px;
                border: 0;
                background-color: #79b27b;
                color: #fff;
            }
        }
    }
    img{
        margin: 0;
        padding: 0;
    }
}

.newsletter{
    padding: 0 20%;
    background-image: url(../assets/newsletter_background.jpg);
    background-size: cover;
    h2{
        margin-top: 50px;
        margin-bottom: 20px;
    }
    form{
        input{
            height: 40px;
            width: 100%;
            border: 1px solid gray;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        button{
            border: 0px;
            color: white;
            background-color: #79b27b;
            border-radius: 30px;
            padding: 10px 20px;
            margin-bottom: 20px;
        }
        p{
            margin-bottom: 50px;
        }
    }
}

</style>