# Домашнее задание №2 к лекции «Символы, итераторы, генераторы»

[![Build status](https://ci.appveyor.com/api/projects/status/8pso4plx2gey5ww2?svg=true)](https://ci.appveyor.com/project/yuriyvyatkin/ajs-hw-11-2-symbols-generators)

## Символы и генераторы

### Легенда

Реализовывать итераторы не так уж здорово, правда? Давайте посмотрим, как нам могут помочь генераторы при переборе.

### Описание

Используйте следующую заготовку для организации перебора класса `Team`:
```javascript
class Team {
  ...
  *[Symbol.iterator]() {
    // это генератор
    // и здесь есть доступ к this
    // остаётся лишь правильно написать yield
  }

}
```
