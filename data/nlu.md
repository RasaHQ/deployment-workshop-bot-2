## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good
- I am good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?

## intent:rivers_verify
- I need Rivers Access
- I need access to rivers
- I need access to Rivers
- I need access to rivers please [*****ac.melton01@gmail.com](extract_email)
- I need access to rivers *****ac.melton01@gmail.com
- yes, I need access to rivers [*****ac.melton01@gmail.com](extract_email)
- I need access to rivers right now [*****ac.melton01@gmail.com](extract_email)

## regex:extract_email
- (?:\*\*\*\*\*)([a-zA-Z0-9._-]+@[a-zA-Z0-9._-]+\.[a-zA-Z0-9_-]+)
