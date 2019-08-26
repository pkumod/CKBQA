# CKBQA
A Chinese KBQA dataset containing both simple questions and complex questions.

For each chinese question, we provide both the gold answers and the gold SPARQL query, so that this dataset can be also applyied in Semantic Parsing task.
Here is a example:
```
q1546:列出中国曾获柏林国际电影节金熊奖的导演？
select ?x where { ?x <职业> <导演>. ?x <国籍> <中华人民共和国>. ?x <主要成就> "威尼斯国际电影节金狮奖". }
<张艺谋>	<贾樟柯>
```

The annotation based on the PKUBASE knowledge base, please click [here](https://pan.baidu.com/s/11vyV_1klxUCefP4ooxKeWA) to download, the extraction code is ```3grq```.

# CCKS Evaluation
From the 2018, we hold the CKBQA evaluation task in [CCKS](http://www.ccks2019.cn/?page_id=62) (China Conference on Knowledge Graph and Semantic Computing).
We update the dataset and release the latest version annually after the evaluation task ends.

Here are the previous evaluation pages:
* [CCKS 2019 task 6](https://biendata.com/competition/ccks_2019_6/)
* [CCKS 2018 task 4](https://biendata.com/competition/CCKS2018_4/)

# Citation
This dataset is annotated and released by pkumod group.
If you use this dataset in your research work, please cite the following paper.
```
// To be updated
@inproceedings{
  title={},
  author={},
  booktitle={},
  volume={},
  pages={},
  year={2019}
}
```
