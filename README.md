# React Hook Flow

![React Hook Flow Diagram](./hook-flow.png)

## Get Started

```
╰─ git clone

╰─ cd react-hook-flow

╰─ npx browser-sync start --server --files "./*.html" --no-open --no-notify --directory

- "Open the dev tools console inside browser of choice to see change in React flow."
```

## Notes

```
╰─ useEffect is called after React finishes rerender.

╰─ When you use a function callback to set the initial state in a useState hook, it is only called when initially rerendered.

╰─ React is only call a function when the component is actually rerendered. You aren't calling the function, React is.

╰─ useEffect is only called when there is no dependencies listed or one of the dependencies change.
```
