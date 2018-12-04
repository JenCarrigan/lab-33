![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Project Name

### Author: Student/Group Name

### Links and Resources
* [sandbox](https://codesandbox.io/s/50qk4x7k7k)

### Modules
#### `index.js`
Creates redux store and passes it down for use
Renders App

#### `store/index.js`
Exports the store with reducers and middleware

#### `actions.js`
Functions get and getOne will generate actions that will either get all people or just one person

#### `reducers.js`
Updates and exports state depending on action

#### `app.js`
App class has methods that will fetch people from Swapi API or a single person.
Has functions that map state to props and dispatch to props
Renders Link and List

#### `link.js`
Link class renders a link to get people from Swapi

#### `list.js`
List class renders people and class Details

#### `details.js`
Details class renders a single person

#### UML
![UML](https://raw.githubusercontent.com/JenCarrigan/data-structures-and-algorithms/master/%3Aassets/lab33UML.jpg)
