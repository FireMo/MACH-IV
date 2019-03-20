<template>
    <div>
      <el-container>
        <el-header>好好看看</el-header>
        <el-main>
            <div>
                1.所有人都有残暴的一面，遇到机会这一面就会冒出来
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                2.至善是可能的
                <el-radio v-model="radio" label="5">不同意</el-radio>
                <el-radio v-model="radio" label="4">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="2">有点同意</el-radio>
                <el-radio v-model="radio" label="1">同意</el-radio>
            </div>
            <div>
                3.如果不在这里或那里搞点小动作，想成功很难
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                4.只有确信符合道德时才能采取行动
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                5.每分钟都有傻子降生
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                6.决不要告诉任何人你做某事的原因，除非你另有目的
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                7.与人相处的最好方法就是说出他们想知道的事
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                8.多数人基本上是好的和善良的
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                9.在任何情况下诚实均为上策
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                10.没有任何理由对别人撒谎
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                11.一般来说，没有压力人们是不会努力工作的
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                12.总而言之地位卑微和诚实优于地位显赫和欺骗
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                13.当你求别人帮忙时，最好告知以真正的理由而不是编造更有说服力的理由
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                14.世界上成功的人大多过着清白和道德的生活
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                15.完全信任别人等于自讨苦吃
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                16.犯人与一般人最大的区别在于他们太笨被抓住了
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                17.奉承大人物的做法是明智的
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                18.各方面都优秀是可能达到的
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                19.患有不治之症的人应该有权选择无痛苦的死亡
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
            <div>
                20.多数人能轻易忘记父母的亡故，却不容易忘记财产的损失
                <el-radio v-model="radio" label="1">不同意</el-radio>
                <el-radio v-model="radio" label="2">有点不同意</el-radio>
                <el-radio v-model="radio" label="3">中立</el-radio>
                <el-radio v-model="radio" label="4">有点同意</el-radio>
                <el-radio v-model="radio" label="5">同意</el-radio>
            </div>
        </el-main>
        <el-footer>
            <p>看完了吧</p>
            <p v-if="radio">You selected: {{radio}}</p>
        </el-footer>
      </el-container>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                radio: [],
            }
        }
    }
</script>

<style>
  body {
    background-color: #fff;
  }

  .el-header, .el-footer {
    background-color: #fff;
    color: #333;
    text-align: center;
    line-height: 60px;
  }

  /*.el-aside {*/
    /*background-color: #D3DCE6;*/
    /*color: #333;*/
    /*text-align: center;*/
    /*line-height: 200px;*/
  /*}*/

  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }

  body > .el-container {
    margin-bottom: 40px;
  }

  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }

  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  }

</style>
