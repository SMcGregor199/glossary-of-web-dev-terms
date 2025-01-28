# A Glossary of Web Dev Terms

### Immediately Invoked Function Expression

**Definition**
An Immediately Invoked Function Expression (IIFE) is a function that is executed immediately after it is defined.

**Example**

```javascript
(
    function(){
        console.log("This is an IIFE");    
    }
)();

/* or with arrow functions*/

(()=>{
    console.log("This is an IIFE")
})();

```

**Notes**

- Notice that the function is wrapped in parethesis. Also that the parenthesis is appended with ``();`` to denote that a function is being called.
- While the IIFE is a concept popularized in JavaScript, it can also be used in other programming languages.

**Further Resources**

- [**MDN Web Docs:Functions**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#immediately_invoked_function_expression)

**Related Terms**

- Function Expression
- Global Scope
- Variable Hosting
- Module Pattern

### Representational State Transfer API

**Definition**

A RESTful API (Representational State Transfer API) is a design pattern for building web services that interact
with resources over HTTP using standard methods like GET, PUT, DELETE, etc. It adheres to REST principles, which emphasize stateless
communication and resource-based archietecture.

```javascript
fetch("https://example.com/api/data")
    .then(function(response){
        return response.json();
    })
    .then(function(data){
        console.log(data);
    })
    .catch(function(error){
        console.log(`There was an error fetching data:${error}`);
    })
```

### Widget

### Largest Contentful Paint (LCP)
