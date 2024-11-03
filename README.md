# ParkinsonsDetectionFromSpeech
WIP
Updating this project every week or so.

## 11/1/2024:<br/> 
**LOG**<br/> 
Just finished the first model for this project! it is linear regression, and with the base model we got 90% accuracy. still have a lot more we can change, but thats a good starting spot!


- [x] try linear reg - 0.9411764705882353
- [ ] try log reg
- [ ] try knn
- [ ] naive bayes (promising because of heatmap)
- [ ] decision trees and that whole mess
- [ ] SVM (need to reseawrch mroe)
- [ ] k means clustering
- [ ] NEURAL NETWORKS! (more research needed for this)


the biggest next step is to be able to convert audio into the file format that this model will be trained on! <br/> 
note: research paper should be at least avaliable before the end of next year! (hoping to get it published too)

## 11/2/2024:<br/> 
**LOG**<br/> 
finished a lot today, but because the dataset is really imbalanced, i had to learn how to balance it out(using smote). from now on the accuracy will be measured thru f1 score, because that is the most accurate and industry standard
i do feel like i cut a few corners, so there is a lto i can look at.

- [x] try linear reg - 0.9411764705882353
- [x] try log reg - 0.9230769230769231
- [x] try knn - 0.9180327868852459
- [x] naive bayes (promising because of heatmap) - 0.7931034482758621
- [x] decision trees and that whole mess - 0.9696969696969697
- [x] SVM (need to reseawrch mroe) - 0.9538461538461539
- [x] k means clustering (didn't even go thru with it, too weird)
- [ ] NEURAL NETWORKS! (more research needed for this)<br/>

decison trees  (random forest ensemble) is our current leader! <br/>
the future decisions for which model to pursue will be in like a deicision tree format, with the hghest base accuracy being the one i pursue.
<br/>
biggest issue is to make sure the models aren't overfitting, which I still need to make sure I do.
