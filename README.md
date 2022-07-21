GraphQL
= 
GraphQL server side.



## Usage
The project has been deployed to <a href="https://graphapitesting.herokuapp.com/graphql">https://graphapitesting.herokuapp.com/graphql</a><br>
You can test it by sending GraphQL request to get datas.

## Example
```
query{
  books {
    name
  }
}
```

It will return JSON datas:
```
{
  "data": {
    "books": [
      {
        "name": "Harry Potter and the Chamber of Secrets"
      },
      {
        "name": "Harry Potter and the Prisoner of Azkaban"
      },
      {
        "name": "Harry Potter and the Goblet of Fire"
      },
      {
        "name": "The Fellowship of the Ring"
      },
      {
        "name": "The Two Towers"
      },
      {
        "name": "The Return of the King"
      },
      {
        "name": "The Way of Shadows"
      },
      {
        "name": "Beyond the Shadows"
      }
    ]
  }
}
```
