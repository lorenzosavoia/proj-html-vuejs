<template>
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
</template>

<script>
export default {
    name:'Thecompany'
}
</script>

<style lang="scss">
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
</style>