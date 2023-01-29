# Methods

class Something {
 constructor(data) {
 this.data = data
 }
 doSomething(text) {
 return {
 data: this.data,
 text
 }
 }
}
var s = new Something({})
s.doSomething("hi") // returns: { data: {}, text: "hi" }
