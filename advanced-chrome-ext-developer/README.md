# Test excersise for Advanced Javascript / Chrome ext Developer

The following exercise is to create a token gated Chrome Extension experience. The core concept is that a game is loaded with a single view, and the end user can unlock content as their progress which is provided by the Chrome Extension (some content is shared and some is hidden). 

## Part 1 - Create the Chrome Extension and set up working code example

- Download this example code https://github.com/nicktaras/basic-rpg 
- Set up your working environment to help you serve / develop with this example
- When the game loads the simple RPG game is shown in the page showing 3 paths.
- Start to build a new chrome extension that is targeted towards this game.
- When the Chrome extension is switched on/off, the games graphics are adjusted (e.g. using CSS, invert the colour, addition of an asset to the canvas or page)
- Within the Chrome extension add 1-3 views to the RPG that can later be dispatched to the website
- Within the Chrome extension add a secret that should not be learnt by the website e.g. "secret111"

## Part 2 - Wallet ownership through extension to create custom experience

- Create a wallet connection inside the webpage (to learn the end users public address)
- Indicate the wallet is connected graphically inside the extension
- Trigger a notification that the RPG game has now opened one of the 3 paths
- When the end user navigates to one of the paths it will now load a new view (from extension data)
- Inside the second dispatch a base64 version of the secret to the end user asking them to copy it
- When the end user navigates to either of the other two paths, the Chrome extension must trigger a prompt for the code.
- Entering the code will do simple check decoding the base64 and checking it matches.
- If the Proof matches the expected value then a notification will let them know they have completed the game. 

## Part 3 (fully optional - based on your time):

1 When the chrome extension is open, show it’s up to date Rinkeby balance
2 Further demonstrate skills using web3 and features available with Chrome extensions

(e.g. API use such as Moralis to load an NFT and use it inside the game, Minting of NFT on a test net on completion of the game).