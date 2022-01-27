<template>
  <div class="jumbotron row pt-3">
        <!-- <img src="..\assets\bg-6.jpg" alt=""> -->
        <div class="row nav-bar row justify-content-center align-items-center">
            <!-- navbar -->
            <div class="col-8 d-flex justify-content-between">
                <div class="nex-gen-logo"> 
                    <h1><span class="">NEX</span>GEN</h1>
                </div>
                <div class="nav-contacts d-flex align-items-center">
                    <ul class="d-flex">
                        <li
                            v-for="(link, index) in links"
                            :key="index"
                        ><a href="">{{link}}</a></li>
                    </ul>
                    <button class="btn button-1" type="submit">GET IN TOUCH</button>
                </div>
                <!-- navbar -->
            </div>
        </div>
        <!-- form -->
        <div class="row justify-content-center jumbo-form">
            <div class="col-8">
                <div class="row justify-content-end">
                    <div class="col-5">
                        <div class="row">
                            <div class="col-12 mb-3">
                                <div class="fusion-text">FUSION & ACQUISTION</div>
                                <h1 class="title-form">Insurance</h1>
                                <h1 class="title-form">Consulting</h1>
                            </div>
                            <div class="col-6 d-flex align-items-center">
                                <input type="text" class="form" id="" placeholder="Name">
                            </div>
                            <div class="col-6 d-flex align-items-center">
                                <input type="email" class="form" id="" placeholder="Email">
                            </div>
                            <div class="col-6 d-flex align-items-center mt-2">    
                                <input type="text" class="form" id="" placeholder="phone">
                            </div>
                            <div class="col-6 d-flex align-items-center mt-2">
                                <select class="select" aria-label="Default select example">
                                    <option selected>More info</option>
                                    <option value="1">Azienda</option>
                                    <option value="2">Libero professionista</option>
                                    <option value="3">Privato</option>
                                </select>
                            </div>
                            <div class="col-12 mt-2">
                                <button class="btn button-1 me-3" type="submit">GET IN TOUCH</button>
                                <button type="button" class="btn button-2-jumbo">READ MORE</button>
                            </div>
                        </div>
                    </div>
                </div>   
            </div>
        </div>
        <!-- form -->
    </div>
</template>

<script>
export default {
    name:'Jumbotron',
    data() {
        return{
            links:[
                'HOME',
                'ABOUT',
                'SERVICES',
                'PROCESS',
                'TEAM',
                'BLOG',    
            ],
        }
    },
}
</script>

<style lang="scss">
.jumbotron{
    background-image: url('~@/assets/bg-6.jpg');
    height: 700px;
    .nex-gen-logo{
        
        h1{
            color: #283944;
            font-size: 1.2em;
           font-weight: 700;
        }
        span{
            display: inline-block;
            background-color: #bfdcdd;
            color: #07a8a8;
            border-top-left-radius:30px;
            border-bottom-left-radius: 30px;
            padding:.4em .1em .4em 1.2em;
        }
    }
    .nav-bar{
        height: 40px;
        
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
                    color: #283944;
                    font-weight: 500;
                } 
            }       
        }
    }
    .jumbo-form{
        .form{
            display: block;
            width: 100%;
            padding: 0.375rem 0.75rem;
            font-size: 1rem;
            font-weight: 400;
            line-height: 1.5;
            color: #939aa3;
            background-color: #ccd1d4;
            background-clip: padding-box;
            border: 1px solid #ccd1d4;
            appearance: none;
            border-radius: 0.25rem;
            transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
        }
        .select{
            display: block;
            width: 100%;
            padding: 0.375rem 2.25rem 0.375rem 0.75rem;
            -moz-padding-start: calc(0.75rem - 3px);
            font-size: 1rem;
            font-weight: 400;
            line-height: 1.5;
            color: #939aa3;
            background-color: #ccd1d4;
            background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='%23343a40' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M2 5l6 6 6-6'/%3e%3c/svg%3e");
            background-repeat: no-repeat;
            background-position: right 0.75rem center;
            background-size: 16px 12px;
            border: 1px solid #ccd1d4;
            border-radius: 0.25rem;
            transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
            appearance: none;
        }
        .fusion-text{
            color:#4abac5;
            font-weight: 600;
        }
        .title-form{
            color: #21333e;
            font-size: 4em;
            font-weight: 800;
        }
    }
}
.button-1{
background-color: #1c918e !important; 
color: white !important;
}
.button-1:hover{
    background-color:#52bbba !important;
    color: white !important;
}
.button-2-jumbo{
color: #1c918e !important;
border: 1px solid #1c918e !important;
}

.button-2-jumbo:hover{
    background-color:#1c918e !important;
    color: white !important;
}

</style>