<p align="left">
<a href ="https://github.com/niedev/RTranslator/blob/v2.00/README.zh-CN.md"><img src="https://img.shields.io/badge/README-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-555555.svg"/></a>

<br /><br />

<img src="https://github.com/niedev/RTranslator/blob/v2.00/images/logo_beta_cut.png" width="280">

RTranslator is an (<a href='https://github.com/niedev/RTranslator?tab=readme-ov-file#libraries-and-models'>almost</a>) open-source, free, and offline real-time translation app for Android.

Connect to someone who has the app, connect Bluetooth headphones, put the phone in your pocket and you can have a conversation as if the other person spoke your language.
<br /><br />

![Conversation mode](https://github.com/niedev/RTranslator/blob/v2.00/images/Conversation_image.png)
<br /><br />
![WalkieTalkie mode and Costs](https://github.com/niedev/RTranslator/blob/v2.00/images/TextTranslation_and_WalkieTalkie.png)
<br /><br />

<h3>Conversation mode</h3>

The Conversation mode is the main feature of RTranslator. In this mode, you can connect with another phone that uses this app. If the user accepts your connection request:

- When you talk, your phone (or the Bluetooth headset, if connected) will capture the audio.

- The audio captured will be converted into text and sent to the interlocutor's phone.

- The interlocutors' phone will translate the text received into his language.

- The interlocutors' phone will convert the translated text into audio and will reproduce it from its speaker (or by the Bluetooth headset of the interlocutor if connected to his phone). 

All this in both directions.

Each user can have more than one connected phone so that you can translate conversations between more than two people and in any combination.
<br /><br />

<h3>WalkieTalkie mode</h3>

If conversation mode is useful for having a long conversation with someone, this mode instead is designed for quick conversations, such as asking for information on the street or talking to a shop assistant.

This mode only translates conversations between two people, it doesn't work with Bluetooth headsets, and you have to talk in turns. It's not a real simultaneous translation, but it can work with only one phone.

In this mode, the smartphone microphone will listen in two languages (selectable in the same screen of the walkie talkie mode) simultaneously. <br />
The app will detect in which language the interlocutor is speaking, translate the audio into the other language, convert the text into audio, and then reproduce it from the phone speaker. When the TTS has finished, it will automatically resume listening.
<br /><br />

<h3>Text translation mode</h3>

This mode is just a classic text translator, but always useful.
<br /><br />

<h3>General</h3>

RTranslator uses <a href="https://ai.meta.com/research/no-language-left-behind/">Meta\'s NLLB</a> for translation and <a href="https://openai.com/index/whisper/">OpenAi\'s Whisper</a> for speech recognition, both are (<a href='https://github.com/niedev/RTranslator?tab=readme-ov-file#libraries-and-models'>almost</a>) open-source and state of the art AIs, have excellent quality and run directly on the phone, ensuring absolute privacy and the possibility of using RTranslator even offline without loss of quality.

Also, RTranslator works even in the background, with the phone on standby or when using other apps (only when you use Conversation or WalkieTalkie modes). However, some phones limit the power in the background so in that case it is better to avoid it and keep the app open with the screen on.

<a href="https://www.producthunt.com/posts/rtranslator?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-rtranslator" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=274849&theme=light" alt="RTranslator - World's first open-source simultaneous translation app. | Product Hunt" style="width: 250px; height: 80px;" /></a>
<br /><br />

<h3>What's new in version 2.0</h3>

The Google API's have been replaced by <a href="https://ai.meta.com/research/no-language-left-behind/">Meta\'s NLLB</a> for translation and <a href="https://openai.com/index/whisper/">OpenAi\'s Whisper</a> for speech recognition. These AI models run directly on your phone, so now the app is totally free and with no configuration required!

A classic text translation mode has been added.

Bluetooth LE device search has been improved.

Fixed some bugs.
<br /><br />

<h3>Performance</h3>

I have optimized the AI models a lot to minimize RAM consumption and execution time, despite this however to be able to use the app without the risk of crashing you need a phone with at least **6GB of RAM**, and to have a good enough execution time you need a phone with a fast enough CPU.

If you have a pretty crappy phone (or if you want maximum speed) you can always use <a href="https://github.com/niedev/RTranslator/tree/v1.00">version 1.0 of RTranslator</a> (but since it uses Google APIs it's not free and needs some initial setup).
<br /><br />


<h3>Download</h3>

To install the app, download the latest version of the app apk file from https://github.com/niedev/RTranslator/releases/ and install it (ignore the other files, those will be downloaded automatically by the app on the first start).

<a href='https://github.com/niedev/RTranslator/releases'><img alt='Get it on GitHub' src='https://github.com/niedev/RTranslator/blob/v2.00/images/get_it_on_github.png' style="width: 180px; height: 58px;" /></a>

On the first launch, you will need to download the models for translation and speech recognition (1.2GB) and once done you can start translating.
<br /><br />


<h3>Supported languages</h3>

The languages supported are as follows:

Arabic, Bulgarian, Catalan, Chinese, Czech, Danish, German, Greek, English, Spanish, Finnish, French, Croatian, Italian, Japanese, Korean, Dutch, Polish, Portuguese, Romanian, Russian, Slovak, Swedish, Tamil, Thai, Turkish, Ukrainian, Urdu, Vietnamese.
<br /><br />

<h3>Privacy</h3>

Privacy is a fundamental right. That's why RTranslator does not collect any personal data (I don't even have a server). For more information, read the <a href="https://github.com/niedev/RTranslator/blob/v2.00/privacy/Privacy_Policy_en.md" target="_blank" rel="noopener noreferrer">privacy policy</a> (for now is the same privacy policy of RTranslator 1.0, but I will update it in the future).
<br /><br />

<h3>Libraries and models</h3>

RTranslator code is completely open-source, but some of the external libraries it uses have less permissive licenses, these are all the external libraries used by the app (with the indication of their license):

<a href="https://github.com/niedev/BluetoothCommunicator">BluetoothCommunicator</a> (open-source): Used for Bluetooth LE communication between devices.

<a href="https://github.com/niedev/GalleryImageSelector">GalleryImageSelector</a> (open-source): Used for selecting and cropping the profile image from the gallery.

[OnnxRuntime](https://github.com/microsoft/onnxruntime) (open-source): Used as an accelerator engine for the AI models.

<a href="https://github.com/google/sentencepiece">SentencePiece</a> (open-source): Used for tokenization of the input text for NLLB.

<a href="https://developers.google.com/ml-kit/language/identification">Ml Kit</a> (closed-source): Used for the identification of the language in the WalkieTalkie mode.
<br /><br />
And the following AI models:

<a href="https://github.com/facebookresearch/fairseq/tree/nllb">NLLB</a> (open-source, but only for non-commercial use): The model used is NLLB-Distilled-600M with KV cache.

<a href="https://github.com/openai/whisper">Whisper</a> (open-source): The model used is Whisper-Small-244M with KV cache.

I converted both models to onnx format and quantized them in int8 (excluding some weights to ensure almost zero quality loss), also I separated some parts of the models to reduce RAM consumption (without this separation some weights were duplicated at runtime consuming more RAM than expected).
<br /><br />

<h3>Donations</h3>

This is an open-source and completely ad-free app, I don't make any money from it.

So, if you like the app and want to say thank you and support the project, you can make a donation via PayPal by clicking on the button below (any amount is well accepted).

<a href='https://www.paypal.com/donate/?business=3VBKS3WC6AFHN&no_recurring=0&currency_code=EUR'><img alt='Donate' src='https://raw.githubusercontent.com/niedev/RTranslator/v2.00/images/Paypal.png' style="width: 190px; height: 80px;" /></a>

In case you will donate, or just live a star, thank you :heart:
<br /><br />

<h3>Bugs and problems</h3>
I remind you that the app is still in beta. The bugs found are the following:

- Sometimes the Bluetooth connection drops.

If you have found any bug please report it by opening an issue, or by writing an email to contact.niedev@gmail.com
<br /><br />

Enjoy your simultaneous translator.
