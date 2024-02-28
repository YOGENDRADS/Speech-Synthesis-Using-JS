# Speech-Synthesis-Using-JS
JavaScript SpeechSynthesis Interface
This is the main controller interface for the speech synthesis service which controls the synthesis or creation of speech using the text provided. This interface is used to start the speech, stop the speech, pause it and resume it, along with getting the voices supported by the device.

The following are the methods available in this Interface:

speak(): Add the utterance(object of SpeechSynthesisUtterance) in the queue, which will be spoken when there is no pending utterance before it. This is the function, we will be using too.

pause(): To pause the current ongoing speech.
