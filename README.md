# Infinite Horizons :milky_way:
Resources for the Infinite Horizons Minecraft server `mc.galaxyheart.net`

![Server icon](data/icon.png)



## Client Setup
To play on the Infinite Horizons server:
1. Install [Modrinth](https://modrinth.com/)
2. Download the [modpack](/data/Infinite%20Horizons%201.0.0.mrpack) file
3. Double-click the modpack file to load it into Modrinth
4. Launch the newly created Modrinth profile for the modpack
5. Connect to the server IP: `mc.galaxyheart.net`

### Updates
To update the modpack to the latest version, re-download the modpack file and load it into Modrinth again.

## Server Setup
To run the server:
1. Clone the repository
2. Run `docker compose up`


## Updates
To update the server to the latest modpack:
1. Shut down the server using `docker compose down`
2. Update the repo `git pull`
3. Restart the server `docker compose up`
