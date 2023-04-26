# full-webrtc-web-and-hybrid-app-for-mobile-and-desktop

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

1 - react-native-webrtc
2 - react-native-incall-manager
3 - react-native-easy-toast
4 - react-native-prompt-crossplatform
5 - react-native-background-job
The React Native application has been compiled only for the Android system, but it can also be adapted for the iOS system.





All of these four WebRTC clients are independents. You can use each of them separately with the server. For exemple, if you just need the code for the React Native hybrid mobile app, you can download the "Server.zip" file and the "WebRTC-React-Native-Heabrid-App.zip" file from google drive.

Here we give you the code for the different client applications that were needed for our thesis, but you can use them according to your needs. 
