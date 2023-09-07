# SociCo_Datasets
This repository contains a Chinese Weibo dataset and an English Twitter dataset. Both datasets contain multiple text and image blog posts of users.

After collecting the data, we screened and sorted the data, and deleted some users whose tags were missing or whose blog posts were less than 20. Both datasets have user gender labels as either male or female. The year of birth labels are divided into three years: 1979 and before, 1980 to 1989, and 1990 and after. In the following, Weibo dataset and Twitter dataset will be used to refer to the two datasets collected in this paper.

## Datasets statistics
### Weibo dataset
The Weibo dataset has a total of 2486 users, of which the ratio of male to female is close to 3 to 1, and the ratio of birth date from front to back is about 1 to 3 to 2.5. The training set of Weibo dataset contains 2075 users, and the test set contains 411 users. The number of text moments provided by each user in this dataset is less than or equal to 60, and the number of visual moments is less than or equal to 10.

### Twitter dataset
The Twitter dataset has a total of 6572 users, of which the ratio of male to female is about 3 to 1, and the ratio of birth years from front to back is about 1 to 1 to 1.5. In this paper, the data set is randomly divided and five-fold cross-validation is performed, and 4600 users are selected as the training set and 1972 users are selected as the test set each time. In the Twitter dataset, each user provided at most 60 textual moments and at most 10 visual moments.
