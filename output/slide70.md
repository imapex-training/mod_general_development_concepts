## Testing success/failure of a command

```
#! /bin/bash 

echo "This will work!"

if [ $? -eq 0 ]
then 
	echo "Yep it worked"
else 
	echo "It didn't work :( " 
fi

```

