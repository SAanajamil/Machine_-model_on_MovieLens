# Machine_ model_on_MovieLens
 Building a Factorization Machines model on MovieLens
 
for windows user first you have to download wget from this 
link(https://eternallybored.org/misc/wget/) and install. for installation pls follow the 
link video (https://www.jcchouinard.com/wget/).
  !wget http://files.grouplens.org/datasets/movielens/ml-100k.zip
  !unzip ml-100k.zip

#As the dataset is ordered by user ID, we shuffle it as a precaution. Then, we take
#a look at the first few lines:
#%cd ml-100k
#!shuf ua.base -o ua.base.shuffled
#!head -5 ua.base.shuffled

#for shuffling use this code
  from sklearn.utils import shuffle
  data = shuffle(data)
