# Example 1

> To improve computational efficiency and **take advantage of** GPUs, we typically carry out vector calculations for minibatches of data.[^1]

## Remarks
根据[thefreedictionary](https://idioms.thefreedictionary.com/take+advantage+of)，该词其的其中一个意思是：
> To utilize or avail oneself of something to the fullest possible extent.

可见，该词其实有“最大程度利用”、“充分利用”或者“利用好”的意思，而不只是指“利用”（翻译软件一般会将该词汇译为“利用”）。就本例的语境而言，GPU当然也能够执行“0.1+0.9”这样简单的浮点数运算，
但是对小批量数据进行向量运算则是为了最大程度利用好GPU的计算优势（大批量低精度运算）。因此，本例用的是**take advantage of**。
 
 
 [^1]: https://d2l.ai/chapter_linear-networks/softmax-regression.html#vectorization-for-minibatches
