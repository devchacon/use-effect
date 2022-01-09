# devchacon

## I branch off hook for using the useEffect() Hook

Store Data in Browser Storage send Http Requests to backend servers set & Manage Timers.

### Handling Side Effect with the useEffect() Hook

<code>
useEffect(() => {...}, [dependencies]);
</code>

### The first argument is a anonymous arrow function.
<code>
(() => {...})
</code>

#### The first argument is a function. A function that should be executed AFTER every component evaluation IF the specifield dependencies changed. Your side effect code goes into this function.

### The second argument is an array of dependencies, you pass in.
<code>
[dependencies]
</code>

#### Dependencies of this effect - the function only runs if the dependencies changed. Specify your dependencies of your function here.

### Effect, Reduces & Context => Features are a bit more advanced

### Main job: Render to UI & React to User Input

