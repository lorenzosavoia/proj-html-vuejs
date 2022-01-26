<template>

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

</template>

<script>
export default {
    name:'Navbar'
}
</script>

<style lang="scss">
    .contacts{
        height: 45px;
        color: #bfc0ca;
        background-color: #21333e;
        font-size: .8em;
    }
</style>