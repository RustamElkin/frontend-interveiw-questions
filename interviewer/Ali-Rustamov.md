#Ali Rustamov's tech interview

##JS
- [x] [Типы данных в JavaScript?](https://youtu.be/ycYp7CYOnO0?t=471) [Common]
- [x] [Разница между `==` и `===` (нестрогое/строгое равенство)?](https://youtu.be/ycYp7CYOnO0?t=529) [Common]
- [x] [Что такое Strict mode в JavaScript?](https://youtu.be/ycYp7CYOnO0?t=577) [Common/Middle]
- [x] [Разница между `null` и `undefined`?](https://youtu.be/G7hLwudGWL4?t=511) [Common]
- [x] [Операторы «И» и «ИЛИ» (`&&` и `||`)?](https://youtu.be/G7hLwudGWL4?t=617) [Common]
    - statement1 && statement2
    - statement2 || statement2
- [x] [Что такое поднятие (Hoisting)?](https://youtu.be/G7hLwudGWL4?t=552) [Common]
- [ ] [Что такое область видимости (Scope)?](https://youtu.be/1eIRTdgzHtw?t=282) [Common]
- [x] [Разница между `var`, `let` и `const`?](https://youtu.be/1eIRTdgzHtw?t=362) [Common]
- [x] [Что такое замыкание (Closure)?](https://youtu.be/kx3dR6ztICU?t=284) [Common/Middle]
- [x] [Разница между `slice` и `splice`?](https://youtu.be/XtQPrt8G0n8?t=679) [Common/Middle]
- [x] [Методы строк (string) в JavaScript?](https://youtu.be/CjdCxxqObaM?t=415) [Common/Middle]
- [x] [Методы массивов (array) в JavaScript?](https://youtu.be/CjdCxxqObaM?t=538) [Common/Middle]
- [x] [Что такое чистая функция?](https://youtu.be/rlWgI7AvV18?t=401)
  - ```javascript
    const a = (counter) => {
    console.log(counter) // do not side effect
    return counter + 1
    }
    ```
- [x] [Разница между `.forEach` и `.map()`?](https://youtu.be/rlWgI7AvV18?t=456) [Common/Middle]
- [x] [Что такое IIFE?](https://youtu.be/kx3dR6ztICU?t=396) [Common/Middle]
- [x] [Разница между `typeof` и `instanceof`?](https://youtu.be/ovV8GhIkzBE?t=835) [Middle]

>00:19 time

##JS in Browser
- [ ] Browser API
- [x] [Что такое DOM?](https://youtu.be/1eIRTdgzHtw?t=471)
- [x] Виртуальный DOM
- [x] [Разница между HTMLCollection и NodeList?](https://youtu.be/IooJ3P2VUYs?t=705)
- [x] [Виды событий в JavaScript?](https://youtu.be/7TvS0iKR3_c?t=318)
- [x] [Разница между `e.preventDefault()` и `e.stopPropagation()`?](https://youtu.be/CjdCxxqObaM?t=650)
- [x] [Разница между `event.target` и `event.currentTarget`?](https://youtu.be/kx3dR6ztICU?t=539)
>00:24 time


##OOP-IF
- [x] [Разница между классовым и прототипным наследованием?](https://youtu.be/rWEsjNWBoIE?t=751) [Middle]
- [x] [Что такое MVC?](https://youtu.be/xZLxdts7ZW4?t=181) [Middle]
- [ ] [Что такое MVVM?](https://youtu.be/ovV8GhIkzBE?t=489) [Middle]
- [x] [Что такое каррирование (Currying)?](https://youtu.be/ovV8GhIkzBE?t=681) [Middle/Senior]
- [ ] [Плюсы и минусы ФП и ООП?](https://youtu.be/70VnuTXi4Wk?t=327) [Middle/Senior]
- [x] [Разница между монолитной и микросервисной архитектурами?](https://youtu.be/70VnuTXi4Wk?t=436) [Middle/Senior]
    - Плюсы и минусы
- [ ] [Что такое статический метод класса (`static`)? Как осуществляется его вызов?](https://youtu.be/G4iYlbilozM?t=641) [Middle/Senior]
>00:35 time


##Async-Js
- [x] [Разница между синхронными и асинхронными функциями?](https://youtu.be/kx3dR6ztICU?t=681)
- [x] [Что такое AJAX?](https://youtu.be/IooJ3P2VUYs?t=547)
- [x] [Что такое промисы (Promises)?](https://youtu.be/G4iYlbilozM?t=371)
- [x] [Разница между `Promise.all()`, `Promise.any()` и `Promise.race()`?](https://youtu.be/XtQPrt8G0n8?t=782)
>00:39 time


##REACT
- [x] [Что такое `PureComponent`?](https://youtu.be/yvOXvZ8aEFo?t=581)
- [x] [Для чего нужен атрибут `key` при рендере списков?](https://youtu.be/yvOXvZ8aEFo?t=526)
- [ ] [Что такое Компонент высшего порядка (Higher-Order Component / HOC)?](https://youtu.be/yvOXvZ8aEFo?t=637)
- [x] [Что Такое `JSX`?](https://youtu.be/RpcB5jnJvcI?t=571)
- [ ] [Что такое контекст (`Context`)?](https://youtu.be/RpcB5jnJvcI?t=390)
- [ ] [Что такое портал (`Portal`)?](https://youtu.be/RpcB5jnJvcI?t=342)
- [x] [Что такое фрагмент (`Fragment`)? Почему фрагмент лучше, чем `div`?](https://youtu.be/RpcB5jnJvcI?t=689)
- [x] [Расскажите о хуках `useCallback()`, `useMemo()` ?](https://youtu.be/GZUy2i6QN7o?t=449)
- [ ] [Расскажите о хуках `useEffect()`, `useLayoutEffect()`?](https://youtu.be/GZUy2i6QN7o?t=449)
- [ ] [Что такое `ReactDOMServer`?](https://youtu.be/81yRgVQ1ciM?t=763)
- [ ] [Чем React Router отличается от обычной маршрутизации?](https://youtu.be/GZUy2i6QN7o?t=710)
- [ ] [Что такое Reselect и как он работает?](https://youtu.be/XtQPrt8G0n8?t=847)
>00:55

##SMALL PRACTICE
```typescript
// ===========================================================================================
// Functions Pipeline
// ===========================================================================================
// TASK Requirements:
// - given varianle t whish is equal to = 'Hello, world'
// - complete given 'utils' with clear functions 


interface IClearValidators {
  [key:string]: (a: string) => string
}

let t:string = 'Hello, world!!'; 

const utils:IClearValidators = {
  // 0 -  Hello, world!,
  'deleteLastLetter': (a) => { // delete last letter of given 'a' argument
    // [reviewer]: ✅
    return a.slice(0, a.length - 1); 
  },
  
  // 1 -  Hello, world!  

  'deleteComma': (a) => { // delete one comma of given 'a' argument
    // [reviewer]: better use .replace()
    return a.slice(0, a.indexOf(',')).concat(a.slice(a.indexOf(',') + 1, a.length))
  },
  // 2 -  Hello world!  
  
  'logAtEnd': (a) => {
   console.log(a);
   return a;    
  }

}

const textFormater = (text: string): string | undefined => {
  return Object.values(utils).reduce((prev, cur) => cur(prev), text);
}

const formattedText = textFormater(t)

console.log(formattedText)
```


