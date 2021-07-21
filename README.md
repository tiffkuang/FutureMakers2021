# FutureMakers2021

### Tiffany Kuang
### July 10, 2021
### Team 8

## Reflection Responses

Day 3
1. Supervised learning is when the machine receives both the data points and labels, and learns from feedback. There are two main types of outcomes in supervised learning: regression and classification. In unsupervised learning, the machine only receives data points and is expected to learn from patterns, such as clustering, rather than feedback.
2. The statemnt "Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries" is false because Scikit Learn is not focused on manipulating or visualizing the data. Instead, Scikit-Learn is used only for machine learning calculations and models. The other libraries, such as NumPy, Graphviz, and Pandas, is used to visualize the data.

Day 4
- I looked at 3 different types of facial datasets: Large-scale CelebFaces Attributes, Labeled Faces in the Wild by UMass-Amherst, and Flickr Faces HQ Dataset. 
1. In the Large-scale CelebFaces Attributes database, I see that a majority of the images are of white young adult females or older white males. These pictures date back about a decade. There are only a small percentage of people of color in these images. Additionally, a portion of these iamges contain photoshop editing. However, this database has a variety of features that are specific to the images, such as images of people with sunglasses, hats, bangs, oval faces, and pointy noses. Although there is a variety physical features specific to a group of images, the database still lacks a diverse range of ethnicities. 
2. In the Labeled Faces in the Wild by UMass-Amherst database, it contains mostly older white people, including well-known athletes, celebrities, and men in tuxedos. There are only a few people of color, but all of them are celebrities. All of these iamges are taken off-guard as none of them are headshots. All of the younger white females had brown hair. All of the older white females had short blond haircuts. One thing that this dataset had that the others didn't were images of twins. This dataset lacks diverse images from the present, and diversity within each set of images. For example, the dataset could have included younger females with different hair colors other than brown. 
3. The Flickr Faces HQ Dataset was by far the best and most diverse dataset out of the three datasets. It contains pictures of all ages, from babies to grandparents. It also contains pictures of a diverse range of ethnicities, including caucasians, east asians, and africans. Individuals had different kinds of hair, inlcuding bangs, unusual colors, no hair, and hair accessories. It also included images of different religions, social status, and locations. However, all of these images appear to be headshots instead of off guard. The faces in these images are clear whereas the background of these images are blurred. 
  

Day 7
1. Tensors are multidimensional arrays. It is essentially inputted data with a certain amount of features. In Machine Learning, tensors are used to quicken the process because with tensors, the feature doesn't have to be passed over and over again. Instead, tensors combine all of the data points into a single matrix that is only called once.

Day 10
1. Machine Learning and AI concepts were utilized in the firing and hiring process of the game. Initially, when I had to choose whether or not to hire or fire the candidates based on a certain number of characteristics given, the model learned from my feedback and choices. Then, when I uploaded the file with all of my previous choices, and combined this dataset with a larger one from Google, the model had enough data to train itself and create accurate results based on my preferences. 
2. An example of a biased machine learning model would be facial recognition technology. Facial recognition has discriminated against people of color due to the lack of diverse images within datasets for the machine to practice. These datasets often include white males. To make this model more fair, inclusive, and equitable, we need more diversity (gender, sex, ethnicity, religion, etc.) in our dataset. People of color are constantly being discriminated against due to the flaws of the algorithm and it is becoming increasingly dangerous. I read too often about darker skinned individuals who have been falsely accused of crimes they didn't commit or being accused of being a terrorist becuase of their religion. Although technology is becoming more and more advanced, it seems as if society is taking steps back in becoming more equitable and safe. 

Day 15
The advantages of using the Rectified Linear Activation Layer is that it is incredible simple to compute. It requires a max() function whereas the tanh and sigmoid activation function must be written out entirely. Another advantage of using the Rectified Linear Activation Layer is that it can output true zero values when given negative values, which is called Representational Sparsity. This helps the model learn faster and simpler. The tanh and sigmoid activation functiona are unable to produce a true zero value, only a value very close to it. The Rectified Linear Activation Layer also has linear behavior which allows the neural network to optimize easier when the behavior is linear. Lastly, the Rectified Linear Activation Layer makes it possible to train deep multi-layered neural networks with a nonlinear function using backpropogation. 
One case the Rectified Linear Activation Layer is used for is CNN because of its simplicity to implement with large datasets, representational sparsity, and requires less computational power. 
