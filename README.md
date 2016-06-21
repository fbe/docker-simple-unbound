# Simple unbound #
Just run 
```
docker run -p 53:53/udp -v /your/unbound.conf:/etc/unbound/unbound.conf fbecker/simple-unbound 

```

to run a really simple unbound.
