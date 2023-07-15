# A Hybrid Approach for WebRTC Video Streaming on Resource-constrained Devices
# University of Science and Technology of Oran - Mohamed Boudiaf (USTO-MB)
# Laboratory of Signals and Images (LSI)

The video conferencing solution based on WebRTC technology was implemented to conduct a comparative study between WebRTC solutions based on web browsers and those based on a hybrid application, on mobile and Raspberry Pi, as part of our PhD thesis titled "Implementation of a Video Conferencing Platform based on WebRTC Technology".

The implementation included the following components:
1. A web server implemented using the Node.js and WebSocket frameworks.
2. A responsive web client for desktop and mobile implemented using HTML5, CSS3, and JavaScript.
3. A mobile hybrid client compatible with Android, implemented using the cross-platform framework React Native.
4. A desktop hybrid client compatible with Windows, implemented using the cross-platform framework Electron Js.
5. A desktop hybrid client compatible with Raspberry Pi, also implemented using the cross-platform framework Electron Js.

The source codes for the different applications have been stored on Google Drive. You can download all of them through the following links.

1 - Server : https://drive.google.com/file/d/19U246M_AOhXKoMF6PBa1AlFeywfJkglv/view?usp=share_link

2 - WebRTC-React-Native-Heabrid-App  :  https://drive.google.com/file/d/1WMRZ7X5U4PPkS1HqTo1wDAZ7YaK9nDm1/view?usp=share_link

3 - WebRTC-Electron-Hybrid-App-For-Windows  :  https://drive.google.com/file/d/1lfaVW6oshWe9M3wJ4yA0JGSaQEyjPF3d/view?usp=sharing

4 - WebRTC-Responsive-Web-App : https://drive.google.com/file/d/19ggvTMvGym0cL__SBALo3rvAdI_LYN-7/view?usp=share_link

5 - WebRTC-Electron-Hybrid-App-For-App : https://drive.google.com/file/d/16saI8GDhjfUJHDhsZrGMgkHFSxkotkiu/view?usp=share_link

To begin, please follow these steps to run the server:

1. Unzip the Server.zip file.
2. Open the resulting folder in a terminal.
3. Type the following command: `node server.js`.

Please note that the server is compatible with Windows, Linux, and macOS operating systems.

To compile the React Native client, please follow these steps:

1. Set up the React Native development environment on your machine.
2. Install the following React Native modules that are used in the application:
   - react-native-webrtc
   - react-native-incall-manager
   - react-native-easy-toast
   - react-native-prompt-crossplatform
   - react-native-background-job

Please note that the React Native application has been compiled specifically for the Android system. However, with appropriate modifications, it can also be adapted for the iOS system.

To compile the Electron application on Windows, first, install Electron on your Windows machine by referring to the following link: [Electron Installation Guide](https://www.electronjs.org/fr/docs/latest/tutorial/installation). 
Once installed, open the "WebRTC-Electron-Hybrid-App-For-Windows" folder in a terminal and execute the command: # npm run start

For compiling the Electron client on Raspberry Pi, you need to install Electron on your Raspberry Pi using the following command: 
$ sudo npm install -g electron --unsafe-perm=true --allow-root

After the installation, navigate to the "WebRTC-Electron-Hybrid-App-For-Raspberry-Pi" folder in a terminal and run the command:
$ npm run start


To test the application, please follow these steps:

1. Start the server.
2. Launch the web or hybrid clients.
3. Assign a unique number to each client (for example, between 6000 and 6999).
4. Click the "connexion" button to connect the client to the server.
5. Make a call to a client using its assigned number.

Please note that all four WebRTC clients are independent and can be used separately with the server. For example, if you only require the code for the React Native hybrid mobile app, you can download the "Server.zip" file and the "WebRTC-React-Native-Hybrid-App.zip" file from Google Drive.

We provide you with the code for the different client applications that were required for our thesis, but feel free to use them according to your specific needs.

Thank you!
