title: about
date: 2016-04-02 18:25:07
---
```javascript
//future requirements
var requirements = Obversable.create((s) => {
    var i = setTimeout(() => {
        s.next('requirements');
        s.complete();
    }, 1000);
    return () => clearTimeout(i);
});

//get the outcome
//regards requirements as constraints so that we can get the outcome
requirements.subscribe(constraints => design(constrains));
```

> "Design is about taking thing apart in such way that they can be put back together."
> "Learning requires inefficiency."
> "We are dealing notion of time, because obversable are really a notion of value over time."
