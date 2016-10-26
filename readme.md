#  Web development tutorials

> Related Tutorials Write your own awesome web development tutorials for the libraries on CDNJS! 

[https://github.com/xgqfrms-GitHub/tutorials](https://github.com/xgqfrms-GitHub/tutorials)

===
===

# React CDN 

> **(Old version && New version)**

[react/0.13.3: JSXTransformer.js](https://cdnjs.com/libraries/react/0.13.3)

[react/0.14.1: react-dom.js](https://cdnjs.com/libraries/react/0.14.1)

[react/15.3.2: react-dom-server.js](https://cdnjs.com/libraries/react/15.3.2)


## CDN
```js
<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/JSXTransformer.js"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.14.1/react-dom.js"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.3.2/react-dom-server.js"></script>

``` 

## SRI
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/JSXTransformer.js" integrity="sha256-MkTacBvNGO5pU06MeUchxYJwIK/4JrIGyEeINOmKLkM=" crossorigin="anonymous"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.14.1/react-dom.js" integrity="sha256-/S+aYL20DqSEKdMsP5bLyYLOVQ8GGES9NsqtNUMOOFw=" crossorigin="anonymous"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.3.2/react-dom-server.js" integrity="sha256-SDRlxU2UvrgTfiqYOo8f8frNbE23UONjhU0Zk/vJjJc=" crossorigin="anonymous"></script>
``` 

## Usage

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>no-babel</title>
</head>
<body>
    <div id="container">
        <!-- This element's contents will be replaced with your component. -->
    </div>   
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/JSXTransformer.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/react.js"></script>
    <script src="no-babel.js"></script>
</body>
</html>
``` 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>no-babel</title>
</head>
<body>
    <div id="container">
        <!-- This element's contents will be replaced with your component. -->
    </div>   
    <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.3.2/react-dom.min.js" integrity="sha256-JIW8lNqN2EtqC6ggNZYnAdKMJXRQfkPMvdRt+b0/Jxc=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.3.2/react.min.js" integrity="sha256-cLWs9L+cjZg8CjGHMpJqUgKKouPlmoMP/0wIdPtaPGs=" crossorigin="anonymous"></script> -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.3.2/react-dom.js" integrity="sha256-M5lc1yUhpXlm2VZjGk4aoFwqR9H1OJ0p5MR5xpipulk=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.3.2/react.js" integrity="sha256-S35NJYrW34su183KBmfUDbOfAwmK0h3fFqdpdDS/8po=" crossorigin="anonymous"></script>
   
    <script src="no-babel.js"></script>
</body>
</html>
``` 




> more coming soon!



