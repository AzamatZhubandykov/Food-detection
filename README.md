# Food-Recognition
The most common waste on our planet is food. About 50 tons of food is thrown away every second in the world. Every year, one and a half billion tons of such waste is sent to landfills and pollutes the environment. Food waste is very dangerous for the environment and decomposes quickly. They produce methane, a greenhouse gas that is 20 times more powerful than carbon dioxide. Moreover, time after time, they take up more and more space.
The main problem for Food Recognition is that most images of food on the Internet are fake and used only for commercial purposes. Same thing on Instagram and other Social media apps, we tend to share beautiful photos of dishes with our friends and family. If we will use these photos for training, our model will be overfitting.
Every model was trained on same conditions. We were using Stochastic Gradient Descent as an optimizer, where learning rate, momentum, and number of epochs were equal for each architecture. By means of that, we could figure out the best one for our Food-11 dataset. 
We mostly carried about architecture performance on the test part. We were looking for the lowest loss and highest accuracy score on test dataset, so we decided to pick InceptionResNetV2. Model weights were downloaded to apply it in our Web Application. 

![](2.png)
![](3.png)
![](4.png)
![](5.png)
