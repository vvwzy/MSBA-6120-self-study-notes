# MSBA-6120
All course materials for 6120

prior to 1st class:
Pre-req knowledge to learn:
Math: knowledge of basic algebra is helpful; for more advanced procedures, some knowledge of calculus is also useful.
Computer skills: R, learn yourself.
the empirical rule（only to those bell-shaped)： 68% of the data lie within 1 std deviation of the mean, 95% of the data lie within 2 std deviations of the mean, 99.7% of the data lies within 3 std deviations of the mean.
Chebyhev's Theorem(apply to every data set)：>=3/4 of the data lie within 2 std dev of the mean; >=8/9 of the data lie within 3 std dev of the mean; >= 1-1/k^2 of the data lie within k std devs of the mean
Degrees of freedom(df): independent pieces of information used in the calculation.
样本方差自由度为什么是n-1呢？
【自由度：一组数据中可以自由取值的个数。所谓自由取值，是指抽样时选取样本，也就是说：只有当以样本的统计量来估计总体的参数时才有自由度的概念，直接统计总体参数时是没有自由度概念的。自由度概念，是为了在通过样本进行参数估计时，剔除系统误差，实现无偏估计。无偏估计就是系统误差为零的估计。
当样本数据的个数为n时，若样本平均数 x拔 确定后，则附加给n个观测值的约束个数就是1个，一次只有n-1个数据可以自由取值，其中必有一个数据不能自由取值。在计算离差平方和 ∑(xi -x)2 时，必须先求出样本平均数 x拔，而 x拔 则是附加给 ∑(xi -x)2 的一个约束，因此，计算离差平方和时只有n-1个独立的观测值，而不是n个。因为在均值确定后，如果知道了其中n-1个数的值，第n个数的值也就确定了。而在计算离差平方和 ∑(xi -x)2 时，必须先求出均值 x拔，均值就相当于一个限制条件，由于加了这个限制条件，估计总体方差的自由度为n-1。】
![image](https://user-images.githubusercontent.com/82482927/132413066-4b66a9fa-d0ee-4c09-83cb-8113ae2a0eea.png)
The likelihood that the survey proportion is close to the population proportion determines out confidence in the survey result.
sample space: sets of all possible outcomes; s{...} event: a subset of the sample space.
probability of an outcome:p(0,1)
probability of an event: the sum of the probabilities of the individual outcomes of which it is composed. P(A)
complement of an event
the intersection of events
mutually exclusive
union of events
addive rule of probability
conditional probability and independent events: P(A|B):the conditional probability of A given B : P（A|B)=P(A交B)/P(B)可以这么理解：条件概率时，例如计算在已经确定B发生的前提下，A发生的概率时，将B当作sample space，此时，P（B）= 1， 取出A在B中的部分，除以此刻的S，即B，得到P(A|B)
propotion:当下的概率 likelihood：未来发生的概率
likelihood interpretations:1.Frequentist: limit of the relative frequency of "comparable" events in the long run / law of large numbers(LLN) 2.Subjective: "Degree of believe"
In LLN, the process is not self correcting, instead, it operates by washing out deviations.
