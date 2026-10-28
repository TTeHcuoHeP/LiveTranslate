# LiveTranslateLiveTranslate
LiveTranslate is a Windows desktop app that translates spoken audio from your computer into live subtitles. Use it during online calls, meetings, webinars, or while watching videos in another language.
Features
- 8 languages: English, Russian, Chinese, Korean, Indonesian, French, German, and Spanish.
- Translation in either direction between supported languages.
- Automatic source-language detection.
- A floating subtitle window with adjustable text size and background opacity.
- Original transcript and translated text with scrollable history.
- Locally saved sessions with date, time, and translation direction.
- Copy transcripts or export them as TXT or Markdown.
- Automatic stop after one minute of silence.
Getting started
1. Download the latest LiveTranslate Setup.exe from this repository’s Releases section.
2. Install the app on Windows 10 or 11, 64-bit.
3. Create an API key at OpenAI Platform and set up API billing.
4. Open Settings, paste your key, and click Save key.
5. Click Test connection to check access.
6. Choose the From and To languages at the top of the app.
7. Select the audio output device used by your call or video.
8. Click Start Translation and play the audio.
Subtitles appear in the app and in a separate floating window. Click Stop Translation when you finish.
Good to know
- You need your own OpenAI API key with access to gpt-realtime-translate. API usage is billed separately from a ChatGPT subscription.
- The app captures computer playback audio. It does not capture your microphone or send translated speech into a call.
- Audio is sent directly to OpenAI for processing. LiveTranslate does not save audio recordings.
- Transcripts are saved locally on your computer. Your API key is encrypted using Windows secure storage.
- Closing a window does not stop translation. Use Stop Translation or Quit from the system tray. Auto-stop activates after 60 seconds without sound; music and other playback can keep it running.
- Press Ctrl + Shift + L to restore the subtitle window and mouse controls.
Developer
Developed by Alsim Mamedov
isograph.me
