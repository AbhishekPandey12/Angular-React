# Angular-React
Training Document

Why Angular?
  - SPA
  - Data Binding
  - Modularization
  - Typescript Support
  
Export/Import variables/function from one .js file to another

demo1.js
===========================
export var a = 10;
export var b = 20;
export function add(){}

demo.js
===========================
import {a} from "./demo1"
import {b} from "./demo1"
import {add} from "./demo1"

demo1.js
===========================
export default xyz = 10;

demo.js
===========================
import xyz from "./demo1"


  
