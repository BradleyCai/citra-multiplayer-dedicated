# Citra Multiplayer Dedicated Lobby

Quickly stand up new dedicated multiplayer lobbies that will be broadcasted on Citra.

## Usage
```
sudo docker run -d \
  --publish 5000:5000/udp
  citraemu/citra-multiplayer-dedicated \
  --room-name "Dedicated (REGION) - GAME TITLE" \
  --preferred-game "GAME TITLE" \
  --preferred-game-id "TITLE ID" \
  --port 5000 \
  --max_members 4 \
  --username "CITRA ACCOUNT USERNAME"
  --token "CITRA ACCOUNT TOKEN" \
  --announce-url https://api.citra-emu.org/lobby
```
