<template>
  <div class="wrap">
        <header class="header">
           <div class="box">
                <img src="https://static2.cnodejs.org/public/images/cnodejs_light.svg" alt="">
                <div class="inp">
                    <i class="iconfont icon-fangdajing"></i>
                </div>
                <ul class="list">
                    <li>首页</li>
                    <li style="width: .82rem;height: .4rem;">新手入门</li>
                    <li>API</li>
                    <li>关于</li>
                    <li>注册</li>
                    <li>登录</li>
                </ul>
            </div>
        </header>
        <main class="main">
            <div class="bo">
                <div class="bo_dv">
                    <p>全部</p>
                    <p>精华</p>
                    <p>分享</p>
                    <p>问答</p>
                    <p>招聘</p>
                    <p>客户端测试</p>
                </div>
                <ul class="listt">
                    <li class="lis">
                        <img src="https://avatars.githubusercontent.com/u/2842176?v=4&s=120" alt="">
                        <p class="p1">置顶</p>
                        <p class="p2">5 月 23 日Node 地下铁武汉热干面专场来啦，开启报名中</p>
                        <p class="p3">2天前</p>
                    </li>
                    <li class="lis">
                        <img src="https://avatars.githubusercontent.com/u/2842176?v=4&s=120" alt="">
                        <p class="p1">置顶</p>
                        <p class="p2">5 月 23 日Node 地下铁武汉热干面专场来啦，开启报名中</p>
                        <p class="p3">2天前</p>
                    </li>
                    <li class="lis">
                        <img src="https://avatars.githubusercontent.com/u/2842176?v=4&s=120" alt="">
                        <p class="p1">置顶</p>
                        <p class="p2">5 月 23 日Node 地下铁武汉热干面专场来啦，开启报名中</p>
                        <p class="p3">2天前</p>
                    </li>
                    <li class="lis">
                        <img src="https://avatars.githubusercontent.com/u/2842176?v=4&s=120" alt="">
                        <p class="p1">置顶</p>
                        <p class="p2">5 月 23 日Node 地下铁武汉热干面专场来啦，开启报名中</p>
                        <p class="p3">2天前</p>
                    </li>
                    <li class="lis">
                        <img src="https://avatars.githubusercontent.com/u/2842176?v=4&s=120" alt="">
                        <p class="p1">置顶</p>
                        <p class="p2">5 月 23 日Node 地下铁武汉热干面专场来啦，开启报名中</p>
                        <p class="p3">2天前</p>
                    </li>

                    <li class="lis">
                        <img src="https://avatars.githubusercontent.com/u/2842176?v=4&s=120" alt="">
                        <p class="p1">置顶</p>
                        <p class="p2">5 月 23 日Node 地下铁武汉热干面专场来啦，开启报名中</p>
                        <p class="p3">2天前</p>
                    </li>
                    
                </ul>
            </div>

            
        </main>
        
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
* {
	margin: 0;
	padding: 0;
}

li {
	list-style: none;
}

html,
body,
.wrap {
	height: 100%;
}

body {
	font-size: 16px;
	background-color: #e1e1e1;
}

.wrap {
	width: 375px;
	display: flex;
	flex-direction: column;
}

.header {
	width: 375px;
	height: 156px;
	background-color: #444;
	.box{
        width: 328px;
        height: 146px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;
        img{
            height: 28px;
            width: 120px;
        }
        .inp{
            width: 233px;
            height: 26px;
            background: #888;
            border-radius: 20px;
        }
        .list{
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            font-size:13px;
            color: #ccc;
           
            li{
              width: 56px;
              height: 40px;
              display: flex;
              align-items: center;
              justify-content: center;
            }
        }
    }
}








.main {
	width: 100%;
    margin: 20px 0;
}

.bo{
    width: 365px;
    margin: 0 auto;

}
.bo_dv{
    height: 60px;
    background: #f6f6f6;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    color: #80bd01;
}
.listt{
    .lis{
        display: flex;
        justify-content: space-around;
        width: 365px;
        height: 50px;
        align-items: center;
        background: #ffffff;
        img{
            width: 30px;
            height: 30px;
        }
        
        .p1{
            font-size: 12px;
            color: #ffffff;
            width: 32px;
            height: 18px;
            background: #80bd01;
        }
        .p2{
            font-size: 14px;
            width: 213px;
            height: 29px;
            overflow: hidden;
            white-space: nowrap;
            text-overflow: ellipsis;
        }
        .p3{
            font-size: 12px;
            color: #778087;
        }
    }
}



</style>