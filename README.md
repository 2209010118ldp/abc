主要程序文件说明
数据
data文件夹
HowNetPOSWord.txt              情感词典
stop_word.txt                         停用词
user_dict.txt                           用户自定义词库
XiFaShui(11061).csv               爬取的淘宝评论

data(temp)文件夹
unique_comments.txt   去重的爬取评论
review_cleaned.txt    清洗后评论
review_seg_post.txt   分词标注词性
review_idf.txt          分词的idf
idf.csv                    分词的idf
ns_dict.csv             候选的观点集及计数
pair_score.csv        排序后的观点
pair_useful.csv       有效的观点

results文件夹
PossibleNewword.csv   可能的新词
generated_reviews.txt  生成的评论
review_labeled.csv       带标签的评论
review_featured.csv     提取的特征

代码
评论采集.txt                                          采集评论的油猴脚本
Reviewprocess+FindNewPhrase.ipynb  人工评论处理，发现新词
GenerateReviews.ipynb                        生成虚假评论
GetFeatures.ipynb                                特征提取
TrainModel.ipynb                                 训练模型
