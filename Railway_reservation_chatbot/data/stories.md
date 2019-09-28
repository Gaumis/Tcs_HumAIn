## happy path11
* greet
  - utter_greet
* mood_great
  - utter_happy
* namei{"name": "Gaurav"}
  - utter_what_help
* book_ticket
  - utter_sure
  - utter_ask_origin
* informori{"origin": "patna"}
  - utter_ask_destination
* informdes{"destination": "delhi"}
  - utter_ask_date
* informdate{"date": "09-02-2019"}
  - utter_confirm
  - utter_wait
* affirm
  - utter_deny
* thankyou
  - utter_see_you

## happy path14
* greet
  - utter_greet
* mood_great
  - utter_happy
* namei{"name": "Gaurav"}
  - utter_what_help
* book_ticket
  - utter_sure
  - utter_ask_origin
* informori{"origin": "patna"}
  - utter_ask_destination
* informdes{"destination": "delhi"}
  - utter_ask_date
* informdate{"date": "09-02-2019"}
  - utter_confirm
  - utter_wait
* affirm
  - utter_deny
* cancel
  - utter_cancel_message
* thankyou
  - utter_see_you

## happy path1
* greet
  - utter_greet
* mood_great
  - utter_happy
* namei{"name": "Gaurav"}
  - utter_what_help
* cancel
  - utter_cancel_message
* thankyou
  - utter_see_you

## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye
