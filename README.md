# Quiz-er
Web Site Project for making Quiz easily


## Abstraction

These days, there are so many QUIZ-generator website. But they are often limitive. Too complex or too simple, too hard or too easy.

My Goal is to make quiz generator site that supports easy upload with randomized order, multiple quiz form.

## Dev Environments

AWS Web Hosting

Frontend : HTML5, CSS3, JS, React

Backend : NodeJs

DB : MongoDB (NoSQL)

## Overall Plan

### homepage

Main page. You can make new quiz or start another quiz.

### quiz uploader

Quiz generator. Can make new quiz project and upload information.

When injecting information, you can choose which img to upload, type of Q, Answer and Wrong Answer... and Group Option that will be used to diffuse user

Each Quiz Project will be saved in a collection, and each question will be saved in a document.

Picture will be saved in FS, in each Directory

### Quiz start

Main Quiz. For each Interval, Question is delivered from DB, and shown.

Each Question div goes to DOM, when true answer is selected, score increase.

(LeaderBoard is not in consideration)
