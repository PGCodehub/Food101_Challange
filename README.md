# Food101_Challange

Break the SOTA accuracy of 80% on Small Resnet50 based arch using advanced ONE POLICY learning techinque and lot of regularization methods to get a accuacy of 87.9 on a same test set as authors

Trained a Image Classifier that can  recognise food from 101 categories 


The datset on which it was trained on was https://www.vision.ee.ethz.ch/datasets_extra/food-101/ 

was very difficult dataset to work becuase of the 

Food-101 is a challenging dataset consisting of 101,000 images of 101 different food classes. Taking a look at some of the images,

![Bread Pudding in dataset](https://drive.google.com/file/d/1DlUX8UHVubAKTakaqwr0N7xfPgQQhjQ1/view?usp=sharing)

And as you can see all the images are of bread pudding , even humans tend to mis interpret.
we can see why models may struggle to get good results.


The creators of the dataset left the training images deliberately uncleaned, so there are a number of mislabelled images, and as we can see, a large range in brightness / colour saturation. More fundamentally, however, it’s clear that no two bread puddings are quite alike (or at all alike it seems). Classifying images with such high intraclass variation is hard.

If our model is to perform well “in the wild”, it needs to be able to handle these issues: real, non-professional photos of food aren’t going to be of uniform size and are unlikely to have perfect lighting or framing.



Present SoTa models like InceptionV3 has a top1 % accuracy of 88.8% and

other unqinue architectures has achieved a litttle higer accuracy of 990% 

With Rstnet model most models whose accuracy is above 90% has used 200 layers or more So to get that level of accuary on Restnet50 we need to use wide varaiety of  regularisations 
