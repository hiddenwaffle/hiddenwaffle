* __The λ calculus as a building block of the universe:__

```
(define Y (lambda (f) ((lambda (x) (f (lambda (a) ((x x) a)))) (lambda (x) (f (lambda (a) ((x x) a)))))))
```
