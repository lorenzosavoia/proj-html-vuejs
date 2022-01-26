<template>
<div class="row justify-content-center process-managment align-items-center relative">
    <div class="col-6 text-center">
        <span class="header-green mb-4">OUR BUSINESS AREAS</span>
        <span class="background me-2">Process</span>
        <div class="header-title">  Management</div>
        <div class="text-grey mt-4">We work with innovative methodologies to ensure that the entire reformatting process is done from start to finish as planned</div>
    </div>
    
    <div class="col-12 level">
        <div class="row justify-content-center align-items-center">
            <div class="col-2 text-center">
                <span class="round">01</span>
                <h3 class="title-managment">Collection of information</h3>
                <span class="text-grey">lorem ipsum dolor sit amet consecturet</span>
            </div>
            <div class="col-2 text-center">
                <span class="round">02</span>
                <h3 class="title-managment">Stategic plannig</h3>
                <span class="text-grey">lorem ipsum dolor sit amet consecturet</span>
            </div>
            <div class="col-2 text-center">
                <span class="round">03</span>
                <h3 class="title-managment">Assignement of responsibil</h3>
                <span class="text-grey">lorem ipsum dolor sit amet consecturet</span>
            </div>
            <div class="col-2 text-center">
                <span class="round">04</span>
                <h3 class="title-managment">Formatting process</h3>
                <span class="text-grey">lorem ipsum dolor sit amet consecturet</span>
            </div>
            <div class="col-2 text-center">
                <span class="round">05</span>
                <h3 class="title-managment">Continuity formalization</h3>
                <span class="text-grey">lorem ipsum dolor sit amet consecturet</span>
            </div>
        </div>
    </div>
    <div class="absolute"></div>
</div>
</template>

<script>
export default {
    name:'Process'
}
</script>

<style lang="scss">
.process-managment{
    height: 550px;
    background-color: white;
    padding: 2em 0;
    .round{
        color: #058183;
        background-color: #cce3de;
        border-radius: 50%;
        display: inline-block;
        font-size: 1em;
        font-weight: 700;
        padding: .5em 0.7em;
    }
    .title-managment{
        font-weight: 700;
        padding: .8em;
    }
}
.relative{
    position: relative;
}
.level{
    z-index: 99;
}
.absolute{
    position: absolute;
    left: 0;
    bottom: 239px;
    width: 100%;
    height: 5px;
    background-color:#cce3de;
    z-index: 0;
}


</style>