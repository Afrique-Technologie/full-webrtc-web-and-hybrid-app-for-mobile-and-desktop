# A Hybrid Approach for WebRTC Video Streaming on Resource-constrained Devices
# University of Science and Technology of Oran - Mohamed Boudiaf (USTO-MB)
# Laboratory of Signals and Images (LSI)

This video conferencing solution based on WebRTC technology was implemented to conduct a comparative study between WebRTC solutions based on web browsers and those based on a hybrid application, on mobile and Raspberry Pi, as part of our PhD thesis "Implementation of a Video Conferencing Platform based on WebRTC Technology".    

It content:
1 - A web server implemented using the node.js and WebSocket frameworks.
2 - A responsive web client for desktop and mobile implemented using HTML5, CSS3, and JavaScript.
3 - A mobile hybrid client, compatible with Android, implemented using the cross-platform framework React Native.
4 - A desktop hybrid client, compatible with Windows, implemented using the cross-platform framework Electron Js.
5 - A desktop hybrid client, compatible with Raspberry Pi, also implemented using the cross-platform framework Electron Js.

The source codes of diffrent apps have been stored on Google Drive, you can download all of them through the following links.

1 - Server : https://drive.google.com/file/d/19U246M_AOhXKoMF6PBa1AlFeywfJkglv/view?usp=share_link

2 - WebRTC-React-Native-Heabrid-App  :  https://drive.google.com/file/d/1WMRZ7X5U4PPkS1HqTo1wDAZ7YaK9nDm1/view?usp=share_link

3 - WebRTC-Electron-Hybrid-App-For-Windows  :  https://drive.google.com/file/d/1lfaVW6oshWe9M3wJ4yA0JGSaQEyjPF3d/view?usp=sharing

4 - WebRTC-Responsive-Web-App : https://drive.google.com/file/d/19ggvTMvGym0cL__SBALo3rvAdI_LYN-7/view?usp=share_link

5 - WebRTC-Electron-Hybrid-App-For-App : https://drive.google.com/file/d/16saI8GDhjfUJHDhsZrGMgkHFSxkotkiu/view?usp=share_link

Before running any of the clients, start by running the server. To run the server, unzip the Server.zip file, then open the resulting folder in a terminal and type the command: node server.js
The server can run on Windows, Linux, or MAC.

To compile the React Native client, you must first set up the React Native development environment on your machine. Then, you must install the following React Native modules that are used in the application:                                                                                                      
1 - react-native-webrtc                                                                                                                                    2 - react-native-incall-manager
3 - react-native-easy-toast
4 - react-native-prompt-crossplatform
5 - react-native-background-job
The React Native application has been compiled only for the Android system, but it can also be adapted for the iOS system.

To compile the Electron application on Windows, install Electron on your Windows machine by following the reference below: https://www.electronjs.org/fr/docs/latest/tutorial/installation.
Then, open the "WebRTC-Electron-Hybrid-App-For-Windows" folder in a terminal and type the following command: $ npm run start

To compile the Electron client on Raspberry Pi, install Electron on Raspberry Pi using the following command:

$ sudo npm install -g electron —unsafe-perm=true —allow-root

Then, open the "WebRTC-Electron-Hybrid-App-For-Raspberry-Pi" folder in a terminal and type the following command:

$ npm run start


To test the application:

Start the server
Launch the web or hybrid clients
Assign a unique number to each client (for example, between 6000 and 6999)
Click the "connexion" button to connect the client to the server
Make a call to a client using its assigned number.

All of these four WebRTC clients are independents. You can use each of them separately with the server. For exemple, if you just need the code for the React Native hybrid mobile app, you can download the "Server.zip" file and the "WebRTC-React-Native-Heabrid-App.zip" file from google drive.

Here we give you the code for the different client applications that were needed for our thesis, but you can use them according to your needs. 

Thanks !
