# Google Chrome DevTools

## 1. Console

1.1. Info

`console.error()`

1.2. Assertion

`console.assert(10===2, 'not nice')`

1.3. Table

```
console.table({name: 'Jon', age: 22},
{name: 'bitfish', age: 30},
{name: 'Alice', age: 33}])
```

1.4. Time

```
console.time();
for(i=0;i<10000000;i++);
console.timeEnd();
```

1.5. Trace

```
function foo() {
  function bar() {
    console.trace();
  }
  bar();
}
foo();
```

## 2. Run command

`...` -> `Run command` or `Ctrl + Shift + P`

2.1. Switch to dark theme

2.2. Show layout borders

2.3. Hard reload

2.4. Capture full size screenshot

2.5. Click element in inspection mode and `Capture node screenshot`

## 3. Meta reference

3.1. `$_` - last operation

3.2. `$0` - last clicked node

3.3. `location` then use `copy(location)` to copy all nodes

3.4. `H` hides choosen element in Inspector

## 4. Resend XHR request

`Network` -> `XHR` -> XHR request right click -> `Replay XHR`

## 5. Monitor page load status

`Network` -> `XHR` -> Gear icon -> check `Capture screenshot`

## 6. Copy img as data uri - binary base64

`Network` -> `Img` -> click on img in list -> `Preview` tab -> click on image -> `Copy img as data uri`
