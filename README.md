# Book Search Engine Starter Code

Questions: 

schemas/resolvers.js:
Do we not have to do a getsingle user in resolvers according to user-controller.js?

Confused about async (parent, { userId, }, context)

typedef.js:
What is query me ? is just a naming convention; can be called user and still do the same thing
where am I getting token from?

client/src/mutations:
first line references the client input 
second line references that same input and the bottom HAS to match the typeDefs
mutation loginUser($email: String!, $password: String!) {
    loginUser(email: $email, password: $password) {
        token








