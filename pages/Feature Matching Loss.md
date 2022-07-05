title:: Feature Matching Loss

- $s$ 表示目標語音，$\tilde{s}$ 表示生成語音
- $\sum_{i=1}^L \frac{1}{N_i} {||D^{(i)}(s)-D^{(i)}(\tilde{s})||}_1$
- $D^{(i)}$ 表示 $D$ 的 i-th layer 抽取的 features，期望能讓語音在特徵的層次上相似。
- $L$ 表示 Discriminator 的層數