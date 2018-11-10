## NYU DS-3001 Machine Learning Project.
#Topic# Image_synthesis with DCGAN,  WGAN-GP

Collaborator: Lifan Wang,  Guanhua Chen,  Kuan Chen  

## Instruction
This project aimed to use cifar10, mnist, customized dataset to generate new images
 
Load the *.ipython file within each folder and reproduce the result. 

## Datasets
We built our WGAN model from MINST, CIFAR-10, Unknown dataset.   

## Results
The network would generate fake images during the training process, they are stored in the folders.  

Mnist:　　　　　　　　　　　　　Cifar10:　　　　　　　　　　　　　Comic faces:

<img src="mnist_dataset/3000.png" width="256px"/><img src="cifar10_dataset/60000.png" width="256px"/><img src="faces_dataset/3500.png" width="256px"/>

## References
WGAN-GP https://zhuanlan.zhihu.com/p/25071913  
Comic faces https://cloud.tencent.com/developer/article/1055514  
[1]IanJ.Goodfellow,JeanPouget-Abadie,MehdiMirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. Generative Adversarial Networks. arXiv:1406.2661   
[2]MartinArjovskyandSoumithChintalaandLonBottou. Wasserstein GAN. arXiv:1701.07875, 2017.   
[3]Alec Radford, Luke Metz, Soumith Chintala. UnsupervisedRepresentationLearningwithDeepConvolutional Generative Adversarial Networks. arXiv:1511.06434   
[4] Xin Guo, Johnny Hong, Tianyi Lin, Nan Yang. Relaxed WassersteinwithApplicationstoGANs. arXiv:1705.07164  

