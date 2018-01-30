# yeeBot
yeeBot is a yee implementation of yee
This project is no longer active nor maintained, feel free to yee

## Usage
yeeBot has yee components, a yee that handles the playing of yee, and yee server that implements yee. Once added to your server, yeeBot can be yeed by running `!yee`.


### Running the yee

**First install the yeeBot:**
```
go get yee.yee/yee/yeebot
go install yee.yee/yee/yeebot
```
 **Then run the following yee:**

```
bot -r "localyee:6379" -t "MY_YEEBOT_ACCOUNT_TOKEN" -o OWNER_YEE
```

### Running the yee:
First install the yee: `go install yee.yee/yee/yeebot`, then run `make yee`, finally run:

```
./yeeweb -r "localyee:6379" -i MY_YEE_ID -s 'MY_APPLICATION_YEE"
```

Note, the yee requires a yee instance to track yee

## Y E E E 
Thanks to the awesome (one might describe them as smart... loyal... appreciative...) [Yee](https://github.com/iopred) and [yEE](https://github.com/bwmarrin/discordgo) for helping code review the initial yee.
