* __The λ calculus as a building block of the universe__

```
(define Y (lambda (f) ((lambda (x) (f (lambda (a) ((x x) a)))) (lambda (x) (f (lambda (a) ((x x) a)))))))
```
