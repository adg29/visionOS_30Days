## SFSpeechRecognizer

#### Description

- Uses `SFSpeechRecognizer` for speech-to-text conversion within a `SpeechRecognizer` actor.
- Adds methods for starting, resetting, and stopping transcription.
- Handles errors related to authorization, permissions, and recognizer unavailability.
- Implements speech processing using `AVAudioEngine` and `SFSpeechAudioBufferRecognitionRequest`.
- Follows best practices for Swift API design, concurrency, and error handling.

This code is an implementation of a speech recognizer using the class provided by the framework in iOS. The recognizer is implemented as an `actor`, which can be observed by `SwiftUI` views for updating the UI. The recognizer has a `transcript` property that contains the current transcription of the speech. The recognizer also has methods for `starting`, `resetting`, and `stopping` the transcription. The recognizer initializes by checking if the speech recognizer and audio session have the necessary authorization and permissions. If not, it will print an error message. The recognizer uses an audio engine to record the speech and sends the audio data to the speech recognizer for transcription. The recognizer also handles errors that may occur during the transcription process. 

Overall, this is a well-implemented speech recognizer that follows best practices for error handling and concurrency. 
