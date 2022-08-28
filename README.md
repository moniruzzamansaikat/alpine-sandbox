# alpine-sandbox
Every pieces of js codes must be inside of a component, otherwise code won't run :)

## Attributes
There are 15 attributes in alpine.js 
- [x] x-data: state or component data
- [x] x-bind: dynamically bind attributes 
- [x] x-on: for binding events
- [x] x-text: show text but not html render
- [ ] x-html: ⚠ TODO
- [x] x-model: modeling with input
- [x] x-show: show an element based on condition
- [x] x-transition: transition efffects on elements
- [x] x-if: conditionaly add or remove elements 
- [x] x-for: loop for data 
- [x] x-init: run some code when element intialized 
- [x] x-effect: track changes for dependencies
- [x] x-ref: reference to an elemtn
- [x] x-cloak: an helper attribute for removing delay  
- [x] x-ignore: ignore a component by intialized by alpine

## Properties
There are 6 properties
- [ ] $store: acces a global store registered by Alpine.store(...)
- [ ] $el: Reference the current DOM element
- [ ] $dispatch: Dispatch a custom browser event from the current element
- [ ] $watch: 
- [ ] $refs
- [ ] $nextTick