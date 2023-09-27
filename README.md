This is a **collaborative project**

We live in an era where many security protocols are prevalent. All important organizations such as banks, factories, or warehouses have some security measures involving the identification of personnel, usually in the form of RFID cards or passcodes. Such methods prevent public access to private areas responsible for storing valuable objects and sensitive information. It is in the best interest of organizations that only select important individuals having appropriate credentials are allowed to enter these areas. There have been several incidents of tailgating where hackers, spies, and criminals got hold of User ID cards and passcodes which were used to intrude into restricted areas. Biometric identification currently provides the best solution as it is impossible to copy features like fingerprints and faces which are unique to every individual. We have decided to work on the problem of Face Recognition for Security and have implemented three CNN models based on the quality and quantity of face images: the Simple CNN model, the Super Resolution CNN model, and the Siamese CNN model. For training the models, Living Faces in the Wild Dataset has been used and we have created several subsets like individuals having at least 50 images, images are pixelated, and individuals having only 10 images. We have found Simple CNN to be quite effective when we have lots of good-quality images to train for one person, however, Super Resolution CNN works best with low-quality image data and Siamese CNN performs best when working with small training samples. We have found the accuracies to be 86.44%, 91.34%, and 92.57% respectively, and for further investigation, we would want to incorporate our SR-CNN model with Siamese architecture to work with low-quality images having a small sample size.
