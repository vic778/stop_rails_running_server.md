To stop all running Rails servers type the following is the terminal

```shell
  kill -9 $(lsof -i tcp:3000 -t)
```
