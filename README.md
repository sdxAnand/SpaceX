# SpaceX Dashboard

### Data management
1. The data has been managed using a single `useReducer` hook.
2. The Sidebar triggers the dispatch action to change state
3. Each state update triggers an API call
4. The MainContent renders with each state update

### IMPORTANT NOTE

I have tried to read the v3 API docs from multiple sources:
1.  [Link 1](https://api.spacex.land/graphql/)
2. [Link 2](https://docs.spacexdata.com/#cfcc49e7-5fe4-4dd3-9701-7c5caf7af9fb) 
   and have not been able to land upon a concrete JSON schema for each `launch` which would have `landing-status` mentioned. Hence, even though the API call for `landing-status` filter is working for me, on each individual launch, the `land-success` field is not well-defined.
   Please look into this.



### Other remaining points
1. React
2. REST API
3. Responsiveness
