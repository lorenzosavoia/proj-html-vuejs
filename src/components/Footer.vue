<template>
<footer class="container-fluid">
  <div class="row main-footer justify-content-center align-items-center">
    <div class="col-8 d-flex justify-content-between align-items-center">
      <div class="col-2 flex-fill">
        <div class="nex-gen-logo"> 
          <h1><span class="">NEX</span>GEN</h1>
        </div>
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
        <button type="button" class="btn button-2">READ MORE</button>
      </div>
      <div 
        class="col-2 box-about flex-fill  ms-3 me-3"
        v-for="(element,index) in footer"
        :key="index"
      >
        <h3>{{element.title}}</h3>
        <ul class="m-0 p-0">
          <li
            v-for="(links,index) in element.link"
            :key="index = 'a'"
          ><i class="fas fa-chevron-right me-2"></i>{{links}}</li>
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
        <span><i class="far fa-copyright"></i>2020 NEXGEN is Proudly Powered by <span class="green">Codings</span></span>
      </div>
    </div>

  </div> 
</footer>
</template>

<script>
export default {
  name:'Footer',
  data(){
    return{
      footer:[
        {
        title:'About',
          link:[
              'Institutional',
              'Social & Evetens',
              'Innovation',
              'Environment',
              'Technology',
          ],
        },    
        {
        title:'Service',
          link:[
            'Audit & Assurance',
            'Financial Advisory',
            'Analytics',
            'Middle Marketing',
            'Legal Consulting',
            'Regulatory Risk',
          ],
        },    
        {
        title:'Support',
          link:[
            'Responsibility',
            'Terms of Use',
            'About Cookies',
            'Privacy Policy',
            'Accesibility',
            'information',
          ],
        }    
      ]

      
      
    }
  }
    
}
</script>

<style lang="scss">
.nex-gen-logo{     
  h1{
      color: #b8b7bb;
      font-size: 1.3em;
      font-weight: 700;
  }
  span{
      display: inline-block;
      background-color: #0e272d;
      color: #01a6a6;
      border-top-left-radius:30px;
      border-bottom-left-radius: 30px;
      padding:.4em .2em .4em 1.2em;
      margin-right: .2em;
  }
}
.green{
  color: #0a5863;
}
.second-footer{
  height: 75px;
  background-color: #0d0d11;
  color: rgb(121, 117, 117);
}
ul{
  list-style: none;
  li{
    color: #b8b7bb;
  }

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
  height: 260px;
}

.button-2{
  color: white !important;
  border: 1px solid #1c918e !important;
}

.button-2:hover{
    background-color:#1c918e !important;
    color: white !important;
}
</style>
