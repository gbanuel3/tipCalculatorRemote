# Project 1 - Tip Calculator

Tip Calculator is a tip calculator application for iOS.

Submitted by: Gildardo Banuelos

Time spent: 6 hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:

* [ ] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!
- [X] Works for any tip amounts

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/BOyHAbX.gif)

GIF created with [ezgif](https://ezgif.com/).

## Notes

Describe any challenges encountered while building the app.
I have never used XCode or Obj-C or MacOS, working on adjusting to it.

At first, I tried to create an app using a TableUI so that I could add any custom tip and it'll show along with all other custom tips added, just like the IOS Stock App. I spent a few hours trying to figure this out and could not get it to work as it was difficult to add a new row to the column without messing up every other row I had added. I suspect it had to do with constraints on the labels. I asked for help but since we are going to cover TableUI tomorrow, I chose to wait for it and instead implemented the required functionality for today.

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
