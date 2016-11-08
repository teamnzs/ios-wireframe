# Trivia Game

## User Stories

- [ ] Intro
   - [ ] User should be able to login or sign up via Facebook
   - [ ] Get user permission for access Facebook data
   - [ ] App should be able to persist user session
- [ ] Main page
   - [ ] It has tab layout on the bottom - Discover, Friends, Profile
   - [ ] By tapping on each tab, user should be able to change the main content view
- [ ] Discover tab
   - [ ] User can create a game room
   - [ ] User can see the list of existing games and should be able to join the room by clicking on one of the rooms
- [ ] Profile tab
   - [ ] User can see their basic information, i.e. profile picture, name, game score, etc
   - [ ] User can go back, save information, or log out
- [ ] Create game tab
   - [ ] User can create a game as "Game room"
- [ ] Ranking tab
   - [ ] User can see the global ranking
- [ ] Game room page
   - [ ] Creat a room
      - [ ] Same as "Friends page", user can see their friends list and select a list of friends (up to 5 people)
      - [ ] User can create a room by selecting the category, selecting number of questions, and selecting public/private mode, or can exit the view
      - [ ] User can see the number of people who have joined, and can click on "Join" or "Cancel" button
   - [ ] See friends list
      - [ ] User can see their friends list loaded from Facebook Graph api
      - [ ] User can search friends
      - [ ] Should be able to select a list of friends (up to 5 people) and create a game room
   - [ ] Playing game
      - [ ] User can see the Trivia question and count down timer
      - [ ] Should be able to exit or select answer. The answer list comes from server
      - [ ] After submit the answer, user should be able to see the ranking
      - [ ] User can go back to the "Ready" page by clicking the next game
   - [ ] Entering an existing game room
      - [ ] User can see the Travia question and count down timer for existing game
      - [ ] Submit button should be gray out until the next round is available
- [ ] Final Score page
   - [ ] User should be able to see the ranking and winner

The following **optional** features can be implemented:

- [ ] Intro
   - [ ] User can signup or login via Twitter
- [ ] Profile page
   - [ ] User can take picture with camera
- [ ] Friends page
   - [ ] User can invite people who is near by you by using location data
   - [ ] User can chat with friends


## License

    Copyright 2016 Savio Tsui, Zhia Hwa Chong, Nari Shin

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
