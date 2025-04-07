# RMCCP-CCPEDIA
The place to edit MIDI CC Values templatesfor Royale MIDI CC Party app

## About the app

Royale MIDI CC Party is a straightforward, fun app designed to create, store, and launch MIDI CC presets. This application has been developed with fast live performance in mind by someone who has been recording live shows all year long. Grab your hardware synth or groovebox, connect it to your iPad using MIDI, set your MIDI channel and CC channels, and start tweaking your kits. In a few seconds, you can enjoy and play one of several creative preset templates available.

More info about the app [here](https://royalemidiccparty.royalefougard.com/)

## How it works?

- 1 - Fork this repo
- 2 - update the `ccpedia.json` file
- 3 - create a PR. 

Then I'll review changes and integrate them (possibly) in a future version of the App

## Don't be exhaustive

Maybe we don't need all the CC Values to have fun with our gear. So just add the ones you like. 


## JSON Format

`{ "title": "MY awesome CC Param ", "presetTitle": "10CHARSMAX", "ccNumber": 47, "category": "My Super Groooooovebox" }`

- `title`: a comprehensive title. **Made to make searching easy**.
- `presetTitle`: a 10 chars max title. **This will fill your preset's title.**
- `ccNumber`: an unsigned int between 0 and 127
- `category`: The name of your synth/groovebox. **Will create a nice section to group the CC params**

Examples:

`{ "title": "CP CLASSIC - Hold Time", "presetTitle": "CPCtlHld", "ccNumber": 21, "category": "Elektron Analog Rytm" }`

`{ "title": "VAP - P1 Shape 2", "presetTitle": "P1Shp2", "ccNumber": 27, "category": "Polyend Synth" }`

`{ "title": "Performance Effect Slot 6 Value - Top Row", "presetTitle": "Slot6", "ccNumber": 56, "category": "Polyend Tracker" }`

