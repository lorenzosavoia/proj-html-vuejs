<template>
<div class="row excellence-service justify-content-center align-items-center">
            <div class="col-8">
                <div class="row">
                    <!-- header -->
                    <div class="col-12 header-excellence">
                        <span class="header-green">OUR BUSINESS AREAS</span>
                        <div class="header-title">Excellence in </div>
                        <span class="background ms-2"> Service</span>
                        <div class="d-flex align-items-center mt-4">
                            <span class=" text-grey w-75">we are leaders in providing consultancy services with a ser a contting-edge techologis and team of experiencerd and renowned and professional, these are some oprtion that you can hire.</span>
                            <div class="w-25 d-flex justify-content-end">
                                <button class="btn btn-primary me-3" type="submit">SEE ALL</button>
                            </div>
                        </div>
                    </div>
                    <!-- header -->
                    <div class="col-12">
                        <div class="row justify-content-between">
                            <!-- primo box -->
                            <div class="col-3 box-excellence flex-fill">
                                <div class="d-flex justify-content-between">
                                    <div class="icon "><i class="fas fa-network-wired"></i></div>
                                    <div class="icon pointer"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="mb-3 mt-3 title-box">Audit & Assurance</h2>
                                <span class="text-box">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div>
                             <!--secondo box  -->
                            <div class="col-3 box-excellence-mid flex-fill">
                                <div class="d-flex justify-content-between">
                                    <div class="icon "><i class="fas fa-briefcase"></i></div>
                                    <div class="icon pointer"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="mb-3 mt-3 title-box">Financial Advisory</h2>
                                <span class="text-box">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            <!-- terzo box -->
                            <div class="col-3 box-excellence flex-fill">
                                <div class="d-flex justify-content-between">
                                    <div class="icon "><i class="fas fa-chart-bar"></i></div>
                                    <div class="icon pointer"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="mb-3 mt-3 title-box">Analytics and M&A</h2>
                                <span class="text-box">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div>
                             <!--quarto box  -->
                            <div class="col-3 box-excellence flex-fill">
                                <div class="d-flex justify-content-between">
                                    <div class="icon"><i class="fas fa-plane"></i></div>
                                    <div class="icon pointer"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="mb-3 mt-3 title-box">Middle Marketing</h2>
                                <span class="text-box">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div>
                             <!--quinto box  -->
                            <div class="col-3 box-excellence-mid flex-fill">
                                <div class="d-flex justify-content-between">
                                    <div class="icon "><i class="fas fa-globe"></i></div>
                                    <div class="icon pointer"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="mb-3 mt-3 title-box">Legal Consulting</h2>
                                <span class="text-box">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div>
                             <!--sestobox  -->
                            <div class="col-3 box-excellence flex-fill">
                                <div class="d-flex justify-content-between">
                                    <div class="icon "><i class="fas fa-inbox"></i></div>
                                    <div class="icon pointer"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="mb-3 mt-3 title-box">Regulatory Risk</h2>
                                <span class="text-box">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            
                            
                        </div>
                    </div>
                      
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name:'Excellence'
}
</script>

<style lang="scss">
.btn-primary{
    background-color:#058183 ;
    border-color:#058183; 
    color: white;
    display: block;
    padding: .5em 1.4em;  
}

.excellence-service{
    height: 850px;
    background-color: #eef4ed;
}
    // header

    .header-green{
        color: #009f93;
        font-weight: 600;
        font-size: 1em;
        display: block;
    }
    .header-title{
        color: #21333e;
        font-size: 3em;
        font-weight: 800;
        display: inline-block;
    }
    .background{
        color: #058183;
        background-color: #cce3de;
        border-radius: 5px;
        display: inline-block;
        font-size: 3em;
        font-weight: 800;
        padding: 0 .3em;
    }
    .text-grey{
        color: #939aa3;
    }
    // header
    
    .box-excellence{
        background-color: white;
        padding: 2em;
        margin: 1em 0;
        border-radius: 10px;
    }
    .box-excellence-mid{
        background-color: white;
        padding: 2em;
        margin: 1em 2em;
        border-radius: 10px;
    }
    .icon{
        font-size: 2em;
        color: #058183;
    }
    .title-box{
        font-size: 1.7em;
        font-weight: 700;
        color: #2a3740;
    }
    .text-box{
        color: #939aa3;
        font-size: 1.1em;
    }  
</style>