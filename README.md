# Redux(Flux)
Redux is the one of the most popular flux implementation which has earned a huge attention due to its way of manage state of application. Basically it make all implementation simple as compared to flux implementation provided by facebook.
### Flux
Flux is the application architecture that Facebook uses for building client-side web applications. Flux is basically a pattren. it uses to persist states between different components and it follows uni-directional data flow unlinke other framework which support two way data-binding like angularjs.


# Look at What is flux for more generic view
https://github.com/virtualforce/FLux


# Components of flux

1) Store
2) Reducer
3) Actions

# Store
Store is the container which is used to hold the state of the applications. 

# Action
Actions is triggered by view like user want to add/delete or fetch data

# reducer
Reducers are functions that are used to update store.

# Redux Rule
we can not update state in store directly. every states need to be update by reducer

# Follow 
1) User trigger actions which has Action type and payload.
2) That payload and action type will be passed to reducers where he will determine what state need to update
3) Store will hold that updated state inside their container

# Things to keep in mind

We can not update state directly because every state(object) in redux is immutable. we have to make a new object to hold new state and old state get pass into new object. That old object will be replaced with new object
