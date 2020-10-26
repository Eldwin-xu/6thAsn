1. 去Unity官网下载了PostProcessing Package
2. 在Main Camera里面加入了PostProcessing Layer
3. 在场景里加入了Empty GameObject改名为PostEffects
4. 在里面加入了PostProcessing Volume
5. 把PostEffects加入新的Layer叫PostProcessing
6. PostProcessing Layer 设置成PostProcessing
7. 在PostProcessing Volume里面加入所有Unity Effect
8. 使用AO, Bloom, Color Grading, Grain, Vignette
8-1. AO和Bloom都是调整数值
8-2. Color Grading调整Temperature, Mode, Saturation, EV, Contrast
8-3. Grain和Vignette都是调整数值
9. 在PostEffects里面加了Box Collider设置了效果的大小， 调为Is Trigger (不和角色顶撞)
10.加入Reflection Probe在玻璃附近
11.更改Direct Light数值
12. Lighting里面开启Fog， 更改数值
13. 在每个环上面加了SpotLight
14. 在场景右边加入一个SpotLight，调整数值，增加宽度

总体目标：因为场景比较简单，就是想把它看起来和本来不太一样。