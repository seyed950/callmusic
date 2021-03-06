# đ§ Calls Music 1 â A multi-chat Telegram group call audio streaming bot based on [tgcalls](https://github.com/MarshalX/tgcalls)

## âī¸ Requirements

- FFmpeg
- Python 3.7+

## đ Deployment

### đ  Config

Copy `example.env` to `.env` and fill it with your credentials.

### â¨ The good way

1. Install Python requirements:
   ```bash
   pip install -U -r requirements.txt
   ```
2. Run:
   ```bash
   python -m callsmusic
   ```

### đŦ Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

### đĩ Heroku

[Click here](https://heroku.com/deploy?template=https://github.com/callsmusic/callsmusic)

## âšī¸ Commands

| Command | Description                                          |
| ------- | ---------------------------------------------------- |
| /play   | play the replied audio file or YouTube video         |
| /pause  | pause the audio stream                               |
| /resume | resume the audio stream                              |
| /skip   | skip the current audio stream                        |
| /mute   | mute the userbot                                     |
| /unmute | unmute the userbot                                   |
| /stop   | clear the queue and remove the userbot from the call |

## đ License

### GNU Affero General Public License v3.0

[Read more](http://www.gnu.org/licenses/#AGPL)
