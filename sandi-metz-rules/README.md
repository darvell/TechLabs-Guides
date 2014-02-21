Sandi Metz’ rules for developers
======

1. Your class can be no longer than a hundred lines of code.
2. Your methods can be no longer than five lines of code
3. You can pass no more than four parameters and you can't just make it one big hash.
4. In your controller, you can only instantiate one object, to do whatever it is that needs to be done.
5. Your view can only know about one instance variable.
6. Your Rails view should only send messages to that object i.e., no Demeter violations.[  "thunder dome principal". Translated: one model in, one model out! ]
7. Rules are meant to be broken if by breaking them you produce better code. [ ...where "better code" is validated by explaining why you want to break the rule to someone else. ]

Sandi Metz' rules of testing
======

Good testing is about following messages between objects. From an object's point of view, messages originate from one of 3 places: received from others, sent to others, or sent to self (private messages).

Messages come in two types: queries and commands. 

Here's how you test each case

* Incomming Query Messages: make assetions about what they send back.
* Incomming Command Messages: assert direct public side effect
* Private Messages: Don't test them
* Outgoing Query Messages: Don't test them
* Outgoing Command Messages: Expect to send outgoing command message
