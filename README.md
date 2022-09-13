# SmartBin: An Automatic and Informative Waste Management System

Pollution is a prominent problem affecting every living being. An eminent constituent of pollution generation is waste produced in daily activities. With the increasing population, generation of waste is increasing exponentially. Even though most of the houses have dustbins, the sanity is still not maintained when it comes to the larger bins kept for public garbage/waste collection. Waste Segregation is mostly done manually that increases labor and its human error which leads to half of the recyclable waste going unnoticed with other waste, eventually losing the chance to recycle it. Main aim is to reduce the human work and help the environment in a better way. So, the project also features a solution for segregating the waste at the dump yard for a better environment. This can help in categorizing the waste into 4 main categories, which are Organic, Non-organic, Plastic, and Recyclable. Through the proposed project we hope to reduce the human labor and improve the waste segregation for environment sustainability.

# Methodology

Individuals can open the lid of the dustbin without touching it. It is made possible using ultrasonic sensor wherein movement of hand at a certain distance will automatically open the lid for the user. The additional features includes waste level detection. When the dustbin reaches its 80% capacity, the workers appointed for it will be informed to clean the bin. Apart from it, if the bin reaches 80% of its volume, then the lid will remain close for the public and a red led will indicate that the bin can no longer be used, preventing the waste from overflowing.

 <div align ="center">
  <img src="https://github.com/nidhigandhi125/Waste-Segregator/blob/master/waste-meth.png" alt="methodology" width="800" align="center"/>
</div>

There are two phases i.e. training phase and functional phase. The input is taken from the custom dataset named TRASH. In the training phase, the first step after loading the TRASH dataset is to pre-process the input image that is fed to the model. Various pre-processing techniques modifies the image to a target size of 64 X 64 and other data augmentation techniques are also used. Next the data is fragmented into training and testing data. The Keras library is used to build a Convolutional neural network (CNN) which takes the training and testing data and generates a model. This model is to be used in the other phase, called functional phase. In this phase, input is fetched from the images uploaded to the dataset. Different types of images are uploaded which helps in training the model. 

 <div align ="center">
  <img src="https://github.com/nidhigandhi125/Waste-Segregator/blob/master/smartbin_model.png" alt="methodology" width="400" align="center"/>
</div>

# Results 

 <div align ="center">
  <img src="https://github.com/nidhigandhi125/Waste-Segregator/blob/master/result%20.png" alt="methodology" width="400" align="center"/>
</div>
<br/>
Overall, the proposed architecture to reach to an average of 80% accuracy in identifying and segregating the waste into its respective categories. 

# Conclusion 

The project will decrease the level of contamination, and hence will be the first step towards recycling. All this together will lead to a cleaner environment, less human interference and minimum efforts for handling the waste correctly. The system provides a better solution in order to reduce the tedious process of waste collection and takes forward the goal of smart cities by introducing these smart dustbins. 

  
