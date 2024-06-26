---
id: 5900f4fe1000cf542c510010
title: 'Завдання 400: гра з деревом Фібоначчі'
challengeType: 1
forumTopicId: 302067
dashedName: problem-400-fibonacci-tree-game
---

# --description--

Дерево Фібоначчі — це бінарне дерево, рекурсивно визначене як:

- $T(0)$ є порожнім деревом.
- $T(1)$ є бінарним деревом з лише одним вузлом.
- $T(k)$ складається з кореневого вузла, який має дочірні дерева $T(k - 1)$ та $T(k - 2)$.

На такому дереві грають двоє гравців. Під час кожного ходу гравець вибирає вузол і забирає його разом із меншим деревом, що прив’язане до цього вузла. Гравець, який повинен взяти кореневий вузол цілого дерева, програє.

Ось виграшні ходи першого гравця на першому ході за умови $T(k)$ від $k = 1$ до $k = 6$.

<img alt="виграшні ходи першого гравця на першому ході за умови від k = 1 до k = 6" src="https://cdn.freecodecamp.org/curriculum/project-euler/fibonacci-tree-game.png" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Нехай $f(k)$ буде кількістю виграшних ходів першого гравця (тобто ходів, для яких другий гравець не має виграшної стратегії) на першому ході гри на дереві $T(k)$.

Наприклад, $f(5) = 1$ та $f(10) = 17$.

Знайдіть $f(10000)$. У відповіді запишіть 18 останніх цифр.

# --hints--

`fibonacciTreeGame()` має повернути `438505383468410600`.

```js
assert.strictEqual(fibonacciTreeGame(), 438505383468410600);
```

# --seed--

## --seed-contents--

```js
function fibonacciTreeGame() {

  return true;
}

fibonacciTreeGame();
```

# --solutions--

```js
// solution required
```
