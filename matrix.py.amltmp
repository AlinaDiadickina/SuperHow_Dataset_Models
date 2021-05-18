from sklearn.metrics import confusion_matrix
import pandas as pd
import numpy as np


dataset_pre = list
dataset_post = list

f1 = open("./git/jodie/data/lastfm.csv", 'r')
Lines = f1.readlines()

# count = 0
# j = 0
# pre_data =[]

# for line in Lines:
#     if count >= 1:
#         res = np.matrix(line)
#         pre_data.append(res)
#     count = count +1

# print(pre_data)


count = 0
j = 0
pre_data =[]

for line in Lines:
    res =[]
    if count >= 1:
        print(np.array(line))
        
        # res = [int(sub.split(',')[1]) for sub in line]
        # if '\n' in res: res.remove('\n')
        confusion_matrix(res, res, labels=['tbatch_id','user_id', 'item_id', 'timestamp', 'state_label', 'comma_separated_list_of_features'])
    count = count + 1

f1.close()
