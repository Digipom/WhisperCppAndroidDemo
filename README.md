A sample Android app using [whisper.cpp](https://github.com/ggerganov/whisper.cpp/) to do voice-to-text transcriptions. For the most up-to-date code, check [whisper.cpp's examples](https://github.com/ggerganov/whisper.cpp/tree/master/examples).

To use:

1. Select a model from the [whisper.cpp repository](https://github.com/ggerganov/whisper.cpp/tree/master/models).[^1]
2. Copy the model to the "app/src/main/assets/models" folder.
3. Select a sample audio file (for example, [jfk.wav](https://github.com/ggerganov/whisper.cpp/raw/master/samples/jfk.wav)).
4. Copy the sample to the "app/src/main/assets/samples" folder.
5. Select the "release" active build variant, and use Android Studio to run and deploy to your device.
[^1]: I recommend the tiny or base models for running on an Android device.
