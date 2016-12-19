### Helpful Hints and Gotchas

* Escaping command characters

```
# Wrong
curl -u admin:cisco! 192.168.0.1/home 
	
# Rigth
curl -u admin:cisco\! 192.168.0.1/home
```

