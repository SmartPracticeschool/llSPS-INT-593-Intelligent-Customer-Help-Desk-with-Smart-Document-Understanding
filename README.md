# llSPS-INT-593-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding
Intelligent Customer Help Desk with Smart Document Understanding Intelligent Customer Help Desk with Smart Document Understanding This is repository build with the help of Watson Assistant, Discovery, Cloud Function and Node Red app of IBM Cloud. It is made with the regard of partial fulfillment of Smartinternz Internship Program at smartbrigde

#Project Description : The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems. To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries. Scope of Work Create a customer care dialog skill in Watson Assistant Use Smart Document Understanding to build an enhanced Watson Discovery collection Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery Build a web application with integration to all these services & deploy the same on IBM Cloud Platform

In Watson Discovery I have added ecobee3_userguide.

Node-Red Dashboard link after deploying : https://node-red-znzdl.eu-gb.mybluemix.net/ui


Youtube video link is : https://youtu.be/tqHZXR5pY0c
Modified video link is: https://drive.google.com/file/d/1sG2-V58CvIdZNxCTmYwLdFqktn2oDO74/view?usp=sharing


The flow of node-red will found in NodeREDZNZDL-master/defaults section as flows.json file.

You can find the discovery manual and cloud function code and assistant skill file above.
