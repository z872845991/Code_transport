# something when I learn mnist

## Environment

- 在colab中ipynb文件可以直接运行
- 在colab中可以直接将文件下载到本地，可以选择py格式
- colab可以使用一张T4的卡进行GPU计算

## 遇到的问题

1. 格式问题，对齐出错，产生了代码，主要在于colab上默认缩进单位为2个字符，不太显眼。

   - 可以在设置中，将缩进改为4个字符

2. `net.train()` 和 `net.eval()` 两个函数的使用

   - 对我来说，这两个函数类似一个标记，尽管它执行了一些东西，但对我来说，我还不清楚它的具体作用

3. 图像显示问题，

   - `reshape` `transpose` 两个函数的使用

   - `torchvision.utils.make_grid()`可以将图片整合在一起，配合`transpose`使用

4. 测试问题

   - 在训练完需要保存模型
   - 在测试时需要启动模型
5. 