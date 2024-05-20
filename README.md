## React 

#### React Folder Structure 

- pages 
	- auth: index.jsx 
	- dashboard: index.jsx 
- config: firebase-config.js 
- hooks: useAddTransaction.js, useGetUserInfo.js

#### Clear Local Storage: clear()

```js
localStorage.clear() 
```

#### Converts a value to a number

```js
Number("2")
```

#### Another way rendering children prop

```js
// Using a Self-Closing Tag with the Spread Operator
const Block = ({ className, ...rest }) => {
  return (
    <motion.div
      className={className}
      {...rest}
    />
  );
};
// Any children passed to Block will be included in the ...rest and will automatically be rendered by the <motion.div />

```

## React Router 

#### New Keyword: exact

```js
<Route path="/" exact component={Home} />
```

#### Refresh The Page

```js
window.location.reload()
```

## Tailwind CSS 

#### Class Names 

```js
<img className="size-14" />
```

## Git 

#### Fork vs Clone 

- Clone: you can download the open-source project to your local env, make changes but cannot push changes back to the repo. That's why you need fork.
  
- Fork: you make a copy of the open-source project on your own GitHub account, clone it, make changes and push them to your own GitHub account. Then, you make a PR to merge your forked copy to the original open-source project. 















