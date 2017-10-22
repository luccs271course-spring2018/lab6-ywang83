# Questions & Answers

## Why does `FixedArrayQueue` require an explicit constructor?
Because we need to construct a `queue` with the default initial `capacity`.

## What happens when you offer an item to a full `FixedArrayQueue`?
It will return `false`.

## What happens when you poll an empty `FixedArrayQueue`?
It will return `null`.

## What is the time and (extra) space complexity of each of the `FixedArrayQueue` methods?
- `offer()`: T(n) =O(1); S(n) =O(1);
- `peek()`: T(n) =O(1); S(n) =O(1);
- `poll()`: T(n) =O(1); S(n) =O(1);
- `isEmpty()`: T(n) =O(1); S(n) =O(1);
- `size()`: T(n) =O(1); S(n) =O(1);
- `asList()`: T(n) =O(n); S(n) =O(n);
