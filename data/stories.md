## happy path
* greet
  - action_hi
* mood_great
  - utter_happy

## sad path 1
* greet
  - action_hi
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - action_hi
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## Story from conversation with f0064358f31a44728b956ec0c005eafb on September 10th 2020

* greet
    - action_hi
* deny
    - utter_cheer_up
