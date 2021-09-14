# umbrel-help
Some useful tips when you have an Umbrel Lightning Node

## Run the lncli command

Connect to your node through SSH using a terminal window
```
ssh umbrel@umbrel.local
```
You will need to enter your node password


Enter the LND docker container
```
docker exec -it lnd sh
```

Execute the desired command
```
lncli getinfo
