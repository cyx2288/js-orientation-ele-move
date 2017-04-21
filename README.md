# orientation-el-move 根据设备晃动，页面元素出现移动
可以在移动端，通过重力感应移动页面元素，适合展示用h5
## 使用方法
引入插件 ori-move.js 该脚本不依赖任何库<br/>
ori-move.min.js 是压缩版本<br/>
需要移动的元素 加个class="ori_move" 加私有属性data-ori="x" 其中 x 为你想要移动的感应权重。<br/>
插件初始化 orientationElMove.init()<br/>

#### v1.0.0
1、解决ios端，跳转后返回该页面后，元素会一直飘走
2、解决Android端，移动元素有卡顿问题
