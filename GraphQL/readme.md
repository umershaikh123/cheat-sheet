# GraphQL


## appollo endpoint
It is a uri pointing towards the data inside a database

## First set up schema

### Types
- ID
- Int
- String
- Float
- Boolean
- [object] // array of object
- type // object
- ! // required field
- $variables 

### Special Types

- type Query // make query of the data that you need
- type Mutation // post/delete/change data 
- input // input for a query

```

input eventInputs {
    id:ID
    name:String
}

type Query {
    event : [Event]
/* getEvent(id : ID , name : String) : Event */
    getEvent(input : eventInputs) : Event
}

```

### schema.graphql

structure of the data 

type Event  {
   id: ID!
   name: String
   description: String
   link: String
   imageURL: String
   attendees : [User]
}

type User[
   id: ID!!
   name : String!
   age : Int!
]


### schema.yaml