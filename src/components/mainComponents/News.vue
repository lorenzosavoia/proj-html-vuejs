<template>
<div class="row latest-news justify-content-center align-items-center">
            <div class="col-8 header-excellence">
                <span class="header-green mb-3">OUR EDITORIAL CONTENT</span>
                <div class="header-title">Latest </div>
                <span class="background ms-2"> News</span>
                <div class="d-flex align-items-center mt-4">
                    <span class=" text-grey w-75">every week publish content about what is best in the buisiness world</span>
                    <div class="w-25 d-flex justify-content-end">
                        <button class="btn btn-primary me-3" type="submit">SEE ALL</button>
                    </div>
                </div>
            </div>
            <div class="col-8">
                <div class="row justify-content-between">
                    <div class="col-3 img-news d-flex d-flex align-items-end">
                        <div class="div mb-4 ms-3 text-news">
                            increasing creativity is possible for everyone
                        </div>
                    </div>
                    <div class="col-3 img-news-2 d-flex d-flex align-items-end">
                        <div class="div mb-4 ms-3 text-news">
                            increasing creativity is possible for everyone
                        </div>
                    </div>
                    <div class="col-3 img-news-3 d-flex d-flex align-items-end">
                        <div class="div mb-4 ms-3 text-news">
                            increasing creativity is possible for everyone
                        </div>
                    </div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    name:'News'
}
</script>

<style lang="scss">
.latest-news{
    height: 650px;
    color: white;
    padding: 4em 0em;
    .img-news{
        width: 300px;
        height: 300px;
        background-image: url(../../assets/news-1.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        border-radius: 5px;
    }
    .img-news-2{
        width: 300px;
        height: 300px;
        background-image: url(../../assets/news-2.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        border-radius: 5px;
    }
    .img-news-3{
        width: 300px;
        height: 300px;
        background-image: url(../../assets/news-3.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        border-radius: 5px;
    }
    .text-news{
        font-weight: 700;
        font-size: 1.4em;
    }
}

</style>