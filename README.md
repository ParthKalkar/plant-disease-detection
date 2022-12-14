# plant-disease-detection
In this project, I created a Convolutional Neural Network which predicts whether a plant is suffering from a disease. 

I used different layers and other hyperparameters for building, training and testing this classification model. 

## Scope
Human society needs to increase food production by an estimated 70% by 2050 to feed an expected population size that is predicted to be over 9 billion people. Currently, infectious diseases reduce the potential yield by an average of 40% with many farmers in the developing world experiencing yield losses as high as 100%. The widespread distribution of smartphones among crop growers around the world with an expected 5 billion smarpgones by 2020 offers the potential of turning the smartphone into a valubale tool for diverse communities growing food. 

One potential application is the development of mobile disease diagnotics through machine learning and big data. 

## Steps
1. Mounting google drive on collab notebook.
2. Visualizing the images that we will be working on.
3. Finding out the mean of the dimensions and resizing all images accordingly.
4. Converting the images intoa  numpy array and normalize them. 
5. Checking class imabalance.
6. Splitting the data and performing one-hot encoding.
7. Creating the model architecture, compiling the model and then fitting it. 
8. Plotting the accuracy and loss against each epoch. 
9. Pre-processing the test data and make predictions on it. 
10. Visualize the original and predicted labels for the test images. 

## Technology
1. Python
2. Tensorflow
3. Keras
4. Streamlit

## Run
Step to run application:

Step 1: Create the copy of the project.

Step 2: Open command prompt and change your current path to folder where you can find `main_app.py` file.

Step 3: Create environment by command given below: `$ conda create -name <environment name>`

Step 4: Activate environment by command as follows: `$ conda activate <environment name>`

Step 5: Use command below to install required dependencies: `$ python -m pip install -r requirements.txt`

Step 6: Run application by command: `$ streamlit run main_app.py `You will get url copy it and paste in browser.

Step 7: You can download a picture from the internet and upload it on the website, then click predict button to get the output.

## Interface
![image](https://user-images.githubusercontent.com/50231750/201531039-1b48322d-c55c-4e08-b81a-fb1a513fca13.png)

## Upload Image
![image](https://user-images.githubusercontent.com/50231750/201531092-c66507dc-9f5b-40d2-a030-05d7b2bdcc3b.png)

## Input
![b475147c-92bc-419a-b2c3-7d5aabbb79ec___RS_Early B 7379](https://user-images.githubusercontent.com/50231750/201531305-3915b353-cb61-4ab1-be7c-8c9daf0725da.JPG)

## Output
![image](https://user-images.githubusercontent.com/50231750/201531133-a27ac400-e8cf-4246-a1c9-d170f1e42aa9.png)

## Accuracy
![image](https://user-images.githubusercontent.com/50231750/201531374-723169b2-8ef5-416a-9d7c-d7e6a84a5497.png)

## Conclusion
We started with loading the dataset into google colab using google drive and visualizing the images. Normalizing is an important step when working with any type of dataset. After that we created a CNN Model which is further used for predicting the plant diseases using the image supplied to model. This model is highly beneficial as it can be used by different agricultural firms and farmers to increase their yield and stop wastage of crops due to disease.
