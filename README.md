# Mutter
Minimalist Zero-Trust Voice and Text chat/talk server/client built on Rust.

## Usage
### CLIENT:
- /join «channel»          -> Joins voice channel **OR** Joins text channel.
- /list users «channel»    -> List users with acess to the **«channel»**.
- /list «channel»          -> List chat from text channel **OR** List current users is voice channel.
- /dc «channel»            -> Disconnect from **«channel»**.
- /dc all                  -> Disconnect from all channels.
- /sound «user» «value»    -> Changes user Volume to **«value»**.
- /print «channel» «value» -> Writes to text **«channel»**.

### ADMIN:
- /create voice «channel» -» Creates a voice channel
- /create text «channel» -» Creates a text channel
- /delete «channel» -» Delets **«channel»**.
- /add «channel» «user» -» Gives user acess to **«channel»**.
- /remove «channel» «user» -» Removes user acess to **«channel»**.
- /dc «channel» «user» -» Disconnects **«user»** from **«channel»**.
