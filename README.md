# ringqueue

```
rq := NewRingqueue()

type Msg struct {}

rq.Add(Msg{})

item, ok := rq.Remove()
if ok {
  msg := item.(Msg)
}
```
