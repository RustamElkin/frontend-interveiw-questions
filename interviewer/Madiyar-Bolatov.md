#Ali Rustamov's tech interview

##JS
> Start time: 16:20 - End time: 16:34
- [x] [Разница между `var`, `let` и `const`?](https://youtu.be/1eIRTdgzHtw?t=362) [Common]
- [x] [Разница между `==` и `===` (нестрогое/строгое равенство)?](https://youtu.be/ycYp7CYOnO0?t=529) [Common]
- [ ] [Что такое Strict mode в JavaScript?](https://youtu.be/ycYp7CYOnO0?t=577) [Common/Middle]
  - ```знает что такое Strict Mode, но не полностью что в его деталях```
- [x] [Разница между `null` и `undefined`?](https://youtu.be/G7hLwudGWL4?t=511) [Common]
- [x] [Операторы (`&&` и `||` и `??`)?](https://youtu.be/G7hLwudGWL4?t=617) [Common]
  - statement1 && statement2
  - statement2 || statement2
  - statement2 ?? statement2
- [x] [Что обозначает `this` в JavaScript?](https://youtu.be/rlWgI7AvV18?t=507) [Common/Middle]
- [ ] [Что такое замыкание (Closure)?](https://youtu.be/kx3dR6ztICU?t=284) [Common/Middle]
  - ```ответ показался не полным.```
- [x] [Разница между `slice` и `splice`?](https://youtu.be/XtQPrt8G0n8?t=679) [Common/Middle]
- [x] [Как превратить любой тип данных в булевый? Перечислите ложные значения в JS?](https://youtu.be/CjdCxxqObaM?t=368) [Common]
- [x] [Методы массивов (array) в JavaScript?](https://youtu.be/CjdCxxqObaM?t=538) [Common/Middle]
- [x] [Что такое чистая функция?](https://youtu.be/rlWgI7AvV18?t=401) [Middle]
  - ```javascript
    const a = (counter) => {
      console.log(counter); // do not side effect
      return counter + 1;
    };
    ```
- [x] [Разница между `.forEach` и `.map()`?](https://youtu.be/rlWgI7AvV18?t=456) [Common/Middle]
- [x] [Что такое IIFE (Immediately invoked function expression) ?](https://youtu.be/kx3dR6ztICU?t=396) [Common/Middle]
- [x] [Разница между `typeof` и `instanceof`?](https://youtu.be/ovV8GhIkzBE?t=835) [Middle]
- [x] [Как передаются параметры в функцию: по ссылке или по значению?](https://youtu.be/nvktMVFM0_M?t=280) [Middle]

##JS in Browser
> Start time: 16:35 - End time: 16:44
- [x] Browser API/Web API
  - знвет но не особо пользовался 
- [x] [Что такое DOM?](https://youtu.be/1eIRTdgzHtw?t=471)
- [x] Виртуальный DOM
- [ ] [Разница между HTMLCollection и NodeList?](https://youtu.be/IooJ3P2VUYs?t=705)
  - ```говорит не помнит```
- [x] [Виды событий в JavaScript?](https://youtu.be/7TvS0iKR3_c?t=318)
- [x] [Разница между `e.preventDefault()` и `e.stopPropagation()`?](https://youtu.be/CjdCxxqObaM?t=650)
- [ ] [Разница между `event.target` и `event.currentTarget`?](https://youtu.be/kx3dR6ztICU?t=539)
  - [x] `event.target`
  - [ ] `event.currentTarget` 

  
##OOP-IF
> Start time: 16:45 - End time: 16:52
>> P.S. - Кандидат поделился что мало владеет OOP 
- [ ] [~~Разница между классовым и прототипным наследованием?~~](https://youtu.be/rWEsjNWBoIE?t=751) [Middle]
- [x] [Что такое MVC?](https://youtu.be/xZLxdts7ZW4?t=181) [Middle]
- [ ] [Что такое MVVM?](https://youtu.be/ovV8GhIkzBE?t=489) [Middle]
  - ```ответ показался не полным.```
- [x] [Что такое каррирование (Currying)?](https://youtu.be/ovV8GhIkzBE?t=681) [Middle/Senior]
- [ ] [~~Плюсы и минусы ФП и ООП?~~](https://youtu.be/70VnuTXi4Wk?t=327) [Middle/Senior]
- [x] [Разница между монолитной и микросервисной архитектурами?](https://youtu.be/70VnuTXi4Wk?t=436) [Middle/Senior]
  - Плюсы и минусы
- [ ] [~~Что такое статический метод класса (`static`)? Как осуществляется его вызов?~~](https://youtu.be/G4iYlbilozM?t=641) [Middle/Senior]

##Async-Js
> Start time: 16:53 - End time: 16:56
- [x] [Разница между синхронными и асинхронными функциями?](https://youtu.be/kx3dR6ztICU?t=681)
- [x] [Что такое AJAX?](https://youtu.be/IooJ3P2VUYs?t=547)
- [x] [Что такое промисы (Promises)?](https://youtu.be/G4iYlbilozM?t=371)
- [ ] [Разница между `Promise.all()`, `Promise.any()` и `Promise.race()`?](https://youtu.be/XtQPrt8G0n8?t=782)
  - [x] `Promise.all()` && `Promise.any()`
  - [ ] `Promise.race()
  - 
##REACT
> Start time: 16:57 - End time: 17:
- [x] [Что такое `PureComponent`?](https://youtu.be/yvOXvZ8aEFo?t=581)
- [x] [Для чего нужен атрибут `key` при рендере списков?](https://youtu.be/yvOXvZ8aEFo?t=526)
- [x] [Что такое Компонент высшего порядка (Higher-Order Component / HOC)?](https://youtu.be/yvOXvZ8aEFo?t=637)
- [x] [Что Такое `JSX`?](https://youtu.be/RpcB5jnJvcI?t=571)
- [x] [Что такое контекст (`Context`)?](https://youtu.be/RpcB5jnJvcI?t=390)
- [x] [Что такое портал (`Portal`)?](https://youtu.be/RpcB5jnJvcI?t=342)
- [x] [Что такое фрагмент (`Fragment`)? Отличие от `div`?](https://youtu.be/RpcB5jnJvcI?t=689)
- [x] [Расскажите о хуках `useCallback()`, `useMemo()` ?](https://youtu.be/GZUy2i6QN7o?t=449)
- [x] [Расскажите о хуках `useEffect()`, `useLayoutEffect()`?](https://youtu.be/GZUy2i6QN7o?t=449)
- [x] [Что такое `ReactDOMServer`?](https://youtu.be/81yRgVQ1ciM?t=763)
- [x] [Чем React Router отличается от обычной маршрутизации?](https://youtu.be/GZUy2i6QN7o?t=710)
- [ ] [Что такое Reselect и как он работает?](https://youtu.be/XtQPrt8G0n8?t=847)
  - ```ответ показался не полным.```



##SMALL PRACTICE
```typescript
// ===========================================================================================

// OPERATORS

const a: any = undefined ?? null; // null
const b: any = !!""; // false
const c: any = 0.1 + 0.2 === 0.3; // false 0
const d: any = +"1" + 2 + 3; // 6
const e: any = typeof typeof 1; // string

// ===========================================================================================

// TASK Requirements:
// - given varianle t whish is equal to = 'Hello, world'
// - complete given 'utils' with clear functions

interface IClearValidators {
  [key: string]: (a: string) => string;
}

let t: string = "Hello,, world!!";

const utils: IClearValidators = {

  deleteLastLetter: (a) => { // "Hello,, world!!"
    // code here ...
    return a.split('').slice(0, a.length - 1).join('')  // 0 - "Hello,, world!"
  },

  deleteComma: (a) => { //  "Hello,, world!"
    // code here ... 
    return a.replace(',', '') // 1 - "Hello, world!"
  },

  logAtEnd: (a) => { // 1 - "Hello, world!"
    console.log(a)
    return a; // 2 - "Hello, world!"
  },
};

const textFormater = (text: string): string | undefined => {
  return Object.values(utils).reduce((acc, cur) => cur(acc), text)
};

const formattedText = textFormater(t);

```
