# this is my heading

### this is another heading

**some bold text**


[
{
 "saveName": "joseph1"
 "score": 45
 "volume": 15
},
{
 "saveName": "joseph2"
 "score": 55
 "volume": 17
}
]

currentVolume = 10
currentScore = 0

openFile = open(".json", "r")
fileSaveGames = json.load(openfile)

saveGameNames = []
for saveGame in fileSaveGames:
  saveGameNames.append(saveGame["saveName"])


print (saveGameNames)

pickedSaveGame = "joseph1"

for saveGame in fileSaveGames:
  if saveGame["saveName"] == pickedSaveGame
    currentVolume = saveGame["volume"]
	currentScore = saveGame["score"]

print(currentVolume)
print(currentScore)
