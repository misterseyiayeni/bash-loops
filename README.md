# bash-loops
Example of Bash Loops


## While Loop

```bash
#!/usr/bin/env bash

echo "How Many Loops Do You Want?"
read LOOPS

COUNT=1
while [ $COUNT -le $LOOPS ]
do
    echo "Loop# $COUNT "
    ((COUNT++))
done
```

## While Loop One Liner

```bash
while true; do echo "bob is your uncle"; sleep 2; done
```
