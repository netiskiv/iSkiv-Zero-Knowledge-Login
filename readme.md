--1. Zero-knowledge login 

This solution gives the owner of the email address the opportunity to manage the login 
without the website publisher's knowledge.

When creating an "account" to an anonymous user, the website issues a password hash 
that the user keeps associated to its email address. 

To login easily, the user can save its username/pseudo with the password hash. 

When the user logs in, only the password hash is checked 
but the username/pseudo is passed for use during the session.

This means that the website keeps only the password hash, 
a meaningless string that does not identify the user. 

In case of a breach, there is nothing to steal. 

The username/pseudo or email address used during the session is NOT kept in a file at website's end.

Despite the full privacy, the session's username/pseudo makes it easy to follow up the activity, comments and usages of a given anonymous user. This is because 'identity' and 'character' are of different nature. and correspond to a different angle. Roughly sais, Identity is about a person;
But activity and usages are about a character.
