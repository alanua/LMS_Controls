## Some Example Commands for DialogFlow / GoogleHome Interface
Once setup and configured you can use your Google Home or Google Assistant to issue voice commands to the LMS squeeze players.  The commands can be issued as explicit or implicit intents. 
## Explicit Intents
Explicit intents are the commands given to the app once it's been called up and is active on your Google device.  It's characterized by the startup phrase:  **"Hey google talk to LMS Controls"**.  This calls up the Welcome intent (**"How can I help?"**) of the app at wich time you are free to issue your voice commands.  Once all commands are issued you say **"Goodbye"** (or after 10 seconds of no requests) the App closes and returns control to the Google environment.
## Implicit Intents
Implicit intents is a voice command given to the google environment directly as part of the app start-up command.  It's characterized by the phrase **"Hey google ask LMS Controls to ...**.  This calls up the app, skips the Welcome intent and goes directly to the command issued after the phrase **"ask LMS Controls to...**.  The command is executed and in the LMS application, there is a 10 second pause that allows you to issue further follow-up commands directly (explicit intents) like **"set volume to 40"** or **"set shuffle on"** without having to re-issue the startup phrase.  After 10 seconds of no requests, the app exits and returns control to the google environment.
## Example Explicit Intent Commands
**Start-Up Phrases:** are used to call up the app for Google Home or Google Assistant and prepare for explicit intents.
  - "Hey google, talk to LMS Controls"
  - "Hey google, LMS Controls"
  - "OK google, ask for LMS Controls"

**Explicit Intents:** After the start-up phrase above, the LMS Controls apps is called up and the Welcome intent is played **"How can I help?"**. Now you are ready to issue the explicit intents (voice commands) to your players. Some example phrases are listed below by category.
- **Play** intents are structured as follows:  "Play [artist, album, song or playlist] [name / title] using player [player name] with shuffle [on/off]".  The phrase "using player" can be substituted with "in the" for simplicity though accuracy may suffer a bit.
  - "Play artist Pink Floyd" or "Play artist Pink Floyd in the kitchen" or "Play artist Pink Floyd with shuffle on" or Play artist Pink Floyd in the kitchen with shuffle on"
  - "Play album Breakfast in America" or "Play album Crime of the Century by Supertramp" or Play ablum Pieces of Eight by Supertramp in the mediaroom with shuffle on"
  

**Note:**  When items are lef out of the command (ie: player name, music source, etc..) LMS Controls uses the current value in the HA GUI to fill in.  If the item is critical, LMS Controls will prompt for it.