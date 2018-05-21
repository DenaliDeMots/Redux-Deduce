# API Reference

## Top-level Exports

* `deduce(rootReducer)`
* `D.[ACTION METHOD]({ configuration })`

### deduce



## D.\[ACTION METHOD\]\_\[ \| IN \| ALL\]

## Primitive Actions

### SET 

Replace the root value in the state-tree.

Works on: Numbers, Booleans, Strings

```javascript
//STATE = { }

D.SET_IN({"Trainer": "Ash Ketchum"})
D.SET_IN({"Badges": 4})
D.SET_IN({"isBattling": true})

/*STATE = {
    "Trainer": "Ash Ketchum",
    "Badges": 4,
    "isBattling": true
}
*/
```

### SET\_IN 

```javascript
//STATE = { "Pokemon": "value": 4 }

D.SET_IN({"key": "Pokemon", "value": 5})

//STATE = { "Pokemon": "value": 5 }
```

Objects, Arrays

### INCREMENT

```java
//STATE = 1

D.INCREMENT({"value": 1})

//STATE = 2
```

### DECREMENT

```java
//STATE = 1

D.INCREMENT({"value": 1})

//STATE = 0
```

### SET\_ALL - Objects, Arrays

```java
//STATE = 1

D.INCREMENT({"value": 1})

//STATE = 2
```

### TOGGLE

```java
//STATE = true

D.TOGGLE({"value": false})

//STATE = false
```

### ADD

```javascript
//STATE = { "Trainer": {} }

D.ADD_IN({"path": "Trainer", "value": { "badges": 5 }})

//STATE
```

### INSERT

### REMOVE

### MERGE

## Using IN and ALL

### INCREMENT\_IN

### INCREMENT\_ALL

### DECREMENT\_IN

### DECREMENT\_ALL

### TOGGLE\_IN

### TOGGLE\_ALL

### ADD\_IN

### ADD\_ALL

### INSERT\_IN

### UPDATE\_IN

### REMOVE\_IN

### REMOVE\_ALL

### MERGE\_IN

### MERGE\_ALL




