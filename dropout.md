# dropout
## tf.nn.dropout and  tf.layers.dropout

- tf.nn.dropout

>tf.nn.dropout(
    x,
    keep_prob,
    noise_shape=None,
    seed=None,
    name=None
)  

其中需要注意的是keep_prob:保留率  
- tf.layers.dropout  
```python
tf.layers.dropout(
    inputs,
    rate=0.5,
    noise_shape=None,
    seed=None,
    training=False,
    name=None
)
```
关键的参数有俩个：rate=1-keep_prob;training为ture时，训练模式；false时为inference mode(预测)
