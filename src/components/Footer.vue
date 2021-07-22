<template>
  <div>

      <div class="footer-info row align-items-top">
          <div class="col-3">
              <img class="logo" src="../assets/avada-drivers-logo-2x.png" alt="logo avada-driving">
              <span>Avada Driving School is the right choice for experienced drivers looking for a refresher course, or the brand new driver wanting to pass first time.</span>
          </div>

          <div class="col-3">
              <h5>CONTACT DETAILS</h5>
              <ul>
                  <li><i class="fas fa-home"></i><span>12345 North Main Street, New <span class="special">York, NY 555555</span></span></li>
                  <li><i class="fas fa-phone-alt phone-icon"></i><span>1.800.555.6789</span></li>
                  <li><i class="far fa-envelope"></i><span>info@your-domain.com</span></li>
                  <li><i class="fas fa-link"></i><span>Theme-Fusion.com</span></li>
              </ul>
          </div>

          <div class="col-3">
              <h5>COURSES</h5>
              <ul class="list3">
                  <li><i class="far fa-arrow-alt-circle-right"></i><a href="#">Pass Plus</a></li>
                  <li><i class="far fa-arrow-alt-circle-right"></i><a href="#">Intensive Course</a></li>
                  <li><i class="far fa-arrow-alt-circle-right"></i><a href="#">Automatic</a></li>
                  <li><i class="far fa-arrow-alt-circle-right"></i><a href="#">Instructor Training</a></li>
              </ul>
          </div>

          <div class="col-3">
            <img class="grid" src="../assets/footer-ad-grid.png" alt="grid">
            <div class="d-flex"><button class="text-uppercase">book now</button></div>

          </div>
      </div>

    <div class="footer-contact row">
        <div class="col-11">
            <p>© Copyright 2012 - 2021 | Avada Theme by <span class="green hover">ThemeFusion</span> | All Rights Reserved | Powered by <span class="green hover">WordPress</span></p>
        </div>
        <div class="col-1">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-youtube"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.footer-info{
    padding: 2% 5%;
    color: #fff;
    background-image: url(../assets/footer-background-color.jpg);
    .col-3{
        img.logo{
           width: 100%; 
        }
        img.grid{
            width: 50%;
        }
        button{
            margin: 15px 0;
            padding: 10px 20px;
            border: 0px;
            border-radius: 30px;
            color: white;
            background-color: #79b27b;
        }
        ul{
            list-style: none;
            li{
                span{
                    margin-left: 10px;
                    .special{
                        margin-left: 30px;
                    }
                }
            }
        }
        .list3{
            li{
                a{
                    margin-left: 10px;
                    color: #79b27b;
                    :hover{
                        color: #79b27b;
                    }
                }
            }
        }
    }
}

.footer-contact{
    padding: 10px 5%;
    background-color: #1D1E1F;
    color: #fff;
    .col-11{
        span{
            color: #79b27b;
        }
    }
    .col-1{
        i{
            margin: 0 20px;
        }
    }
}

</style>