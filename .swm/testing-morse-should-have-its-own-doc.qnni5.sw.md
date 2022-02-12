---
id: qnni5
name: testing morse should have it's own doc
file_version: 1.0.2
app_version: 0.7.4-0
file_blobs:
  chapter_attention-mechanisms/transformer.md: 208e59b1eec7c4e7accc5e476099e6fa959654ab
  chapter_attention-mechanisms/transformer_origin.md: 5bf782832af40f68c886186ac166ff2615db86fb
---

dod:

after committing doc

change local files with the snippets to same commit

<br/>

doc should have outdated docs

<br/>

`width`[<sup id="2hyFKK">↓</sup>](#f-2hyFKK)
<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 chapter_attention-mechanisms/transformer.md
```markdown
⬜ 8      Transformer作为编码器－解码器架构的一个实例，其整体架构图在 :numref:`fig_transformer`中展示。正如所见到的，transformer是由编码器和解码器组成的。与 :numref:`fig_s2s_attention_details`中基于Bahdanau注意力实现的序列到序列的学习相比，transformer的编码器和解码器是基于自注意力的模块叠加而成的，源（输入）序列和目标（输出）序列的*嵌入*（embedding）表示将加上*位置编码*（positional encoding），再分别输入到编码器和解码器中。
⬜ 9      
⬜ 10     ![transformer架构](../img/transformer.svg)
🟩 11     :width:`1000px`
🟩 12     :label:`fig_transformer`
⬜ 13     
⬜ 14     图 :numref:`fig_transformer`中概述了transformer的架构。从宏观角度来看，transformer的编码器是由多个相同的层叠加而成的，每个层都有两个子层（子层表示为$\mathrm{sublayer}$）。第一个子层是*多头自注意力*（multi-head self-attention）汇聚；第二个子层是*基于位置的前馈网络*（positionwise feed-forward network）。具体来说，在计算编码器的自注意力时，查询、键和值都来自前一个编码器层的输出。受 :numref:`sec_resnet`中残差网络的启发，每个子层都采用了*残差连接*（residual connection）。在transformer中，对于序列中任何位置的任何输入$\mathbf{x} \in \mathbb{R}^d$，都要求满足$\mathrm{sublayer}(\mathbf{x}) \in \mathbb{R}^d$，以便残差连接满足$\mathbf{x} + \mathrm{sublayer}(\mathbf{x}) \in \mathbb{R}^d$。在残差连接的加法计算之后，紧接着应用*层规范化*（layer normalization） :cite:`Ba.Kiros.Hinton.2016`。因此，输入序列对应的每个位置，transformer编码器都将输出一个$d$维表示向量。
⬜ 15     
```

<br/>


<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 chapter_attention-mechanisms/transformer.md
```markdown
⬜ 109    
⬜ 110    ```{.python .input}
⬜ 111    #@tab tensorflow
🟩 112    ffn = PositionWiseFFN(4, 8)
🟩 113    ffn(tf.ones((2, 3, 4)))[0]
⬜ 114    ```
⬜ 115    
⬜ 116    ## 残差连接和层规范化
```

<br/>

<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 chapter_attention-mechanisms/transformer.md
```markdown
⬜ 95     下面的例子显示，[**改变张量的最里层维度的尺寸**]，会改变成基于位置的前馈网络的输出尺寸。因为用同一个多层感知机对所有位置上的输入进行变换，所以当所有这些位置的输入相同时，它们的输出也是相同的。
⬜ 96     
⬜ 97     ```{.python .input}
🟩 98     ffn = PositionWiseFFN(4, 8)
🟩 99     ffn.initialize()
🟩 100    ffn(np.ones((2, 3, 4)))[0]
⬜ 101    ```
⬜ 102    
⬜ 103    ```{.python .input}
```

<br/>

`minute_transformer`[<sup id="ZL7Wel">↓</sup>](#f-ZL7Wel) \`
<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 chapter_attention-mechanisms/transformer_origin.md
```markdown
⬜ 1      # Transformer
🟩 2      :label:`minute_transformer`
⬜ 3      
⬜ 4      
⬜ 5      We have compared CNNs, RNNs, and self-attention in
```

<br/>

<!-- THIS IS AN AUTOGENERATED SECTION. DO NOT EDIT THIS SECTION DIRECTLY -->
### Swimm Note

<span id="f-ZL7Wel">minute_transformer</span>[^](#ZL7Wel) - "chapter_attention-mechanisms/transformer_origin.md" L2
```markdown
:label:`minute_transformer`
```

<span id="f-2hyFKK">width</span>[^](#2hyFKK) - "chapter_attention-mechanisms/transformer.md" L11
```markdown
:width:`1000px`
```

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://swimm-web-app.web.app/repos/Z2l0aHViJTNBJTNBZDJsLXpoJTNBJTNBc2h1anV1dQ==/docs/qnni5).