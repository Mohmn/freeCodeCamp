---
id: 5900f5191000cf542c51002c
title: '問題 429: 単約数の平方和'
challengeType: 5
forumTopicId: 302099
dashedName: problem-429-sum-of-squares-of-unitary-divisors
---

# --description--

ある数 $n$ の単約数 $d$ とは、$gcd(d, \frac{n}{d}) = 1$ という性質を持つような $n$ の約数です。

The unitary divisors of $4! = 24$ are 1, 3, 8 and 24.

これらの平方数の和は $12 + 32 + 82 + 242 = 650$ です。

$n$ の単約数の平方和を $S(n)$ で表します。 Thus $S(4!) = 650$.

$S(100\\,000\\,000!)$ mod $1\\,000\\,000\\,009$ を求めなさい。

# --hints--

`sumSquaresOfUnitaryDivisors()` は `98792821` を返す必要があります。

```js
assert.strictEqual(sumSquaresOfUnitaryDivisors(), 98792821);
```

# --seed--

## --seed-contents--

```js
function sumSquaresOfUnitaryDivisors() {

  return true;
}

sumSquaresOfUnitaryDivisors();
```

# --solutions--

```js
// solution required
```
