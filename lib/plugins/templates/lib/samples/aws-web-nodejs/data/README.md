## Framework : [squeezer.io](https://squeezer.io)
## Documentation : [squeezer.io/docs](https://squeezer.io/docs)

### Project Structure

```
.
├── cloudformation      CloudFormation nested custom YAML templates
├── lib                 Project's Library
├── services       Functions Directory
│   └── my-service
│     └── function1
├── node_modules        Node NPM packages
└── plugins             Squeezer plugins
```


### Requirements

- [Install node.js](http://nodejs.org/) version `>=4`

## Squeezer CLI

> Squeezer command-line interface

### Getting started


|    | cmd | description  |
|----|-----|--------------|
| 1. | **npm install -g squeezer-cli**  |  Install Squeezer CLI |
| 1. | **sqz install**  |  Install all project dependencies |
| 3. | **sqz deploy**  |  Initial deployment ( required before **serve** ) <br>*NOTE* : first deployment takes a little longer |
| 4. | **sqz serve**  |  Simulates functions platform on your local machine<br>*NOTE* : live reload enabled by default |

**Web App** : [http://localhost:4001/](http://localhost:4001/)