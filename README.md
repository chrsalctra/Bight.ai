Bight.ai
v0.2 (Preview Build)

# Author: Christian Alcantara
# Author: www.calcantara.com
# Email: chrsalctra@icloud.com (Accepting feedback!)
# Build: 4 May 2024
# Tested with OpenAI GPT-3.5-Turbo-0125 & 4.0 Turbo on Google Chrome & Safari 
# Development started on March 25, 2024

## TEASER: https://www.youtube.com/watch?v=be6OTgQLsL0
## TRAILER: https://www.youtube.com/watch?v=fZcus0DOrus&t=65s
 

# RELEASE NOTES
# Updating Code Previews
 
# KNOWN ISSUES:

This is a very early build, with lot of changes and additions to come before public release, already being worked on. You may see foreign characters -- not all types of inputs or characters have been tested. Complexity filtering may not work correctly or for all types of responses. Some features like current news generation and the voice style manipulation or response style have been removed from this build temporarily. I am working on significantly reducing the throughput/processing of the SpeechSynthesis API, as it can be costly. Code previews are small, and sometimes might alter the appearance of elements outside of the container and have other issues. 

Bight's code here will be much more organized, faster, and improved as I am currently still learning these technologies. My goal is to have as much of the processing done here. This version has not been tested on all devices or browsers. You may submit bugs and issues using the button on the page.
Thank you, enjoy!


## REQUIRMENTS:

1. Make sure you have NPM/Node installed: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
2. You must have an OpenAPI Key for this to work at all. 
You'll need ElevenLabs Speech Synthesis key as well. 
Current News/Events feature has been removed from this build temporarily.

All APIs offer a free trial or reduced initiation costs. Reach out to me if you have any issues or questions --> chrsalctra@icloud.com

        https://elevenlabs.io/docs/api-reference/text-to-speech
        https://platform.openai.com/docs/introduction
        https://newsapi.org (in progress)
        Google Translate API (Free): "https://translate.googleapis.com/translate_a/single?client=gtx&sl="...

3. You MUST place the keys+assistant ID in the root in a keys.ts file 

5. Make sure Code Retrieval and Code Interpreter are set to ON

## START:

1. npm install or npm i
2. npm run dev
3. Open [http://localhost:3000] on a browser. 
