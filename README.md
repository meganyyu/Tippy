# Project 1 - Tippy

Tippy is a tip calculator application for iOS.

Submitted by: Megan Yu

Time spent: 6 hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:

* [x] Settings page to change the default tip percentage.
* [x] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [x] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Added functionality for setting custom tip amount
- [x] Added functionality for splitting bill among any number of people

## Video Walkthrough

Here's a walkthrough of version 1 of the app, with only the required features:

<img src='http://g.recordit.co/ragw4L4fYI.gif' title='Version 1 Video Walkthrough' width='30%' alt='Version 1 Video Walkthrough' />

Here's a walkthrough of version 2 of the app, with the extended user features (walkthrough of locale-specific currency feature shown on right):

<img src = 'http://g.recordit.co/7Vrxrn1R0Z.gif' title='Version 2 Video Walkthrough' width ='30%' alt ='Version 2 Video Walkthrough' /> &nbsp; &nbsp; &nbsp; <img src = 'http://g.recordit.co/8wS5HQjDDL.gif' title='Version 2 Currency Video Walkthrough' width='30%' alt ='Version 2 Currency Video Walkthrough' />

GIFs created with [Recordit](http://recordit.co/).

## Notes

* Finished required portion of app relatively quickly but ran into some blocks while extending app functionality & design
* Got stuck on updating a UISegmentedControl with data from NSUserDefaults, but tinkered around and now have a better idea of how to work with NSUserDefaults and how to customize UISegmentedControl
* Tried animating views - I did manage to animate two views on one screen but probably not in the best way
* Also learned about:
    * How to set placeholder text for text fields!
    * How to access and use information about current locale!
    * Beginning to understand the idea behind outlets
* Found myself running into not just technical questions, but design questions - i.e. what’s the best way to let users customize their experience?
* What to improve/learn next time: figure out how to use auto layout & constraints so that UI works with every kind of screen

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library

## License

    Copyright 2020 Megan Yu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
