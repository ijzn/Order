<template>
    <div class="leftNav">
        <ul id="leftNav">
            <li>
                <i class="icon iconfont icon-dache"></i>
                <div>打车</div>
            </li>
            <li>
                <i class="icon iconfont icon-dache"></i>
                <div>外卖</div>
            </li>
            <li>
                <i class="icon iconfont icon-dache"></i>
                <div>快餐</div>
            </li>
            <li>
                <i class="icon iconfont icon-dache"></i>
                <div>SPA</div>
            </li>
            <li>
                <i class="icon iconfont icon-dache"></i>
                <div>快递</div>
            </li>
            <li>
                <i class="icon iconfont icon-dache"></i>
                <div>足疗</div>
            </li>
        </ul>
    </div>
</template>

<script>
export default{
    name:'leftNav',
    data () {
        return {
            
        }
    }
};
</script>

<style scoped>
.leftNav{
    color:#fff;
    font-size:20px;
    background-color: #1D8ce0;
    float:left;
    width:5%;
    height:100%;
}
.iconfont{
    font-size:50px;
}
.leftNav ul{
    padding:0px;
    margin: 0px;
    height:100%
}
.leftNav li{
    list-style: none;
    text-align: center;
    border-bottom:1px solid #20a0ff;
    height:100px;
    display:flex;
    justify-content: center;
    align-items: center;
    flex-direction:column;
}
</style>