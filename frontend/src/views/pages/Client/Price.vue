<template>
    <div id="price">
        <h1>Bảng Giá</h1>
        <div class="row">
            <div class="col-4 col-s-12">
                <router-link to="/price-sum"><img src="../../../assets/imgs/price/price-1.jpg" width="100%" alt=""></router-link>
                <div class="infor-price">
                    <p>PHÒNG 50 -60 Người</p>
                    <div class="p50">
                        <div class="col-6">
                            <p>Ngày thường</p>
                            <p>Thứ 7, CN</p>
                            <p>Buổi tối phụ thu</p>
                        </div>
                        <div class="col-6">
                            <p>250k/h</p>
                            <p>350k/h</p>
                            <p>+90k/h</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-4 col-s-12">
                <router-link to="/price-sum"><img src="../../../assets/imgs/price/price-2.jpg" width="100%" alt=""></router-link>               
                <div class="infor-price">
                    <p>PHÒNG 50 -60 Người</p>
                    <div class="p50">
                        <div class="col-6">
                            <p>Ngày thường</p>
                            <p>Thứ 7, CN</p>
                            <p>Buổi tối phụ thu</p>
                        </div>
                        <div class="col-6">
                            <p>200k/h</p>
                            <p>30k/h</p>
                            <p>+50k/h</p>
                        </div>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>
<style scoped>
.infor-price p {
    padding-left: 2%;
}
#price .row {
    overflow: hidden;
}
#price .row .col-4 {
    margin-top: 2%;
    margin-right: 2%;
    background-color: white;
    width: 33.33%;
    display: inline-block;
    float: left;
}
 .p50 .col-6:nth-child(1) {
    box-sizing: border-box;
    padding-left: 3%;
    display: inline-block;
    width: 50%;
    float: left;
}

.p50 .col-6:nth-child(2) {
    display: inline-block;
    box-sizing: border-box;
    padding-left: 25%;
}
@media only screen and (max-width: 868px) {
#price .col-4.col-s-12 {
    width: 100%;
  }
}
</style>