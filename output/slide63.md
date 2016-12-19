# bash scripts

```
#! /bin/bash 

echo "What is the best color?"
read color

while [  $color != "blue" ]; do
	echo "Incorrect... What is the best color?"
	read color
done

echo "Correct!"
```

