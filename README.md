# HackSC AI Healthcare Assistant
## Inspiration
The project draws its inspiration from a commitment to enhance patient safety.

It aims to reduce errors during prescription of drugs especially that could happen due to communication barriers or human erros and also provides accessibility to people from different communities who may speak different language from the available physicians. It is an assistant for doctors, patients and community workers alike.

We build it using Android SDK and the backend is written with Python & Flask. We also integrated Redis to store patient and Doctor details and additionally, make use of Google CLoud technology to deploy our backend system.

## Challenges we ran into
Limited public datasets for the medicine chemical composition. Also, lack of patient and doctor appointment transcript datasets, which made it difficult to create a model that could compare the appointment transcript and the prescription.

## Accomplishments that we're proud of
The app functions as expected, allowing us to record and transcript appointment conversation between a general physician and a patient. We have deployed our backend to cloud, and the algorithm raises flags in prescription based on publicly available dataset.

## What we learned
We have learned about patient safety and problems that are faced today especially by marginalized communities.

## What's next for AIHealthAssistant
Lost of possibilities, first and foremost we can improve the backend to an ML model which can give more information regarding why it raised a flag, can be more accurate and also the app can be expanded using patient history and tracking of patient allergies or precious reactions.

## Built With
android-studio
api
flask
gcp
google-web-speech-api
java
python
redis
rest

[Link to Backend repo](https://github.com/Adishar93/PrescriptionValidator)

![Landing Page](https://github.com/Adishar93/AIHealthcareAsistant/assets/39119745/93a71950-50fa-451e-acd6-e34cfed14c81)
![Login Page](https://github.com/Adishar93/AIHealthcareAsistant/assets/39119745/686a8de4-26b4-48a4-8fc9-1fe96010b425)
![Doctor can record appointment, enter prescription and verify using the model if there are any potential flags in the prescription:](https://github.com/Adishar93/AIHealthcareAsistant/assets/39119745/1d81bd9d-9066-435a-866a-a625fb970668)



