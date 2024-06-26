# CSC305 Term Project - QuickWrite
This is a social media app being developed for 305Soft that aims to provide users with daily writing prompts they can respond to and share with their friends.
## Usage
To use this app in the intended way, you can download it from the Google Play Store with an android device or go to [our website placeholder](). QuickWrite is a social media app that allows users to connect through responses to timed creative writing prompts. New prompts are shared across users and change on a daily basis, so everyone starts on the same level. Once a user posts their response for the day, they can see how other users responded to that same prompt and comment on those responses to provide feedback or praise. 
## Installation 
To make modifications to the app, a local copy of this repository must be installed locally then pushed to an app in thunkable. This can be done in a few easy steps, which are outlined below:
1. `git clone` the [thunkd](https://github.com/SupurCalvinHiggins/thunkd) repository and follow the installation instructions in its README
2. `git clone` this repository into the thunkd directory
3. Set your thunk token using the command `python thunkd.py set thunk_token <thunk_token>`. Where to find the thunk token is described in the FAQ section of [thunkd's README](https://github.com/SupurCalvinHiggins/thunkd/blob/main/README.md).
4. In the root directory of this repository, call the function `python thunkd.py push <project_id> src` to push the local copy of the app onto the project with the specified project_id. Where to find the project_id is outlined in the FAQ section of [thunkd's README](https://github.com/SupurCalvinHiggins/thunkd/blob/main/README.md).
5. Refresh the page for that project and it should become a copy of the QuickWrite app.

To download the app as a tester, follow the steps below:
1. Follow [this link](https://play.google.com/apps/internaltest/4701366745035518889) and log into the Google Play store with the account registered as a tester.
2. Click the "download it on Google Play" text highlighted in blue.
3. Click the install button and select what device or devices to install the app on.
4. Wait a few moments, then the app should be downloaded onto that device.
## License
QuickWrite is developed under the [CC BY License](https://creativecommons.org/licenses/by/4.0/deed.en), so you are free to use this project for whatever you want as long as you give appropriate credit.
