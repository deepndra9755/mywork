# bank_chat_spec

## Purposs
A chat program where a customer asks a bank assistant questions
and sees what each answers cost us.


## user
A bank customer typing in a terminal window.

## it must
- show the assistant's answer to each question.
- Keep chatting until the user types "quit"
- Remember what the user said earlier in the same chat.
- Show each answer's cost in ruppes and the total so far.

## it must not
- Keep the secret key inside the code.
- Answer questions unrelated to banking.

## Done when
1. i ask "what is a fixed deposit?" -> a short, sensible answer.
2. i type "My name is Ravi", then "what's my name?" -> it answers "Ravi".
3. i ask three questions -> the ruppes total goes up after every answer.
4. i type "quit" -> the program ends.