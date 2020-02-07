# Authenticating-User-using-Gestures

The aim of the project is to authenticate a user using gestures. The organisation wants to completely remove the use of keyboards to enter pin and instead wants the user to enter the pin using hand gestures due to security reasons. This project has been built using deep learning and convolutional neural network technologies with 4 hidden layers in the neural network. Our model has been trained to verify a user based on a few gestures and based on that give the account details of the user. We have built a prototype of the project which has been trained to recognize 2 getsures as of now.

Following is the list of gestures:
1) L: 1
2) Peace: 2

Following are the list of files attached:
1) Faculty Evaluation Q and A: It consists of the response to the faculty question
2) Faculty Presentation: It consists of the presentation of out project. This is in form a google drive link as it couldn't be              uploaded due to its large size. 
3) Demo of the project: It consists of the final demo of the working prototype. Certain files have been used in the demo. The files would be uploaded as a google drive link and would be shared here. In order to run the files ensure everything is included in the same directory.


The VGG_cross_validated.h5 consists of the trained model which would be uploaded on google drive due to large size.
SIH Database.csv consists of the database of users having the bank account


When running the model on a local machine, ensure that while clicking photographs of the gestures, there is white backgroud. Results can vary due to noise or shadows in the background

The app is ready and only part left is integeration with this system. Screenshots of the app are attached below.

![photo6190536509657033020](https://user-images.githubusercontent.com/57843558/74012883-455d4180-49b1-11ea-95f3-1a5db13f8966.jpg)

When the app is opened, this screen opens first.

![photo6190275457249815004](https://user-images.githubusercontent.com/57843558/74013181-e1874880-49b1-11ea-9e35-430bfb075901.jpg)

The user enters his account number. Once the account number is verified, the user is asked to enter the pin.

![photo6190536509657033021](https://user-images.githubusercontent.com/57843558/74013578-cff27080-49b2-11ea-9ea2-16f890e29d89.jpg)

User clicks on the take picture button and then the camera opens.

![photo6190536509657033018](https://user-images.githubusercontent.com/57843558/74013748-2f508080-49b3-11ea-8e04-30a434934431.jpg)

User shows the corresponding gesture to the number he has to enter in the pin. The gesture gets recorded. For security reasons the app can store only one gesture at a time. The user again has to click on the take pictue icon to enter the second number of the pin. The first gesture would get deleted and then user would be able to enter the second getsure.

Lets assume the user has enetered the pin using the two getsures L and Peace. The pin that has been enterend is shown in the backend code and the screenshot has been placed below. The black and white image denotes what the computer sees.

![Screen Shot 2020-02-07 at 4 09 38 PM](https://user-images.githubusercontent.com/57843558/74022864-6e3b0200-49c4-11ea-907f-668f36b8a1d7.png)

From the above image its clear that user has entered pin as 1111. Once the 4 digit pin has been entered a GUI window opens which has been created using Tkinter library in Python. The window acts as the frontend. The screenshot for the same is shared below.

![Screen Shot 2020-02-07 at 4 15 22 PM](https://user-images.githubusercontent.com/57843558/74023221-236dba00-49c5-11ea-8aa2-776f73153e18.png)

Once the user clicks on the Details button, a message box opens which gives the account details namely user's name and the account balance as shown in below screenshot.

![Screen Shot 2020-02-07 at 4 18 24 PM](https://user-images.githubusercontent.com/57843558/74023383-8c553200-49c5-11ea-92d5-bf2d02570704.png)

In case the pin entered is wrong or the account is not found, the message box would display "Account Not Found"
