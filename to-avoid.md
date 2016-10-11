## What to avoid while testing your code ?
Unit test should **not** :

- Interact with a database or file system ;
- Require non-trivial network communication (you're not testing the network) ;
- Require any environment changes to run ;
- Call complex collaborator objects ;

# Unit test != othe tests
