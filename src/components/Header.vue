
<template>
  <div class="container-fluid">
    <!-- contacts -->
      <div class="row justify-content-center contacts align-items-center">
          <div class="col-8">
              <div class="row justify-content-between">
                    <div class="col-4 ">
                        <div class="text"><i class="fas fa-clock me-2"></i>Open Hours Mon-Sat - 9.00 - 18-00</div>
                    </div>  
                    <div class="col 4 d-flex justify-content-end">
                          <div class="phone me-3">
                              <i class="fas fa-phone-alt me-2"></i>
                              <span>+1 (305) 1234-56789</span>
                          </div>
                          <div class="e-mail me-3">
                              <i class="fas fa-envelope me-2"></i>
                              <span>hello@example.com</span>
                          </div>
                          <div class="social me-3">
                              <i class="fab fa-facebook-f me-3"></i>
                              <i class="fab fa-twitter me-3"></i>
                              <i class="fab fa-linkedin-in me-3"></i>
                          </div>
                    </div>
              </div>
          </div>
      </div>
    <!-- contacts -->
    <div class="jumbotron row pt-3">
        <!-- <img src="..\assets\bg-6.jpg" alt=""> -->
        <div class="row nav-bar row justify-content-center align-items-center">
            <!-- navbar -->
            <div class="col-8 d-flex justify-content-between">
                <div class="next-gen-logo"> <h1>NEXTGEN</h1></div>
                <div class="nav-contacts d-flex align-items-center">
                    <ul class="d-flex">
                        <li><a href="">HOME</a></li>
                        <li><a href="">ABOUT</a> </li>
                        <li><a href="">SERVICES</a> </li>
                        <li><a href="">PROCESS</a> </li>
                        <li><a href="">TEAM</a> </li>
                        <li><a href="">BLOG</a> </li>
                    </ul>
                    <button class="btn btn-primary" type="submit">GET IN TOUCH</button>
                </div>
                <!-- navbar -->
            </div>
        </div>
        <div class="row justify-content-center">
            <div class="col-8">
                <div class="row justify-content-end">
                    <div class="col-5">
                        <div class="row">
                            <div class="col-12">
                                <div>FUSION & ACQUISTION</div>
                                <h1 class="title-form">Insurnce</h1>
                                <h1 class="title-form">Consulting</h1>
                            </div>
                            <div class="col-6">
                                <div class="mb-3">
                                    <label for="formGroupExampleInput" class="form-label"></label>
                                    <input type="text" class="form-control" id="formGroupExampleInput" placeholder="Name">
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="mb-3">
                                    <label for="exampleFormControlInput1" class="form-label"></label>
                                    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email">
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="mb-3">
                                    <label for="formGroupExampleInput" class="form-label"></label>
                                    <input type="text" class="form-control" id="formGroupExampleInput" placeholder="phone">
                                </div>
                            </div>
                            <div class="col-6 d-flex align-items-center">
                                <select class="form-select" aria-label="Default select example">
                                <option selected>More info</option>
                                <option value="1">Azienda</option>
                                <option value="2">Libero professionista</option>
                                <option value="3">Privato</option>
                            </select>
                            </div>
                        </div>
                    </div>
                </div>   
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name:'Header',
  data(){
      return{
        //   image:"../assets/bg-6.png"
      }
  } 
}

</script>

<style lang='scss' scoped>
 @import "~bootstrap/scss/bootstrap";
 
 .container-fluid{
     .contacts{
         height: 45px;
        color: #bfc0ca;
        background-color: #21333e;
        font-size: .8em;
    }
    .jumbotron{
        background-image: url('~@/assets/bg-6.jpg');
       height: 700px;

       .nav-bar{
           height: 40px;
            
           .btn-primary{
                       background-color:#058183 ;
                       border-color:#058183; 
                       color: white;
                       display: inline-block;
                    //    height: 40px;
                   }
            ul{
                list-style: none;
                margin: 0;
                padding: 0;
                li{
                    display: flex;
                    align-items: center;
                    a{
                        text-decoration: none;
                        margin-right: 1em;
                        display: inline-block;
                        color: black;
                    } 
                }       
            }
       }
    }
 }

</style>