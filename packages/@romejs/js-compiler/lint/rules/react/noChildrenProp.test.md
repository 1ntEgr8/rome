# `noChildrenProp.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/lint/rules/react/noChildrenProp.test.ts --update-snapshots` to update.

## `no children props`

### `0`

```

 unknown:1 lint/noChildrenProp ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ children should not be passed as a prop

    <MyComponent children={'foo'}></MyComponent>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
<MyComponent children={'foo'}></MyComponent>;

```

### `1`

```

 unknown:1 lint/noChildrenProp ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ children should not be passed as a prop

    React.createElement('div', {children: 'foo'})
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
React.createElement('div', {children: 'foo'});

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
<MyComponent><AnotherComponent /></MyComponent>;

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
React.createElement('div', {}, 'children');

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
React.createElement('div', child1, 'child2');

```
