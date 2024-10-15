# ORM-Timer
## Double timer app to help in manual assesment of behavioral murine tests

This is an Android app that works as two independent tactile timers. It is meant to help in murine behavioral tests such as the Object Recognition Memory assesment. In this example test, the analyst should track the time a mouse has explored (getting its nose close) two objects in a closed area. Usually this test is recorded and can be automated with the use of paid propietary software such as Any-Maze, however, when a lab does not have the resources to pay the licence, manual assesment is prefered. When manually timing the exploration time of two objects, the use of traditional timers (chronometers) can be troublesome. This timers need to be clicked once to start running, and a second time to stop. If the mouse rapidly changes from exploring one object to the other, or when repeatedly getting its nose in and out of the exploration distance, the analyst might mistake the right timer to click or forget to stop a timer which keeps the time running and natually messes up with the true exploration time.
This app is much easier to use for the analyst since it just requieres to keep pressed one side of the screen to start running the timer. The operation is so intuitive that eliminates the confounding factors that come with traditional chronometer.

## How to install

To use the app, install the .apk file form the repository
1. Open the link of this repository in a mobile phone
2. Click the .apk file and choose download
3. Allow external sources for software installation in the mobile device
4. It should not ask for other permissions after instalation is completed (but if it does, let me know)

## Additional features

Besides the two chonometers, some helpful features were added:
1. A "play" button will start a cont down from 60 seconds by default. When finished, the device will vibrate. This feature allows the user to analyze the recorded video of the experiment ***by chunks*** so that any mistakes in the time will only afect the last minute of video play or so.
2. A store button will store the values displayed at the current time by each timer
3. The settings button will display a slide bar to change de count down time from 0 to 120 seconds and a **recorded values** button to check the list of values the user saved. Lastly the check mark will save the info and get the user back to the original screen.
4. The reset button on the lowest part can be **long pressed to reset** both timers (the cont down time will be reset as well, but remain the time specified in settings)

## Find a bug?
If you found an issue or would like to submit an improvement to this project, please submit an issue using the issues tab above. If you would like to submit a Pull Request with a fix, reference the issue you created.


## Known issues (Work in progress)
The app is simple, however I'll list any ideas or future improvements I would like to make to it:
- I would like to add the option to export the values recorded as an Excel or .csv file
