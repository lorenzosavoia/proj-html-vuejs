<template>
<div class="row team-of-expert justify-content-center align-items-center">
    <div class="col-8">
        <div class="row justify-content-center align-items-center">
            <div class="col-8">
                <div class="about-text mb-4">WE LIKE WHAT WE DO</div>
                <h1><span class="backgorund">Team</span> of Experts</h1>
                <span class="about-description pe-5">enthics and integrity are the bases on wihitch our professionals bvuild their careeers. thehy are foundamentrlast theat vceoamsc dalsda asdhasd</span>
                <div class="row">
                    <div 
                        class="card col-5"
                        v-for="(team,index) in teams"
                        :key="index + 'A'"
                    >
                        <div class="row">
                            <div class="col-4">
                                <div class="img-card">
                                    <img class="w-100" :src="team.img" alt="">
                                </div> 
                            </div>
                            <div class="col-8 pe-0">
                                <div class="text-card">
                                    <h3 class="mb-1">{{team.name}}</h3>
                                    <span>{{team.role}}</span>
                                    <div class="icon-card mt-1">
                                        <i class="fab fa-facebook-f me-3"></i>
                                        <i class="fab fa-twitter me-3"></i>
                                        <i class="fab fa-linkedin-in me-3"></i>
                                    </div>
                                </div>
                            </div>

                        </div>
                    </div>
                </div>
            </div>
            <div class="col-4 president-speech">
                <h2>President Speech</h2>
                <p>
                    <span class="mb-3 mt-3"> possimus doloremque? Molestias excepturi quae perferendis in mollitia exercitationem deserunt molestiae rem eveniet sapiente!</span>
                    <span class="mb-3"> doloremque? Molestias excepturi quae perferendis in mollitia exercitationem deserunt molestiae rem eveniet sapiente!</span>
                    <span class="mb-3"> ea facere sed eum nam maxime possimus doloremque? Molestias excepturi quae perferendis in mollitia exercitationem deserunt molestiae rem eveniet sapiente!</span>
                </p>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    components:'Team',
    data(){
        return{
            teams:[
                {
                    name:'David Cooper',
                    role:'CTO & CO-FOUNDER',
                    img: require('../../assets/team-1.jpg'),
                },
                {
                    name:'Oliver Jones',
                    role:'CHIEF PROCUREMENT',
                    img: require('../../assets/team-3.jpg'),
                },
                {
                    name:'Emma Lopez',
                    role:'CHIEF MARKETING',
                    img: require('../../assets/team-2.jpg'),
                },
                {
                    name:'T.Jonhson',
                    role:'CEO & PRESIDENT',
                    img: require('../../assets/team-4.jpg'),
                },
            ],
        }
    }
}
</script>

<style lang="scss">

.team-of-expert{
    height: 650px;
    background-color: #111117;
    color: white;
    
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
    
    .card{
        background-color: #111117;
        margin-top: 1em;
        margin-bottom: 1em;
        margin-right: 1em;
        .img-card{
            width: 80px;
            border-radius: 5px;
            img{
                overflow: hidden;
                width: 80px;
                border-radius: 5px;
            }
        }
        .icon-card{
            i{
                color: #058182;
                background-color: #0f2129;
                padding: .5em;
                border-radius: 50%;

            }
        }
        .text-card{
            span{
                font-size: 0.8em;
                color: lightgrey;
            }
        }
    }
    .president-speech{
        background-color: #058183;
        padding: 2em;
        border-radius: 5px;
        h2{
            font-weight: 700;
            font-size: 1.7em;
        }
        p span{
            color: lightgrey;
        }
    }
}
</style>