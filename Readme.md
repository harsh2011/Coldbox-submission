# ColdBox
Two decades ago, we were more connected with Nature. People were living simple lives under the hood of nature without having major health issues like diabetes, Thyroid, Blood Pressure. Life was comforting even with the lesser money. As we entered the 21st century, revolution started to begin in all the sectors. We started to lose connection with Nature and started living more artificial life which affected majorly on our health. Having Diabetes, Blood Pressure, Thyroid, Osteoporosis, Cancer, TB, Viral infections became generic. Currently, in India, more than 17 Lakh people die every year due to heart diseases and by 2030, the figure is expected to increase with 2.3 crore deaths.

For having good health, the first and foremost thing is to know that we do not have any disease. For senior citizens, it is suggested to have a regular full body profile checkup every month. For the new born babies, it is mandatory to follow the full vaccination program so that their immunity becomes stronger as they grow. The Government of India is organizing a lot of child immunization programs to spread awareness all over India. 

Coming to the problem that we want to solve, first we want to throw a light on the two issues that we’re facing right now. For example, a person wants to have a laboratory medical test. For that, he has to go to the nearest pathology laboratory or hospital.After the tests are done, he also again has to go to collect the sample results. Now, for doing the same task he has to go twice to the laboratory which is not efficient. Similarly, for the new born babies, parents must vaccinate their child. Usually, the vaccination cycle continues till 12 months where they need to visit Pediatrician every month. Usually, vaccination is done by nurses in the nursing home. In metro cities, where both the parents are working, it becomes very difficult to adjust the timings which is suitable to the nursing home for their child or Maybe, sometimes because of their busy schedules, there comes the delay in vaccination or they might forget since no one is going to call them to remind about the next vaccination date. 

After the global pandemic hit over the world. It is always suggested to remain at home especially for senior citizens and new born babies. Due to which, there is a strong need of doorstep lab tests and vaccination at their needs. We’re introducing our app “COLDBOX ”. A medium between citizens and laboratories and pediatricians.  ColdBox is an android application which provides doorstep vaccine or lab test service. Users can select nearby pediatricians or any laboratory, request the tests that they want to be done.  Pediatricians/Laboratory will see the requests and confirm the requests according to resources. While confirming, they’ll allocate the contact information of paramedics who will come certain period of time to the user's house and collect the samples. After collecting, users will get the test results in their application. 

In conclusion, ColdBox is designed in such a way that it is useful for citizens of all ages. After using the ColdBox, they will be able to compare the prices of medical tests so they can choose the best options accordingly. They will get in-house service for all the tests which can ease and fasten the process of laboratory testing. Hence, COLDBOX can be the revolutionary option in the laboratory testing field.

## Benefits of Application
* Help the mission of “Local to Vocal” by Govt. Of India. Since it will showcase medical laboratories filtered by location. So even a small-sized medical laboratory can grow their business using our application.
* No more long queues at laboratory chambers. No more waiting required.
* It’s difficult to track a child's upcoming vaccination dates according to IAP schedules. ColdBox will give timely reminders for that. So no more missing out.
* Our expert vaccinators will come at your home as per your comfortable time. So everything is at your ease and comfort.
* No more exposure to your kid or to yourself to other patients in waiting areas of the laboratory.
* Gives more opportunities to the paramedic industry. The vaccination/ medical tests will be done at home. Laboratories will need more people at service which can help to create more jobs in the nursing/paramedic industry.

## Development Phase

|Start          |End	|Brief	| Details explained|      Status|
| ------------- | ------------- | ------------- | ------------- | ------------- |
|29-June	|30-June	|Create project and intergration with firebase	|Start project with flutter,(cross platform), but right just focus on developing for Android Platfrom. And integration with firebase of user login and register , and to store all the date on firestore |	Done |
|1-July	|3-July	|Login and Registraction screen for user and pediatrician/laboratories	|Implementation of login and registeration for user and  pediatrician/laboratories. <br> -> Login with email and password  for user and  pediatrician/laboratories. <br> -> Registeration with email and some extra details like. address, name etc for user and pediatrician/laborartories|	Done |
|4-July	|5-July	| Add screen for pediatrician/laboratories to view the list of vaccine and medical test that they have added and To add more vaccine and medical test in their list| Implementation of medical test and vaccine list  for pediatrician/laboratories. <br> -> Viewing currently added vaccine and medical test <br> -> Adding new vaccine and medical in their list |	Done |
|6-July	|8-July	|Add screen where user can select the pediatrician or laboratories , and request a appointment of vaccine and medical test |Implementation of screen for selection of pediatrician or laboratory on that specific pediatrician user can select a vaccine and on that specific laboratory user can select a medical test for appointment. This whole process will create a request which will have a link between users and pediatricians/laboratories. Request will have have details of user home address location and user will have to added Pateint name. <br>-> Request will have details like (vaccine_id/medical_test_id, company_id, price, createdAt, userLocation, status)<br>Note. initial status of request will be pending....|	Done|
|9-July	|10-July	|Add screen where pediatrician and laboratories can edit the status of request of appointment| Implemetation of screen for editing request status<br> -> Request status change to In process.., where pediatrician or laboratory can assign a nurse for appointment (so they have to add nurse_name and nurse_mobile_number)<br>-> Request status change to Done.., where pediatrician or laboratory can set it to done after confirmation with nurse|	Done|
|11-July |13-July	|Add location for users and pediatrician/laboratories in there details. 	Implemenation |will add google maps, which helps to pick the exact location of  pediatrician or laboratory and user, which will help it the time for location base search and for appointment|Done|
|14-July	|17-July	|Add report results in request added by the laborartory	|Implementation of a screen, which help laboratries to upload the report on application, so user doesn't have to go for collecting it|In process |
|Not decided	|Not decided	|Integration of FCM	Integration of FCM for push notification in application. |Saving the FCM token of user and pediatrician/laboratories in firestore database|	Pending|
|Not decided	|Not decided	|Add notification for pediatrician and laboratories when request for appointment is created	|Implemetation of push notification when a request is create for pediatrician/laboratories for appointment	|Pending|
|Not decided	|Not decided	|Add notification for user when request status changed	|Implemetation of push notification when a request is status change for user for appointment|	Pending|
|Not decided	|Not decided	|Add location base filtering of pediatrician and laboratories for user, and even search by name 	| Implemetation of google map to point out the location of pediatrician/laboratories from the user perspective, and also search of  pediatrician and laboratories by there name.|Pending|
|Not decided	|Not decided	|Testing	|Testing for 10 - 15 people	|Pending |
|Not decided	|Not decided	|Development	|Developing it to play store for public use| Pending |

# App Info
* Framework: Flutter
* Platfrom : Android
* version : 1.0.0

