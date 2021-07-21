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
                  <li>12345 North Main Street, New York, NY 555555</li>
                  <li>1.800.555.6789</li>
                  <li>info@your-domain.com</li>
                  <li>Theme-Fusion.com</li>
              </ul>
          </div>

          <div class="col-3">
              <h5>COURSES</h5>
              <ul>
                  <li><a href="#">Pass Plus</a></li>
                  <li><a href="#">Intensive Course</a></li>
                  <li><a href="#">Automatic</a></li>
                  <li><a href="#">Instructor Training</a></li>
              </ul>
          </div>

          <div class="col-3">
            <img class="grid" src="../assets/footer-ad-grid.png" alt="grid">
            <div class="d-flex"><button class="text-uppercase">book now</button></div>

          </div>
      </div>

    <div class="footer-contact row">
        <div class="col-11">
            <p>© Copyright 2012 - 2021 | Avada Theme by <span>ThemeFusion</span> | All Rights Reserved | Powered by <span>WordPress</span></p>
        </div>
        <div class="col-1">
            <i></i>
            <i></i>
            <i></i>
            <i></i>
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
            background-color: green;
        }
    }
}

.footer-contact{
    padding: 10px 5%;
    background-color: black;
    color: #fff;
}

</style>