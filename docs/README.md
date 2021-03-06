
> hexlet-pairs@1.0.4 documentation /Users/mokevnin/projects/js-pairs
> documentation "build" "src/index.js" "-f" "md"

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [isPair](#ispair)
-   [cons](#cons)
-   [car](#car)
-   [cdr](#cdr)
-   [toString](#tostring)

## isPair

Check if something is pair

**Parameters**

-   `pair` **Pair?** 

**Examples**

```javascript
const pair = cons(5, 'hello');
isPair(pair); // true
isPair(5); // false
```

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 

## cons

Build pair

**Parameters**

-   `a` **any** 
-   `b` **any** 

**Examples**

```javascript
const pair = cons(5, 'hello');
```

```javascript
const pair = cons(cons(1, null), 'world');
```

Returns **Pair** 

## car

Get car (first element) from pair

**Parameters**

-   `pair` **Pair** 

**Examples**

```javascript
const pair = cons(5, 'hello');
car(pair); // 5
```

Returns **any** 

## cdr

Get cdr (second element) from pair

**Parameters**

-   `pair` **Pair** 

**Examples**

```javascript
const pair = cons(5, 'hello');
cdr(pair); // hello
```

Returns **any** 

## toString

Convert pair to string (recursively)

**Parameters**

-   `pair` **Pair** 

**Examples**

```javascript
toString(cons('', 10)); // ('', 10)
```

Returns **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** 
