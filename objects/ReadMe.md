#Movie Database with objects

## Defining an object

```
    var object = {
        key1: value1,
        key2: value2
    }
```

## Setting individual values in an object

You can set the value of a key by:

```
    object.key1 = newValue
```

## Getting value from object

To get key1 from the example object:

```
object.key1

// returns value1
```

or if you need to use a variable as they key:

```
var name = "key2"
object[name]

// returns value2
```