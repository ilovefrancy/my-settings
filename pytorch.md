# forward的使用

```python
class Modeule(nn.Module):
  def __init__(self):
    super(Module.self).__init__()
    # ...
  
  def forward(self, x):
    # ...
    return x

data = ... # 输入数据
# 实例化一个对象
module = Module()
# 前向传播
module(data)
```

# forward使用的解释

init只是规定网络结构的输入通道数量、输出通道数量和卷积核尺寸。
在神经网络中，描述具体结构的是在forward部分。
