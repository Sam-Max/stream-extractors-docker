# Mod of Streams Extractor Bot [https://github.com/TroJanzHEX/Streams-Extractor]

#### This Bot can extract audios and subtitles from video files.
#### Send any valid video file and the bot shows you available streams in it that can be extracted!!

3. **Deploying on VPS Using Docker**

- Start Docker daemon (skip if already running), if installed by snap then use 2nd command:
    
        sudo dockerd
        sudo snap start docker

     Note: If not started or not starting, run the command below then try to start.

        sudo apt install docker.io

- Build Docker image:

        sudo docker build . -t streams-extractor

- Run the image:

        sudo docker run streams-extractor

- To stop the image:

        sudo docker ps
        sudo docker stop id

## Configs

* BOT_TOKEN     - Get bot token from @BotFather
* APP_ID        - From my.telegram.org 
* API_HASH      - From my.telegram.org 
* AUTH_USERS    - Get from @MissRose_bot by /id command

## Credits

[![TroJanz](https://img.shields.io/badge/Pyrogram%20-%23F37626.svg?&style=for-the-badge&logo=telegram&logoColor=white)](https://github.com/pyrogram/pyrogram)


