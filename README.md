# react-localstorage-hook

Adds a hook to sync a state variable with the user's browser's local storage.

## Installation

`npm i tmetcalfe89/react-localstorage-hook`

## Usage

```
import useLocalStorage from "react-localstorage-hook";

function App() {
  const [someState, setSomeState] = useLocalStorage("someState", "");

  return <div>
    <input value={someState} onChange={(e) => setSomeState(e.target.value)} />
  </div>;
}

export default App;
```

## Notes

Retrieved from a ChatGPT conversation. There was a version I was using from [this article](https://usehooks.com/useLocalStorage/), but it was a bit overdeveloped imho.