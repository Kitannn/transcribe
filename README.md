Transcribe
Transcribe is a service which provides captioning services for presenters.

Alexa Skill 💮
It all begins with an Alexa-skill which is used to control the trascription service by the presenter. The presenter just need say "Alexa, Transcribe" Alexa sends a start signal to a server to start the transcription process. Then after the prompt from the Alexa, "Start transcribe" Which will send a signal to the server to stop the transcription process.

Node Server ☁️
The Node backend server runs continoulsy and receives a signal from the lambda function powering Alex. This signal is then sent to the Web front-end where information is collected. The infromation is sent back to the server where it is then sent to the final mobile application for the users display.

Mobile App 📱
Recieves text from server and then displays text as subtitles in augmented reality. App uses camera on back of phone for the augmented reality.

Front end website 💻
Recieves start and stop signal from server to start and stop transcribing microphone audio to text using google transcribe api. Then sends Transcriptions as text to server to be sent to Mobile App. Can Understand and Transcribe many different languages.
