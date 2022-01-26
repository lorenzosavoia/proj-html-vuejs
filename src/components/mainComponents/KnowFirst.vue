<template>
<div class="row know-first justify-content-center align-items-center">
            <div class="col-7">
                <div class="row">
                    <div class="col-6">
                        <div class="about-text mb-4">NEWSLETTER</div>
                        <h1><span class="backgorund">Know</span> First</h1>
                        <span class="about-description pe-5">follow closely and receive content about our company and the news of the currente market</span>
                    </div>
                    <div class="col-6">
                        <input type="email" class="form mb-4" id="" placeholder="email">
                        <input type="text" class="form mb-4" id="" placeholder="Name">
                        <button class="btn btn-primary me-3" type="submit">SUBSCRIBE</button>
                    </div>
                </div>
            </div>
        </div>  
</template>

<script>
export default {
    name:'KwonFirst'
}
</script>

<style lang="scss">
.know-first{
    height: 370px;
    background-image: url(../../assets/bg-1.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
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
}
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
</style>