# ABX-MaxMSP

A Max/MSP patcher for ABX listening tests.

This patcher implements an ABX listening test. The test is a discrimination task, assessing the listener's ability to hear differences in audio files that contain small impairments. The patcher chooses a reference stimulus and a test stimulus, which are randomly assigned to A and B. Either A or B is then randomly assigned to X. This listener must decide whether X is A or B. The patcher chooses the test stimulus from a pool of several audio files. The presentation of each audio file can be repeated a specified number of times. The presentation of all audio files and repeats is randomised.

![ABX2.json](/ABX.png?raw=true "ABX2.json")

## Requirements

Max/MSP 6 or higher.
