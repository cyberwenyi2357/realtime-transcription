# AssemblyAI Real-Time Transcription Browser Example
adaptive layout
This open-source repo provided by AssemblyAI displays how to use our real-time API in the browser!

In this app, we grab an audio stream from the user's computer and then send that over a WebSocket to AssemblyAI for real-time transcription. Once AssemblyAI begins transcribing, we display the text in the browser. This is accomplished using Express for our backend and the AudioWorklet to process the raw audio.

## How To Install and Run the Project

##### ❗Important❗

- Before running this app, you need to upgrade your AssemblyAI account. The real-time API is only available to upgraded accounts at this time.
- Running the app before upgrading will cause an **error with a 402 status code.** ⚠️
- To upgrade your account you need to add a card. You can do that in your dashboard [here](https://app.assemblyai.com/)!

##### Instructions

1. Clone the repo to your local machine.
2. Open a terminal in the main directory housing the project. In this case `realtime-transcription-browser-js-example`.
3. Run `yarn install` to ensure all dependencies are installed.
4. Create a .env file and set your AssemblyAI API key. Use the [.env.example](./.env) as a reference.
5. Start the application with the command `yarn serve` (will run on port 8000).

## Further Documentation

- [AssemblyAI Real-Time Documentation](https://www.assemblyai.com/docs/speech-to-text/real-time)
- [MDN AudioWorklet](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Using_AudioWorklet)
- [Express](https://expressjs.com/)

## Contact Us

If you have any questions, please feel free to reach out to our Support team - support@assemblyai.com!
