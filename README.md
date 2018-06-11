# event-bus

### Introduction

> event-bus is a ligtweight、none dependence lib, it supports distribution、subscription and offline subscription.

### Install

> npm i event-bus

### Usage
```
const e = new _event({})   //init
const handler = (params) => {
    console.log(params)
}
//event subscripte
e.on('msg', handler);  

//event distribute
e.emit('msg', 'recive a message');  

//remove subscripte
e.off('msg', handler)  

```


### Api

#### on

#### once

#### emit

#### off

#### emitList

#### eventList

