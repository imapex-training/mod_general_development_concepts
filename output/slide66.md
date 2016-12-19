## Asking user for input 

```
# Ask user for their name
echo "What is your name?"

# "read" the input and save to variable 
read username

# Hide the input with -s
echo "What is the secret word?"
read -s secret

echo "The name given was: $username."
echo "The secret word was: $secret... don't tell anyone."

```

