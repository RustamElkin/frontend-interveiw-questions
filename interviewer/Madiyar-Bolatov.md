#Ali Rustamov's tech interview

##JS

- [] [Разница между `var`, `let` и `const`?](https://youtu.be/1eIRTdgzHtw?t=362) [Common]
- [] [Разница между `==` и `===` (нестрогое/строгое равенство)?](https://youtu.be/ycYp7CYOnO0?t=529) [Common]
- [] [Что такое Strict mode в JavaScript?](https://youtu.be/ycYp7CYOnO0?t=577) [Common/Middle]
- [] [Разница между `null` и `undefined`?](https://youtu.be/G7hLwudGWL4?t=511) [Common]
- [] [Операторы (`&&` и `||` и `??`)?](https://youtu.be/G7hLwudGWL4?t=617) [Common]
  - statement1 && statement2
  - statement2 || statement2
  - statement2 ?? statement2
- [] [Что обозначает `this` в JavaScript?](https://youtu.be/rlWgI7AvV18?t=507) [Common/Middle]
- [] [Что такое замыкание (Closure)?](https://youtu.be/kx3dR6ztICU?t=284) [Common/Middle]
- [] [Разница между `slice` и `splice`?](https://youtu.be/XtQPrt8G0n8?t=679) [Common/Middle]
- [] [Как превратить любой тип данных в булевый? Перечислите ложные значения в JS?](https://youtu.be/CjdCxxqObaM?t=368) [Common]
- [] [Методы массивов (array) в JavaScript?](https://youtu.be/CjdCxxqObaM?t=538) [Common/Middle]
- [] [Что такое чистая функция?](https://youtu.be/rlWgI7AvV18?t=401) [Middle]
  - ```javascript
    const a = (counter) => {
      console.log(counter); // do not side effect
      return counter + 1;
    };
    ```
- [] [Разница между `.forEach` и `.map()`?](https://youtu.be/rlWgI7AvV18?t=456) [Common/Middle]
- [] [Что такое IIFE?](https://youtu.be/kx3dR6ztICU?t=396) [Common/Middle]
- [] [Разница между `typeof` и `instanceof`?](https://youtu.be/ovV8GhIkzBE?t=835) [Middle]
- [] [Как передаются параметры в функцию: по ссылке или по значению?](https://youtu.be/nvktMVFM0_M?t=280) [Middle]

> 00:19 time

##JS in Browser

- [] Browser API/Web API
- [] [Что такое DOM?](https://youtu.be/1eIRTdgzHtw?t=471)
- [] Виртуальный DOM
- [] [Разница между HTMLCollection и NodeList?](https://youtu.be/IooJ3P2VUYs?t=705)
- [] [Виды событий в JavaScript?](https://youtu.be/7TvS0iKR3_c?t=318)
- [] [Разница между `e.preventDefault()` и `e.stopPropagation()`?](https://youtu.be/CjdCxxqObaM?t=650)
- [] [Разница между `event.target` и `event.currentTarget`?](https://youtu.be/kx3dR6ztICU?t=539)
  > 00:24 time

##OOP-IF

- [] [Разница между классовым и прототипным наследованием?](https://youtu.be/rWEsjNWBoIE?t=751) [Middle]
- [] [Что такое MVC?](https://youtu.be/xZLxdts7ZW4?t=181) [Middle]
- [] [Что такое MVVM?](https://youtu.be/ovV8GhIkzBE?t=489) [Middle]
- [] [Что такое каррирование (Currying)?](https://youtu.be/ovV8GhIkzBE?t=681) [Middle/Senior]
- [] [Плюсы и минусы ФП и ООП?](https://youtu.be/70VnuTXi4Wk?t=327) [Middle/Senior]
- [] [Разница между монолитной и микросервисной архитектурами?](https://youtu.be/70VnuTXi4Wk?t=436) [Middle/Senior]
  - Плюсы и минусы
- [] [Что такое статический метод класса (`static`)? Как осуществляется его вызов?](https://youtu.be/G4iYlbilozM?t=641) [Middle/Senior]
  > 00:35 time

##Async-Js

- [] [Разница между синхронными и асинхронными функциями?](https://youtu.be/kx3dR6ztICU?t=681)
- [] [Что такое AJAX?](https://youtu.be/IooJ3P2VUYs?t=547)
- [] [Что такое промисы (Promises)?](https://youtu.be/G4iYlbilozM?t=371)
- [] [Разница между `Promise.all()`, `Promise.any()` и `Promise.race()`?](https://youtu.be/XtQPrt8G0n8?t=782)
  > 00:39 time

##REACT

- [] [Что такое `PureComponent`?](https://youtu.be/yvOXvZ8aEFo?t=581)
- [] [Для чего нужен атрибут `key` при рендере списков?](https://youtu.be/yvOXvZ8aEFo?t=526)
- [] [Что такое Компонент высшего порядка (Higher-Order Component / HOC)?](https://youtu.be/yvOXvZ8aEFo?t=637)
- [] [Что Такое `JSX`?](https://youtu.be/RpcB5jnJvcI?t=571)
- [] [Что такое контекст (`Context`)?](https://youtu.be/RpcB5jnJvcI?t=390)
- [] [Что такое портал (`Portal`)?](https://youtu.be/RpcB5jnJvcI?t=342)
- [] [Что такое фрагмент (`Fragment`)? Отличие от `div`?](https://youtu.be/RpcB5jnJvcI?t=689)
- [] [Расскажите о хуках `useCallback()`, `useMemo()` ?](https://youtu.be/GZUy2i6QN7o?t=449)
- [] [Расскажите о хуках `useEffect()`, `useLayoutEffect()`?](https://youtu.be/GZUy2i6QN7o?t=449)
- [] [Что такое `ReactDOMServer`?](https://youtu.be/81yRgVQ1ciM?t=763)
- [] [Чем React Router отличается от обычной маршрутизации?](https://youtu.be/GZUy2i6QN7o?t=710)
- [] [Что такое Reselect и как он работает?](https://youtu.be/XtQPrt8G0n8?t=847)
  > 00:55

##SMALL PRACTICE

```typescript
// ===========================================================================================
// Functions Pipeline
// ===========================================================================================
// TASK Requirements:
// - given varianle t whish is equal to = 'Hello, world'
// - complete given 'utils' with clear functions

const a: any = undefined ?? null; // null
const b: any = !!""; // false
const c: any = 0.1 + 0.2 === 0.3; // 0.29 == 0.3
const d: any = +"1" + 2 + 3; // 6
const e: any = typeof typeof 1; // string

interface IClearValidators {
  [key: string]: (a: string) => string;
}

let t: string = "Hello, world!!";

const utils: IClearValidators = {
  // 0 -  Hello, world!,
  deleteLastLetter: (a) => {
    // delete last letter of given 'a' argument
    // [reviewer]: ✅
    return a.slice(0, a.length - 1);
  },

  // 1 -  Hello, world!

  deleteComma: (a) => {
    // delete one comma of given 'a' argument
    // [reviewer]: better use .replace()
    return a
      .slice(0, a.indexOf(","))
      .concat(a.slice(a.indexOf(",") + 1, a.length));
  },
  // 2 -  Hello world!

  logAtEnd: (a) => {
    console.log(a);
    return a;
  },
};

const textFormater = (text: string): string | undefined => {
  return Object.values(utils).reduce((prev, cur) => cur(prev), text);
};

const formattedText = textFormater(t);

console.log(formattedText);
```
