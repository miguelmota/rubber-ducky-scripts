# Mac OSX Reverse Bash Shell

Starts a reverse bash shell instance in the background that connects to your server on port 1337.

On your server make sure to run the netcat listener on the port.

```bash
nc -l -p 1337n
```

Update the ip address of your server (`0.0.0.0`) in `source.txt`.

# License

MIT
