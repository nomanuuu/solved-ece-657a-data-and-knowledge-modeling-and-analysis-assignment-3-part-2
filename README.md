Download Link: https://assignmentchef.com/product/solved-ece-657a-data-and-knowledge-modeling-and-analysis-assignment-3-part-2
<br>
<strong>Feature Extraction, Classification, Deep Learning and Regularization</strong>

<h1>Overview</h1>

<strong>Collaboration:</strong>

<ul>

 <li>You can do your work alone or in pairs.</li>

 <li>You can collaborate on the right tools to use and setting up your programming environment, but each team must produce their own code, report and kaggle submission.</li>

 <li>If you are working in a pair, report your team on this spreadsheet: https:</li>

</ul>

//bit.ly/2QBixDQ

<strong>Hand in:</strong>

<ul>

 <li>One report per team, via the CROWDMARK site in PDF format. You will need to divide the PDF up into multiple 3 files and drag and drop each onto the relevant question. You should receive an invite to crowdmark by email. You can write the report in any tool you like, it does not need to be a printout of a notebook. It can be created with LaTeX, Word, google docs or anything you like. As long as it is clear and readable with your analysis and plots saved as a pdf.</li>

 <li>Also submit the code/scripts needed to reproduce your work as a python jupyter notebook to the LEARN dropbox.</li>

</ul>

<strong>Broad objectives:</strong>

<ul>

 <li>Experiment with feature extraction methods to process image data and use classic data analysis and machine learning algorithms</li>

 <li>Set up and train a small Convolutional Neural Network in python tensorflow for classification.</li>

 <li>Compare the results of the methods used.</li>

</ul>

<strong>Tools: </strong>You can use any libraries available in python, tensorflow, keras, scikitlearn for this project. You need to mention explicitly which libraries you are using, any blogs or papers you used to figure out how to carry out your calculations.

<h1>Data Set – Fashion MNIST … with a Twist</h1>

An image dataset based on ”Fashion MNIST”. The input features will be the same but the *label* you will be using will be new, something we have computed and created based on the data. The same dataset is hosted on two seperate Kaggle competitions for the class only. The only difference between the two is that Part 1 is for non Deep Learning based solutions, and Part 2 is for Deep Learning (ie. CNN) solutions.

<ul>

 <li>Part 1:</li>

</ul>

∗ Pulic link: https://www.kaggle.com/c/ece657a-w20-asg3-part2/ overview

∗ To join: https://www.kaggle.com/t/e89aaf2776124cfd91f9b60729e9d2e3 <strong>– </strong>Part 2:

∗ Public link: https://www.kaggle.com/c/ece-657a-w20-asg3-part-1/ overview

∗ To join: https://www.kaggle.com/t/80ab6ed9101f486aa7fa738a5504982c

<strong>Other links:</strong>

<ul>

 <li>Link to another public Kaggle that works on the original Fashion MNIST and shows lots of things that can be done. <a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a></li>

 <li>Original FashionMNIST Kaggle<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a></li>

 <li>Python setup – for this assignment you can any python following packages that are useful, you should focus on scikitlearn, keras, tensorflow.</li>

</ul>

<h1>Question 1: Classification: Feature Extraction + Classical Methods (40 points)</h1>

<h2>1.1: Explanation of Design and Implementation Choices of your Model (15 points)</h2>

Describe the underlying algorithms you are using, how they work and why you chose them.

<h2>1.2: Implementation of your Design Choices (5 points)</h2>

Show some of the important code blocks to implement your model. We will also consult your full code on LEARN, so this is your chance to guide us to understand your code and how you acheived your result.

<h2>1.3: Kaggle Competition Score (5 points)</h2>

Report the highest score your submissions received on Kaggle. If you have any explanations for varying performance by different teams explain it here.

<h2>1.4: Results Analysis (15 points)</h2>

<ul>

 <li>Runtime performance for training and testing.</li>

 <li>Comparison of the different algorithms and parameters you tried.</li>

 <li>Explanation of your model (algorithms, design choices, numbers of parameters)</li>

 <li>Use a <strong>ROC curve </strong>used for some method in your initial or results analysis such as exploring the impact on accuracy of some parameter.</li>

 <li>Evaluate your code with other metrics on the training data (by using some of it as test data) and argue for the benefit of you approach.</li>

</ul>

<h1>Question 2: Classification : Convolutional Neural Networks (60 points)</h1>

<h2>2.1: Design and Implementation Choices of your Model (25 points)</h2>

<ul>

 <li>Use some CNN-based approach to solve the classification problem. You can explore any architecture of the network you like.</li>

 <li>You should also consider exploring other ML methods and Deep Neural Network varirants to solve the problem, cite sources you used : library, as well as papers or blogs. (eg. can the use of Resnet learn a better classifier than a simple CNN?)</li>

</ul>

<h2>2.3: Implementation of your Design Choices (10 points)</h2>

Show some of the important code blocks to implement your model. We will also consult your full code on LEARN, so this is your chance to guide us to understand your code and how you acheived your result.

<h2>2.4: Kaggle Competition Score (5 points)</h2>

Report the highest score your submissions received on Kaggle. If you have any explanations for varying performance by different teams explain it here.

<h2>2.5: Results Analysis (20 points)</h2>

<ul>

 <li>Runtime performance for training and testing.</li>

 <li>Comparison of the different algorithms and parameters you tried.</li>

 <li>Explanation of your model (algorithms, network architechture, optimziers, regularization, design choices, numbers of parameters)</li>

 <li>You can use any plots to explain the performance of your approach. But at the very least <strong>produce two plots</strong>, one of <strong>training epoch vs. loss </strong>and one of <strong>classification accuracy vs. loss </strong>on both your training and test set.</li>

 <li>Evaluate your code with other metrics on the training data (by using some of it as test data) and argue for the benefit of you approach.</li>

</ul>

<a href="#_ftnref1" name="_ftn1">[1]</a> https://www.kaggle.com/fuzzywizard/fashion-mnist-cnn-keras-accuracy-93/

<a href="#_ftnref2" name="_ftn2">[2]</a> https://www.kaggle.com/zalando-research/fashionmnist