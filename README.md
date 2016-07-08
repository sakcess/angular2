# angular2
Angular 2




Note:
Compilation Error: <br>
      node_modules/angular2/src/facade/promise.d.ts(1,10): error TS2661: 
        Cannot re-export name that is not defined in the module.

Solve this problem by adding declare var Promise: PromiseConstructor; on the top of promise.d.ts
