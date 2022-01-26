<template>
<footer class="container-fluid">
  <div class="row main-footer justify-content-center align-items-center">
    <div class="col-8 d-flex justify-content-between align-items-center">
      <div class="col-2 flex-fill">
        <h2>NEXGEN</h2>
        <span>A functional HTML template for corporate & business</span>.
        <div class="phone me-3 mb-2 mt-2">
          <i class="fas fa-phone-alt me-2"></i>
          <span>+1 (305) 1234-56789</span>
        </div>
        <div class="e-mail me-3 mb-2">
          <i class="fas fa-envelope me-2"></i>
          <span>hello@example.com</span>
        </div>
        <div class="e-mail me-3 mb-2">
          <i class="fas fa-map-marker-alt me-2"></i>
          <span>Main Avenue, 987</span>
        </div>
        <button type="button" class="btn btn-outline-success">READ MORE</button>
      </div>
      <div class="col-2 box-about flex-fill">
        <h3>About</h3>
        <ul class="m-0 p-0">
          <li><i class="fas fa-chevron-right me-2"></i>The company</li>
          <li><i class="fas fa-chevron-right me-2"></i>Institutional</li>
          <li><i class="fas fa-chevron-right me-2"></i>Social & Evetens</li>
          <li><i class="fas fa-chevron-right me-2"></i>Innovation</li>
          <li><i class="fas fa-chevron-right me-2"></i>Environment</li>
          <li><i class="fas fa-chevron-right me-2"></i>Technology</li>
        </ul>
      </div>
      <div class="col-2 box-about flex-fill me-5 ms-5">
        <h3>Services</h3>
        <ul class="m-0 p-0">
          <li><i class="fas fa-chevron-right me-2"></i>Audit & Assurance</li>
          <li><i class="fas fa-chevron-right me-2"></i>Financial Advisory</li>
          <li><i class="fas fa-chevron-right me-2"></i>Analytics</li>
          <li><i class="fas fa-chevron-right me-2"></i>Middle Marketing</li>
          <li><i class="fas fa-chevron-right me-2"></i>Legal Consulting</li>
          <li><i class="fas fa-chevron-right me-2"></i>Regulatory Risk</li>
        </ul>
      </div>
      <div class="col-2 box-about flex-fill">
        <h3>Support</h3>
        <ul class="m-0 p-0">
          <li><i class="fas fa-chevron-right me-2"></i>Responsibility</li>
          <li><i class="fas fa-chevron-right me-2"></i>Terms of Use</li>
          <li><i class="fas fa-chevron-right me-2"></i>About Cookies</li>
          <li><i class="fas fa-chevron-right me-2"></i>Privacy Policy</li>
          <li><i class="fas fa-chevron-right me-2"></i>Accesibility</li>
          <li><i class="fas fa-chevron-right me-2"></i>information</li>
        </ul>
      </div> 
    </div>
  </div>
  <div class="row second-footer justify-content-center align-items-center">
    <div class="col-8 d-flex justify-content-between align-items-center">
      <div class="col-5">
        <span>Enjoy the low price. We are traking any inention of piracy.</span>
      </div>
      <div class="col-4">
        <span><i class="far fa-copyright"></i>2020 NEXGEN is Proudly Powered by <span>Codings</span></span>
      </div>
    </div>

  </div> 
</footer>
</template>

<script>
export default {
    name:'Footer',
    
}
</script>

<style>
.second-footer{
  height: 75px;
  background-color: #0d0d11;
  color: rgb(121, 117, 117);
}
ul{
  list-style: none;

}
.main-footer{
  background-color:#111117;
  height: 600px;
  color: lightgrey;
  font-size: 1em;
}
.box-about{
  background-color: #19191f;
  padding: 2em 2em 2em 3em;
  border-radius: 10px;
}
</style>
