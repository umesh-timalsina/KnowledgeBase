## Knowledge Base
As a programming/software-engineering noob, I often get overwhelmed by the amount of misses I have.

Recently, [@brollb](https://github.com/brollb) suggested a change to a code-base I have been working to incorporate `debounce` to reduce the repeated number of UI calls I had. When I was working on that change, I somehow missed the suggestion, not that I wanted to disregard the suggestion, but I ended up with a somewhat hacky solution that could easily be solved using the `debounce` function from underscore. Then and there, I decided, I need to document these things. So, I am keeping a long living tab of coding practices, syntactic sugars etc... in this repository.

### Debounce Function in Javascript
The javascript debounce function limits the number of calls to a function. It's used to boost web application performance, where the function's firing rate is limited by wait.

**Signature**
```js
/** The debounce function
 * @param {function} func The function to debounce
 * @param {Number} wait The wait time before the function is called
 * @param {boolean} immediate Whether to call this function immedeatly
 */
debounce(func, wait, immediate)
```

Useful Links:
1. https://levelup.gitconnected.com/debounce-in-javascript-improve-your-applications-performance-5b01855e086
2. https://davidwalsh.name/javascript-debounce-function
3. https://underscorejs.org/#debounce
4. https://lodash.com/docs/4.17.15#debounce
