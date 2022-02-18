# Critical Difference Diagrams 
该存储库包含根据Wilcoxon-Holm方法生成关键差异图以检测成对重要性所需的代码。

## Result 
通过运行```python3 main.py```，您将使用 Wilcoxon-Holm 事后分析对 [example.csv](https://github.com/hfawaz/ cd-diagram/blob/master/example.csv) 文件。
![cd-diagram-example](https://github.com/hfawaz/cd-diagram/blob/master/cd-diagram.png)
首先执行弗里德曼检验以拒绝原假设，然后我们继续基于 Wilcoxon-Holm 方法进行事后分析。
我们可以清楚地看到平均而言 ```clf3``` 和 ```clf5``` 是 15 个数据集上最好的算法。
粗水平线将一组没有显着差异的分类器分组。



## Relevant projects
### Deep learning for time series classification: a review 
在这篇 [论文](https://arxiv.org/abs/1809.04356v3) 中，我们使用关键差异图来比较最近用于时间序列分类的深度学习模型，我们在 [UCR] 的 85 个不同数据集上评估了 9 种不同的架构 /UEA 档案](https://www.cs.ucr.edu/~eamonn/time_series_data/)。

查看 [代码](https://github.com/hfawaz/dl-4-tsc)！

### Deep Neural Network Ensembles for Time Series Classification
在这篇 [论文](https://arxiv.org/abs/1903.06602) 中，我们使用了关键差异图来展示集成混合架构如何让深度学习模型在对来自 [UCR] 的 85 个不同数据集进行评估时达到更高的准确性 /UEA 档案](https://www.cs.ucr.edu/~eamonn/time_series_data/)。

查看[代码](https://github.com/hfawaz/ijcnn19ensemble)！

## Requirements
要运行此代码，您将需要以下 python 包：
* [numpy](https://www.numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [scipy](https://www.scipy.org/)
* [networkx](https://networkx.github.io/)

## Reference 

如果您重复使用此作品，请引用：

```
@article{IsmailFawaz2018deep,
  Title                    = {Deep learning for time series classification: a review},
  Author                   = {Ismail Fawaz, Hassan and Forestier, Germain and Weber, Jonathan and Idoumghar, Lhassane and Muller, Pierre-Alain},
  journal                  = {Data Mining and Knowledge Discovery},
  Year                     = {2019},
  volume                   = {33},
  number                   = {4},
  pages                    = {917--963},
}
```
