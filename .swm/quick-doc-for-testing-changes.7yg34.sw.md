---
id: 7yg34
name: Quick doc for testing changes
file_version: 1.0.2
app_version: 0.7.4-0
file_blobs:
  setup.py: a5f464a9eb56522818309356988969037d548ac9
  README.md: d9058efd061e4636989453d48d0799d560b42066
  TERMINOLOGY.md: 7f3a83135f26c6e8d97eb5d6cf33438d0a481ee4
---

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 setup.py
```python
⬜ 10     ]
⬜ 11     
⬜ 12     setup(
🟩 13         name='d2l',
🟩 14         version=d2l.__version__,
🟩 15         python_requires='>=3.5',
🟩 16         author='D2L Developers',
🟩 17         author_email='d2l.devs@gmail.com',
🟩 18         url='https://d2l.ai',
🟩 19         description='Dive into Deep Learning',
🟩 20         license='MIT-0',
🟩 21         packages=find_packages(),
🟩 22         zip_safe=True,
🟩 23         install_requires=requirements,
⬜ 24     )
⬜ 25     
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 setup.py
```python
⬜ 2      import d2l
⬜ 3      
⬜ 4      requirements = [
🟩 5          'jupyter',
🟩 6          'numpy',
🟩 7          'matplotlib',
🟩 8          'requests',
🟩 9          'pandas'
⬜ 10     ]
⬜ 11     
⬜ 12     setup(
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 README.md
```markdown
⬜ 7      <h5 align="center"><i>理解深度学习的最佳方法是学以致用。</i></h5>
⬜ 8      
⬜ 9      <p align="center">
🟩 10       <img width="200"  src="static/frontpage/_images/eq.jpg">
🟩 11       <img width="200"  src="static/frontpage/_images/figure.jpg">
🟩 12       <img width="200"  src="static/frontpage/_images/code.jpg">
🟩 13       <img width="200"  src="static/frontpage/_images/notebook.gif">
⬜ 14     </p>
⬜ 15     
⬜ 16     本开源项目代表了我们的一种尝试：我们将教给读者概念、背景知识和代码；我们将在同一个地方阐述剖析问题所需的批判性思维、解决问题所需的数学知识，以及实现解决方案所需的工程技能。
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 README.md
```markdown
⬜ 24     
⬜ 25     <h5 align="center">将本书（中英文版）用作教材或参考书的大学</h5>
⬜ 26     <p align="center">
🟩 27       <img width="400"  src="http://en.d2l.ai.s3-website-us-west-2.amazonaws.com/_images/map.png">
⬜ 28     </p>
⬜ 29     
⬜ 30     如果本书对你有帮助，请Star (★) 本仓库或引用本书的英文版：
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 1      ## 英汉术语对照
⬜ 2      
🟩 3      鞍点，saddle point
🟩 4      
🟩 5      变换，transform
🟩 6      
🟩 7      编码器，encoder
🟩 8      
🟩 9      标签，label
🟩 10     
⬜ 11     步幅，stride
⬜ 12     
⬜ 13     参数，parameter
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 12     
⬜ 13     参数，parameter
⬜ 14     
🟩 15     长短期记忆网络，long short-term memory (LSTM)
🟩 16     
🟩 17     超参数，hyperparameter
🟩 18     
🟩 19     层序softmax，hierarchical softmax
🟩 20     
🟩 21     查准率，precision
🟩 22     
🟩 23     成本，cost
⬜ 24     
⬜ 25     词表，vocabulary
⬜ 26     
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 24     
⬜ 25     词表，vocabulary
⬜ 26     
🟩 27     词嵌入，word embedding
🟩 28     
🟩 29     词向量，word vector
🟩 30     
🟩 31     词元，token
🟩 32     
🟩 33     词元分析器，tokenizer
🟩 34     
🟩 35     词元化，tokenize
🟩 36     
⬜ 37     汇聚层，pooling layer
⬜ 38     
⬜ 39     稠密，dense
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 38     
⬜ 39     稠密，dense
⬜ 40     
🟩 41     大小，size
🟩 42     
🟩 43     导入，import
🟩 44     
🟩 45     轮，epoch
🟩 46     
🟩 47     暂退法，dropout
🟩 48     
🟩 49     动量法，momentum (method)
🟩 50     
🟩 51     独立同分布，independent and identically distributed (i.i.d.)
⬜ 52     
⬜ 53     端到端，end-to-end
⬜ 54     
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 52     
⬜ 53     端到端，end-to-end
⬜ 54     
🟩 55     多层感知机，multilayer perceptron
🟩 56     
🟩 57     多头注意力，multi-head attention
🟩 58     
🟩 59     二元分类，binary classification
🟩 60     
🟩 61     二元，bigram
🟩 62     
🟩 63     子采样，subsample
🟩 64     
🟩 65     发散，diverge
🟩 66     
⬜ 67     泛化，generalization
⬜ 68     
⬜ 69     泛化误差，generalization error
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 68     
⬜ 69     泛化误差，generalization error
⬜ 70     
🟩 71     方差，variance
🟩 72     
🟩 73     分类，classification
🟩 74     
🟩 75     分类器，classifier
🟩 76     
🟩 77     负采样，negative sampling
🟩 78     
⬜ 79     感受野，receptive field
⬜ 80     
⬜ 81     格拉姆矩阵，Gram matrix
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 80     
⬜ 81     格拉姆矩阵，Gram matrix
⬜ 82     
🟩 83     共现，co-occurrence
🟩 84     
🟩 85     广播，broadcast
🟩 86     
🟩 87     规范化，normalization
🟩 88     
🟩 89     过拟合，overfitting
🟩 90     
⬜ 91     核回归，kernel regression
⬜ 92     
⬜ 93     恒等映射，identity mapping
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 91     核回归，kernel regression
⬜ 92     
⬜ 93     恒等映射，identity mapping
🟩 94     
🟩 95     假设，hypothesis
🟩 96     
🟩 97     基准，baseline
🟩 98     
🟩 99     激活函数，activation function
🟩 100    
🟩 101    解码器，decoder
🟩 102    
⬜ 103    近似法，approximate method
⬜ 104    
⬜ 105    经验风险最小化，empirical risk minimization
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 103    近似法，approximate method
⬜ 104    
⬜ 105    经验风险最小化，empirical risk minimization
🟩 106    
🟩 107    局部最小值，local minimum
🟩 108    
🟩 109    卷积核，convolutional kernel
🟩 110    
🟩 111    卷积神经网络，convolutional neural network
🟩 112    
🟩 113    决策边界，decision boundary
🟩 114    
⬜ 115    均值，mean
⬜ 116    
⬜ 117    均方误差，mean squared error
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 116    
⬜ 117    均方误差，mean squared error
⬜ 118    
🟩 119    均匀采样，uniform sampling
🟩 120    
🟩 121    块，block
🟩 122    
🟩 123    困惑度，perplexity
⬜ 124    
⬜ 125    拉普拉斯平滑，Laplace smoothing
⬜ 126    
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 124    
⬜ 125    拉普拉斯平滑，Laplace smoothing
⬜ 126    
🟩 127    连结，concatenate
🟩 128    
🟩 129    类，class
🟩 130    
🟩 131    交叉熵，cross-entropy
🟩 132    
🟩 133    连续词袋，continous bag-of-words (CBOW)
🟩 134    
🟩 135    零张量，zero tensor
🟩 136    
🟩 137    流水线，pipeline
🟩 138    
⬜ 139    滤波器，filter
⬜ 140    
⬜ 141    门控循环单元，gated recurrent units (GRU)
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 140    
⬜ 141    门控循环单元，gated recurrent units (GRU)
⬜ 142    
🟩 143    目标检测，object detection
🟩 144    
🟩 145    偏置，bias
🟩 146    
🟩 147    偏导数，partial derivative
🟩 148    
🟩 149    偏移量，offset
⬜ 150    
⬜ 151    批量，batch
⬜ 152    
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 TERMINOLOGY.md
```markdown
⬜ 150    
⬜ 151    批量，batch
⬜ 152    
🟩 153    齐普夫定律，Zipf's law
🟩 154    
🟩 155    欠拟合，underfitting
🟩 156    
🟩 157    情感分析，sentiment analysis
🟩 158    
🟩 159    全连接层，fully-connected layer
🟩 160    
🟩 161    权重，weight
🟩 162    
🟩 163    三元，trigram
🟩 164    
🟩 165    上采样，upsample
🟩 166    
🟩 167    上下文变量，context variable
🟩 168    
🟩 169    上下文窗口，context window
🟩 170    
🟩 171    上下文词，context word
🟩 172    
🟩 173    上下文向量，context vector
🟩 174    
🟩 175    实例/示例，instance
🟩 176    
🟩 177    收敛，converge
🟩 178    
🟩 179    属性，property
🟩 180    
🟩 181    数值方法，numerical method
🟩 182    
🟩 183    数据集，dataset
🟩 184    
🟩 185    数据示例，data instance
🟩 186    
🟩 187    数据样例，data example
🟩 188    
🟩 189    顺序分区，sequential partitioning
🟩 190    
🟩 191    softmax回归，softmax regression
🟩 192    
🟩 193    随机采样，random sampling
🟩 194    
🟩 195    损失函数，loss function
🟩 196    
🟩 197    双向循环神经网络，bidirectional recurrent neural network
🟩 198    
🟩 199    特征，feature
🟩 200    
🟩 201    特征图，feature map
🟩 202    
🟩 203    特征值，eigenvalue
🟩 204    
🟩 205    梯度，gradient
🟩 206    
🟩 207    梯度裁剪，gradient clipping
🟩 208    
🟩 209    梯度消失，vanishing gradients
🟩 210    
🟩 211    填充，padding
🟩 212    
🟩 213    跳元模型，skip-gram model
🟩 214    
🟩 215    调参，tune hyperparameter
🟩 216    
🟩 217    停用词，stop words
🟩 218    
🟩 219    通道，channel
🟩 220    
🟩 221    凸优化，convex optimization
🟩 222    
🟩 223    图像，image
🟩 224    
🟩 225    未知词元，unknown token
🟩 226    
🟩 227    无偏估计，unbiased estimate
🟩 228    
🟩 229    误差，error
🟩 230    
🟩 231    小批量，minibatch
🟩 232    
🟩 233    小批量梯度，minibatch gradient
🟩 234    
🟩 235    线性模型，linear model
🟩 236    
🟩 237    线性回归，linear regression
🟩 238    
🟩 239    协同过滤，collaborative filtering
🟩 240    
🟩 241    学习率，learning rate
🟩 242    
🟩 243    训练误差，training error
🟩 244    
🟩 245    循环神经网络，recurrent neural network (RNN)
🟩 246    
🟩 247    样例，example
🟩 248    
🟩 249    一维梯度下降，gradient descent in one-dimensional space
🟩 250    
🟩 251    一元，unigram
🟩 252    
🟩 253    隐藏变量，hidden variable
🟩 254    
🟩 255    隐藏层，hidden layer
🟩 256    
🟩 257    优化器，optimizer
🟩 258    
🟩 259    语料库，corpus
🟩 260    
🟩 261    运算符，operator
🟩 262    
🟩 263    自注意力，self-attention
🟩 264    
🟩 265    真实值，ground truth
🟩 266    
🟩 267    指标，metric
🟩 268    
🟩 269    支持向量机，support vector machine
🟩 270    
🟩 271    注意力机制，attention mechanism
🟩 272    
🟩 273    注意力模型，attention model
🟩 274    
🟩 275    注意力提示，attention cue
🟩 276    
🟩 277    准确率/精度，accuracy
⬜ 278    
```

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://swimm-web-app.web.app/repos/Z2l0aHViJTNBJTNBZDJsLXpoJTNBJTNBc2h1anV1dQ==/docs/7yg34).