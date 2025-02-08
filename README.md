## TTS Assets

**Resource Api for a TTS engine**

> The emoji files were extracted from SmartVoice, credits to the creator.

### Getting started

A json file (index.json) is created with the following structure:

    {
	  "title": "TTS Assets",
	  "version": "1.0.1",
	  "types": ["emoji", "punctuation"],
	  "assets": [
		{
		  "locale": "ar-SA",
		  "name": "ara-SAU",
		  "type": "emoji"
		},
		{
		  "locale": "en-US",
		  "name": "eng-USA",
		  "type": "punctuation"
	    }
	  ]
    }

It can be obtained with the following link
base:

    https://raw.githubusercontent.com/YOUR_USER/YOUR_REPOSITORY/main/

with link to the minified JSON:

    https://raw.githubusercontent.com/YOUR_USER/YOUR_REPOSITORY/main/index.min.json
    
   Resources are stored in the “assets” folder with the following structure:
   

    📂 assets/ 
    ├── 📂 emoji/ 
    ├──── ara-SAU.json 
    ├──── zho.json
    ├── 📂 punctuation/
    ├──── por-PRT.json 
    ├──── eng-IND.json

to access the resources you can use the link from:

    https://raw.githubusercontent.com/YOUR_USER/YOUR_REPOSITORY/main/assets/${type}/${name}.json

   
### Elements to add

 - [x] Emojis
 - [ ] Language icons
 - [ ] Punctuation
 - [ ] Numbers

