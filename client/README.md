# Documentating Console Interactions on the Client

## Events
```
Events.START_GAME
```

## Communicating with the server
```
activeGame.broadcast(f(e))
```

Ongoing google doc: https://docs.google.com/document/d/1lcEguYjSl28Dcy8AEVSLFRhSrP-QSNzvggRoPw1iEHM/edit

## Code
### table-service.js
- Represents lobby of before you click "start game" against an opponent
### js/lib/game/play/play-service.js
- Contains functions related to playing cards
```
getActions()
getBuys()
...
```

## Terms
`hero` represents the player with the current turn
