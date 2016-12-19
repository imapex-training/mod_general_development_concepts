## Loops 

### for loop

```
#!/bin/bash
for i in $( ls ); do
   echo item: $i
done		
```

### while loop

```
#!/bin/bash 
COUNTER=0
while [  $COUNTER -lt 10 ]; do
	echo The counter is $COUNTER
	COUNTER=$(( COUNTER+1 ))
done	
```	

