# HFL-RC: A Chinese Reading Comprehension Dataset

标签（空格分隔）： Reading Comprehension

---
Here, we release the first Chinese reading comprehension dataset, which includes People Daily and Children's Fairy Tale (CFT). We hope this would speed up the process for future research in machine comprehension.

##Statistics
The statistics of the dataset is listed as below.
|　| PD-train | PD-valid | PD-test | CFT-auto | CFT-human |
|--------|:-----:|:-----:|:-----:|:-----:|:-----:|
| # Query | 870,710 | 3,000 | 3,000 | 1,646 | 1,953 |
| Max # tokens in docs | 618 | 536 | 634 | 318 | 414 |
| Max # tokens in query| 502 | 153 | 265 | 83 | 92 |
| Avg # tokens in docs | 379 | 425 | 410 | 122 | 153 |
| Avg # tokens in query| 38 | 38 | 41 | 20 | 20 |
| Vocabulary | 248,160 | - | - | - | - |


##Data Format
Here is a sample of People Daily data,
```
1 ||| 人民网 1月 1日 讯 据 《 纽约 时报 》 报道 ， 美国 华尔街 股市 在 2013年 的 最后 一 天 继续 上涨 ， 和 全球 股市 一样 ， 都 以 最高 纪录 或 接近 最高 纪录 结束 本年 的 交易 。
2 ||| 《 纽约 时报 》 报道 说 ， 标普 500 指数 今年 上升 29.6% ， 为 1997年 以来 的 最 大 涨幅 ；
3 ||| 道琼斯 工业 平均 指数 上升 26.5% ， 为 1996年 以来 的 最 大 涨幅 ；
4 ||| 纳斯达克 上涨 38.3% 。
5 ||| 就 12月 31日 来说 ， 由于 就业 前景 看好 和 经济 增长 明年 可能 加速 ， 消费者 信心 上升 。
6 ||| 工商 协进会 报告 ， 12月 消费者 信心 上升 到 78.1 ， 明显 高于 11月 的 72 。
7 ||| 另 据 《 华尔街 日报 》 报道 ， 2013年 是 1995年 以来 美国 股市 表现 最 好 的 一 年 。
8 ||| 这 一 年 里 ， 投资 美国 股市 的 明智 做法 是 追 着 “ 傻钱 ” 跑 。
9 ||| 所谓 的 “ 傻钱 ” X ， 其实 就 是 买 入 并 持有 美国 股票 这样 的 普通 组合 。
10 ||| 这个 策略 要 比 对冲 基金 和 其它 专业 投资者 使用 的 更为 复杂 的 投资 方法 效果 好 得 多 。
11 ||| 所谓 的 “ 傻钱 ” X ， 其实 就 是 买 入 并 持有 美国 股票 这样 的 普通 组合 。 ||| 策略
```
This document consists of 10 sentences, each sentence is in the form of 
```
sentence_id(space)|||(space)sentence
```
and the last line indicate the `Query` and `Answer`
```
sentence_id(space)|||(space)Query(space)|||(space)Answer
```


##Downloads
**The download link will soon available...** 
> **People Daily**
[Training Data]
[Validation & Test Data]

> **Children's Fairy Tale (CFT)**
[Automatic Test Data]
[Human Evaluated Test Data]

Download all data in a single package:
> **ALL in ONE**
[Download link]


##Paper
Our paper is avaliable through arXiv: 


##Reference
If you wish to use this data in your work, please cite
```
@article{cui-etal-2016,
  title={Consensus Attention Neural Networks for Chinese Reading Comprehension},
  author={Cui, Yiming and Liu, Ting and Chen, Zhipeng and Wang, Shijin and Hu, Guoping},
  journal={arXiv preprint arXiv:1606.xxxxx},
  year={2016}
}
```

##You may also interested in ...

> **DeepMind CNN / Daily Mail data**
[**Pre-processed Data (recommended)**](http://cs.nyu.edu/~kcho/DMQA/)
[Original Data](https://github.com/deepmind/rc-data)

> **Children's Book Test (CBTest)**
[**Original Data**](http://www.thespermwhale.com/jaseweston/babi/CBTest.tgz)


##Contact
For any problems concerning the paper or data, please contact: **admin [AT] ymcui [dot] com**