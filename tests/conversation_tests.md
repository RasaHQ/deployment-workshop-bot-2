## ## This file contains tests to evaluate that your bot behaves as expected.

## ## If you want to learn more, please see the docs: https://rasa.com/docs/rasa/user-guide/testing-your-assistant/

## happy path 1
* greet: hello there!
  - action_hi
* mood_great: amazing
  - utter_happy

## happy path 2
* greet: hello there!
  - action_hi
* mood_great: amazing
  - utter_happy
* goodbye: bye-bye!
  - utter_goodbye

## sad path 1
* greet: hello
  - action_hi
* mood_unhappy: not good
  - utter_cheer_up
  - utter_did_that_help
* affirm: yes
  - utter_happy

## sad path 2
* greet: hello
  - action_hi
* mood_unhappy: not good
  - utter_cheer_up
  - utter_did_that_help
* deny: not really
  - utter_goodbye

## sad path 3
* greet: hi
  - action_hi
* mood_unhappy: very terrible
  - utter_cheer_up
  - utter_did_that_help
* deny: no
  - utter_goodbye

## say goodbye
* goodbye: bye-bye!
  - utter_goodbye

## bot challenge
* bot_challenge: are you a bot?
  - utter_iamabot

## Story from conversation with 8cbeedbb3fb7464fbe68a58c308233f5 on January 7th 2021

* greet: hey
    - action_hi
* affirm: cool
    - utter_happy
* greet: woh!
    - action_hi
* mood_unhappy: not that great
    - utter_cheer_up
    - utter_did_that_help
* greet: hahah
