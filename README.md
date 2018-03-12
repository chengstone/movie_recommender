# movie_recommender
MovieLens based recommender system.使用MovieLens数据集训练的电影推荐系统。

__Author__ chengstone

__e-Mail__ 69558140@163.com

代码详解请参见文内jupyter notebook和↓↓↓

知乎专栏：https://zhuanlan.zhihu.com/p/32078473

博客：http://blog.csdn.net/chengcheng1394/article/details/78820529

欢迎转发扩散 ^_^

This is a simple recommender system, using Tensorflow 1.0 and python 3.5.
With text cnn implement movies recommend:
 - 1.Giving user id and movie id to predict a rating.
 - 2.Recommanding a same Genres's movies.
 - 3.Recommanding your favorites movies.
 - 4.Recommanding Watched the same movie's people who favorites movies.

这是一个简单的推荐系统，使用TensorFlow1.0和Python 3.5开发。

使用文本卷积神经网络，并利用MovieLens数据集完成电影推荐的任务。
实现的推荐功能如下：
 - 1、指定用户和电影进行评分
 - 2、推荐同类型的电影
 - 3、推荐您喜欢的电影
 - 4、看过这个电影的人还看了（喜欢）哪些电影

## 模型如下：
![image](https://raw.githubusercontent.com/chengstone/movie_recommender/master/assets/model.001.jpeg)

## 训练的Loss：
![image](https://raw.githubusercontent.com/chengstone/movie_recommender/master/assets/loss.png)

## 指定用户和电影进行评分
给用户234，电影1401的评分是：4.27963877

## 推荐同类型的电影
您看的电影是：[1401 'Ghosts of Mississippi (1996)' 'Drama']

以下是给您的推荐：

3385

[3454 'Whatever It Takes (2000)' 'Comedy|Romance']

707

[716 'Switchblade Sisters (1975)' 'Crime']

2351

[2420 'Karate Kid, The (1984)' 'Drama']

2189

[2258 'Master Ninja I (1984)' 'Action']

2191

[2260 'Wisdom (1986)' 'Action|Crime']

## 推荐您喜欢的电影
以下是给您的推荐（用户234）：

1642

[1688 'Anastasia (1997)' "Animation|Children's|Musical"]

994

[1007 'Apple Dumpling Gang, The (1975)' "Children's|Comedy|Western"]

667

[673 'Space Jam (1996)' "Adventure|Animation|Children's|Comedy|Fantasy"]

1812

[1881 'Quest for Camelot (1998)' "Adventure|Animation|Children's|Fantasy"]

1898

[1967 'Labyrinth (1986)' "Adventure|Children's|Fantasy"]

## 看过这个电影的人还看了（喜欢）哪些电影
您看的电影是：[1401 'Ghosts of Mississippi (1996)' 'Drama']

喜欢看这个电影的人是：[[5782 'F' 35 0]

 [5767 'M' 25 2]
 
 [3936 'F' 35 12]
 
 [3595 'M' 25 0]
 
 [1696 'M' 35 7]
 
 [2728 'M' 35 12]
 
 [763 'M' 18 10]
 
 [4404 'M' 25 1]
 
 [3901 'M' 18 14]
 
 [371 'M' 18 4]
 
 [1855 'M' 18 4]
 
 [2338 'M' 45 17]
 
 [450 'M' 45 1]
 
 [1130 'M' 18 7]
 
 [3035 'F' 25 7]
 
 [100 'M' 35 17]
 
 [567 'M' 35 20]
 
 [5861 'F' 50 1]
 
 [4800 'M' 18 4]
 
 [3281 'M' 25 17]]
 
喜欢看这个电影的人还喜欢看：

1779

[1848 'Borrowers, The (1997)' "Adventure|Children's|Comedy|Fantasy"]

1244

[1264 'Diva (1981)' 'Action|Drama|Mystery|Romance|Thriller']

1812

[1881 'Quest for Camelot (1998)' "Adventure|Animation|Children's|Fantasy"]

1742

[1805 'Wild Things (1998)' 'Crime|Drama|Mystery|Thriller']

2535

[2604 'Let it Come Down: The Life of Paul Bowles (1998)' 'Documentary']

更多内容请参考代码，Enjoy！
