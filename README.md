# meetUsProject
This repository intends to guide the API Rest endpoint that will be used for the project.

## Arquitecture



## Workflow

This is the main workflow in which all the app is based on.

![Main workflow](/images/principalWorkflow.png)

As an user app, you could follow three functionalities that will allow manage the meetings. 

## 1.1 Creating a meeting

The process is quit easy. The only steps that an user has to follow are: 1) Look for participants. 2) Choosing a place from the list. 3) Choosing date and time for meeting. 4) Clicking the create bottom and done! User has created his first meeting. The app sends as much invitations as participants the meeting has. These have to be answered in 15min. After this time, the invitation for a single participant is rejected and the app will recalculate nearby places for meeting.

![Creating meeting](/images/creatingMeeting.png)

## 1.2 Managing invitations

Once the invitation has been sent to the participant, it is his duty to answer. To do so, the participant user enters the app invitations list. Then, select the invitation he would like to see and then accept or reject the invitation. If an invitation is not answered within 15min, it is automatically rejected.

![Managing invitations](/images/managingInvitation.png)

