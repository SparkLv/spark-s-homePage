<template>
    <section class="animated">
        <h2 style="float:left;margin-left:100px;text-decoration:underline;color:#fff">我的经历 ></h2>
        <img class="me" src="http://ozgnrqjtt.bkt.clouddn.com/me.jpg" alt="me">
        <div class="detail">
            <hr>
        </div>
        <div class="page1">
            <div style="margin-left:9%;width:10px;height:10px;border-radius:50%;background-color:yellow;margin-top:5px;"></div>
            <div style="padding:5px;width:15%;margin-left:2%;background-color:#FFA500;color:#fff">
                <h3>2016年3月始</h3>
                <div class="refrence">
                    开始接触前端，感觉相见恨晚，遂利用学校图书馆资源，网上视频、博客教程，学习前端基础，并且勤加练习
                </div>
            </div>
        </div>
         <div class="page2">
            <div style="margin-left:9%;width:10px;height:10px;border-radius:50%;background-color:yellow;margin-top:5px;"></div>
            <div style="padding:5px;width:15%;margin-left:2%;background-color:#FFA500;color:#fff;">
                 <h3>2017年4月-10月</h3>
                <div class="refrence">
                    通过校招来到上海，并在波导信息技术有限公司实习，由于已经打好了基础，进入公司，在没有培训的情况下，
                    便开始进入项目之中，全职实习
                </div>
            </div>
        </div>
        <div class="page3">
            <div style="margin-left:9%;width:10px;height:10px;border-radius:50%;background-color:yellow;margin-top:5px;"></div>
            <div style="padding:5px;width:15%;margin-left:2%;background-color:#fff;background-color:#FFA500;color:#fff">
                <h3>2017年7月</h3>
                <div class="refrence">
                    在安徽大学毕业，并且取得学士学位，毕业证书。
                    在上海波导信息技术有限公司转正，参与更多的项目之中，工作表现优秀，上进
                </div>
            </div>
        </div>
        <div class="page4">
            <div style="margin-left:9%;width:10px;height:10px;border-radius:50%;background-color:yellow;margin-top:5px;"></div>
            <div style="padding:5px;width:15%;margin-left:2%;background-color:#fff;background-color:#FFA500;color:#fff">
                <h3>2017年11月</h3>
                <div class="refrence">
                    公司经营不善，濒临倒闭。
                    公司提出解除合同，待业期间制作个人主页，并继续学习前端技能
                </div>
            </div>
        </div>
        <div class="page5">
            <div style="margin-left:9%;width:10px;height:10px;border-radius:50%;background-color:yellow;margin-top:5px;"></div>
            <div style="padding:5px;width:15%;margin-left:2%;background-color:#fff;background-color:#FFA500;color:#fff">
                <h3>Futrue</h3>
                <div class="refrence">
                    未完待续，敬请期待！
                </div>
            </div>
        </div>
        <div class="advice">
          完整内容，请使用PC观看，谢谢！
        </div>
    </section>
</template>

<script>
export default {
  name: "blogHome",
  data() {
    return {};
  },
  mounted() {},
  components: {},
  methods: {}
};
</script>


<style scoped>
section {
  width: 100%;
  height: 100%;
  position: absolute;
  background-color: #cd69c9;
  overflow: hidden;
}
li {
  float: left;
}
.advice {
  position: absolute;
  bottom: 100px;
  width: 100%;
  display: none;
}
@keyframes move {
  20% {
    left: 12%;
  }
  40% {
    left: 30%;
  }
  60% {
    left: 48%;
  }
  80% {
    left: 66%;
  }
  100% {
    left: 84%;
  }
}
@keyframes move2 {
  20% {
    width: 19%;
  }
  40% {
    width: 37%;
  }
  60% {
    width: 55%;
  }
  80% {
    width: 73%;
  }
  100% {
    width: 100%;
  }
}
@keyframes pagemove {
  from {
    opacity: 0;
    top: 70%;
  }
  to {
    opacity: 1;
    top: 30%;
  }
}
.me {
  width: 100px;
  height: 150px;
  position: absolute;
  left: 0;
  top: 10%;
  animation: move 6s;
  animation-fill-mode: forwards;
}
.detail {
  position: absolute;
  top: 30%;
  animation: move2 6s;
  animation-fill-mode: forwards;
}
.page1 {
  position: absolute;
  left: 6%;
  width: 100%;
  top: 30%;
  animation: pagemove 2s;
  animation-fill-mode: forwards;
}
.page2 {
  position: absolute;
  left: 24%;
  width: 100%;
  opacity: 0;
  animation: pagemove 2s;
  animation-delay: 1s;
  animation-fill-mode: forwards;
}
.page3 {
  position: absolute;
  left: 42%;
  width: 100%;
  opacity: 0;
  animation: pagemove 2s;
  animation-delay: 2s;
  animation-fill-mode: forwards;
}
.page4 {
  position: absolute;
  left: 60%;
  width: 100%;
  opacity: 0;
  animation: pagemove 2s;
  animation-delay: 3s;
  animation-fill-mode: forwards;
}
.page5 {
  position: absolute;
  left: 78%;
  width: 100%;
  opacity: 0;
  animation: pagemove 2s;
  animation-delay: 4s;
  animation-fill-mode: forwards;
}
@media screen and (max-width: 768px) {
  @keyframes move {
  20% {
    left: 12%;
  }
  40% {
    left: 30%;
  }
  60% {
    left: 48%;
  }
  80% {
    left: 66%;
  }
  100% {
    left: 74%;
  }
}
  .refrence {
    display: none;
  }
  .me {
    width: 80px;
    height: 120px;
  }
  .page1 {
    width: 80%;
  }
  .page1 h3 {
    font-size: 16px;
  }
  .page2 {
    width: 80%;
  }
   .page2 h3 {
    font-size: 16px;
  }
  .page3 {
    width: 80%;
  }
   .page3 h3 {
    font-size: 16px;
  }
  .page4 {
    width: 80%;
  }
   .page4 h3 {
    font-size: 16px;
  }
   .page5 h3 {
    font-size: 16px;
  }
  .advice{
    display: block;
  }
}
</style>