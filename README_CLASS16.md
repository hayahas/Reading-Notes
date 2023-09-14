# Reading Class 16

1- What does it mean to authenticate a user?

- Verifying the identity oh the user to know who exactly who he is.

2- What does it mean to authorize a user?

- The access control to the user and what is he allowed to do

3- What are the three possible outcomes of the AuthenticationManager’s authenticate() method?

- Return an Authentication if it can verify that the input represents a valid principal.
- Throw an AuthenticationException if it believes that the input represents an invalid principal.
- Return null if it cannot decide.
