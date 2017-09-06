Retrieves an object that contains data about the monitor setup of the computer that the runtime is running on
# Example
```js
async function getMousePosition() {
    return await fin.System.getMousePosition();
}

getMousePosition().then(mousePosition => console.log(mousePosition)).catch(err => console.log(err));
```