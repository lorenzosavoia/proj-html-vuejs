<template>
  <main>
    <div class="container-fluid">
        <!-- the company -->
        <div class="row the-company justify-content-center">
            <div class="col-8 d-flex align-items-center">
                <div class="row align-items-center">
                    <div class="col-6 about-company">
                        <div class="about-text mb-4">ABOUT THE NETWORK</div>
                        <h1><span class="backgorund">The</span> Company</h1>
                        <span class="about-description pe-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro earum quia iste facere unde, incidunt quos non, possimus, eaque laudantium quisquam laboriosam beatae. Sapiente harum, est ducimus quas ipsa blanditiis.</span>
                        <span class="about-description mt-3 pe-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident dolorum officia esse</span>
                    </div>
                    <div class="col-6 company-square">
                        <div class="row">
                            <div class="col-6">
                                <div class="title-icon">
                                    <span class="icon"><i class="fas fa-award"></i></span>
                                    <h5>Tradition</h5>
                                </div>
                                <span class="square-text">lorem ipsum dolor sit amet consecturet adipiscing elit.</span>
                            </div>
                            <div class="col-6">
                                <div class="title-icon">
                                    <span class="icon"><i class="fas fa-lock"></i></span>
                                    <h5>Security</h5>
                                </div>
                                <span class="square-text">lorem ipsum dolor sit amet consecturet adipiscing elit.</span>
                            </div>
                            <div class="col-6 mt-5">
                                <div class="title-icon">
                                    <span class="icon"><i class="far fa-edit"></i></span>
                                    <h5>Certificate</h5>
                                </div>
                                <span class="square-text">lorem ipsum dolor sit amet consecturet adipiscing elit.</span>
                            </div>
                            <div class="col-6 mt-5">
                                <div class="title-icon">
                                    <span class="icon"><i class="fas fa-graduation-cap"></i></span>
                                    <h5>Expertise</h5>
                                </div>
                                <span class="square-text">lorem ipsum dolor sit amet consecturet adipiscing elit.</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- the company -->
        <!-- exellence in service -->
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
                        <div class="row justify-content-around">
                            <div class="col-3 box-excellence flex-fill">
                                <div class="text-center">
                                    <div class="icon text-center"><i class="fas fa-network-wired"></i></div>
                                    <div class="icon text-center"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2 class="text-center">Audit & Assurance</h2>
                                <span class="text-center">lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            <div class="col-3 box-excellence flex-fill">
                                <div>
                                    <div class="icon"><i class="fas fa-network-wired"></i></div>
                                    <div class="icon"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2>Audit & Assurance</h2>
                                <span>lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            <div class="col-3 box-excellence flex-fill">
                                <div>
                                    <div class="icon"><i class="fas fa-network-wired"></i></div>
                                    <div class="icon"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2>Audit & Assurance</h2>
                                <span>lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            <div class="col-3 box-excellence flex-fill">
                                <div>
                                    <div class="icon"><i class="fas fa-network-wired"></i></div>
                                    <div class="icon"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2>Audit & Assurance</h2>
                                <span>lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            <div class="col-3 box-excellence flex-fill">
                                <div>
                                    <div class="icon"><i class="fas fa-network-wired"></i></div>
                                    <div class="icon"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2>Audit & Assurance</h2>
                                <span>lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            <div class="col-3 box-excellence flex-fill">
                                <div>
                                    <div class="icon"><i class="fas fa-network-wired"></i></div>
                                    <div class="icon"><i class="fas fa-arrow-right"></i></div>
                                </div>
                                <h2>Audit & Assurance</h2>
                                <span>lorem ipsum dolor sit amet consectetur adipiscing elit.</span>
                            </div> 
                            
                        </div>
                    </div>
                      
                </div>
            </div>
        </div>
        <!-- exellence in service -->
    </div>
  </main>
</template>

<script>
export default {
    name:'Main',
}
</script>

<style lang="scss" scoped>
// the company
.the-company{
    background-color: #111117;
    height: 450px;
    color: white;
    .about-company{
        .about-text{
            color: #009f93;
            font-weight: 600;
            font-size: .9em;
        }
        h1{
            font-weight: 800;
        }
        .backgorund{
            background-color:#0e272d;
            border-radius: 5px;
            font-weight: 800;
            padding: .1em 0.3em;
        }
        span{
            display: inline-block;   
        }
        .about-description{
            color: #939aa3;   
        }
    }
    .company-square{
        .icon{
            font-size: 1.5em;
            color:#009f93;
        }
        h5{
            display: inline-block;
            font-weight: 700;
            margin-left: .3em;
        }
        .square-text{
            color: #939aa3;
        }
    }
}
// the company
// excellence service
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
        padding: 1em;
        margin: 0.3em;
        border-radius: 10px;
    }
}

// excellence service

</style>