# Dog-Breed-Identification

I developed an algorithm that could be used as part of a mobile or web app to determine whether the image contains human, dog or neither. The algorithm returns the predicted breed if a dog is detected in the image or resembling dog breed if a human is detected. I used OpenCV's implementation of Haar feature-based cascade classifiers to detect human faces and Pre-trained VGG-16 Model for dog detector. Built dog breed classification convolutional neural network via transfer learning: initialized weights from the pre-trained ResNet50 model, re-trained the entire neural network with 8351 dog images by 30 epochs. Finally achieved an 85% test accuracy for dog breed identification.
### Step 0: Import Datasets
### Step 1: Detect Humans
### Step 2: Detect Dogs
### Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
### Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
### Step 5: Write Algorithm
### Step 6: Test Algorithm





| Input Algorithm with Human Images | Input Algorithm with Dog Images    |
|------------|-------------|
| <img src="https://raw.githubusercontent.com/muxiazhixing/Dog-Breed-Identification/master/images/human.png" width="290"> |<img src="https://raw.githubusercontent.com/muxiazhixing/Dog-Breed-Identification/master/images/dog.png" width="440" >|
