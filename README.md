# Non-local Scope

Functions have access to both global and built-in scopes as well as their respective local scopes. but the inner function also has access to its enclosing scope .i.e the scope of outer scope. that scope is neither local nor global. it is called a non-local scope.

Functions defined inside anther function can reference variables from that enclosing scope, just like functions can reference variables from the global scope.