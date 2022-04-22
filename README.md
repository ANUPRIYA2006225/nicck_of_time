# nicck_of_time

# Demo
[Drive Link (Presentation,Demo,APK)](https://youtu.be/slfq3XdERSw)

[Frontend - live link](https://chic-gecko-f6544c.netlify.app/)

[Backend - live link](https://test-anu1.herokuapp.com)



# Problem Statement
People are trying all options for education online, this type of education
has not gotten the desired response due to poor internet connectivity in
the remote and some areas of hilly districts in the state. Many times, stu
dents had to trek for a few kilometers in certain areas to get a proper sig
nal so that they could attend classes or submit their assignments and an
swer sheets online. So, we have to work on improving the services of ap
ps or enhancing the features of existing applications.
That’s why we have come up with a new application that improves acces
sibility in different ways. Through our app, we are able to submit scanne
d answer pdfs at the time of internet issues during exam time. So, we ha
ve got a solution in which students will have to download an app and just
have to send a shared key using message service of scanned pdf by pres
sing a button on our app which will be redirected to the SMS app, and no
w the student has to just click the send button of their message app.


# Solution
* The Teacher will create a group and add Students in it
* The Teacher will create a test and upload the pdf of question paper
* The app will encrypt the pdf with a password teacher entered at the time of uploading
* The encrypted question paper will be sent to the students beforehand (10-15 days before the exam)
* The password to the pdf will be sent to the students at the time of the test using SMS (Twilio API)
* The student will give the test and when the time is finished they will upload the pdf on the app
* If there's an Internet issue at student's end, A SHA256 key will be sent to the teacher
* When the problem is resolved at the student's end they can upload the pdf
* The app will verify the uploaded pdf with the submitted SHA256 key and if it is successfully verified the job's done!


# Frontend 
command to run : 
</br>

```js
npm install
</br>
```
```js
npm start
```
</br>


# for backend
# Backend
required credential are as follows:_
</br>
```
cloudinary-
</br>
    cloudname
    </br>
    apikey
    </br>
    apisecretkey
    </br>
    apikey = api-key
    apisecretkey = api-secret
Monogodb-
</br>
    mongourl
    </br>
    mongourl = your-mongo-url
Twilio-
</br>
    twilioauthtoken
    </br>
    twilioauthsid
    </br>
    twilioauthtoken = your-twilio-auth-token
    twilioauthsid = your-twilio-auth-sid
```

command to run : 
</br>
```
npm install
</br>
```
```
npm run dev
```
</br>

# for app
# For app
command to run :
</br> 
```
npm install
</br>
```
```
npm start
```
</br>
run on android/ios
</br>
Run on android/ios
