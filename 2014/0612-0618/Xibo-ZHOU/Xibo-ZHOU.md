Period:20140612 - 20140618

Name: Xibo ZHOU

Planned target:
1. Cross validation between UFLDL and DeepLearnToolbox: SAE & Linear Encoder
2. Paper presentation: two papers related to ImageNet competition 2012 & 2013
3. Coursera: Data Scientist's Toolbox (Week 1, 2 & 3)

Actual progress:
1. [60%]SAE finished
2. [100%]Done
3. [100%]Done

Remarks:
1. Traveled to Nansha with LIU Hao from 06-13 to 06-14. Checked the server newly bought by DLRC. Contacted with the provider and reported the problems. Got the document for fixing the problem. Planning to find an engineer in DLRC to help fix it by tomorrow.

2. Found a problem with the UFLDL machine learning code. For softmax classifier, both UFLDL and Toolbox code works fine with the MNIST data. However, the UFLDL code couldn't work with the data given by Ding Ye, but the Toolbox code works fine. The detail is that when training with fmincg or lbfgs function, the iteration soon runs out of bounds and terminates after one or several cycles, while the result is far away from expected accuracy. Still haven't sovled this problem yet.

3. Still haven't fix the problem of output generating. Planning to rewrite the previous code to formalize this issue.

4. Recieved 10 USB disk from DLRC. Copied the systems and fixed the broken nodes in the cluster.