### Common While loop... waiting for something to happen

```
#!/bin/bash 
COUNTER=0
while [  $COUNTER -lt 10 ]; do
	echo The counter is $COUNTER
	COUNTER=$(( COUNTER+1 )) 
	sleep 5
done	
```	

