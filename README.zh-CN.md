<p align="left">
<a href ="https://github.com/niedev/RTranslator/blob/v2.00/README.zh-CN.md"><img src="https://img.shields.io/badge/README-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-555555.svg"/></a>

<img src="https://github.com/niedev/RTranslator/blob/v2.00/images/logo_beta_cut.png" width="280">

RTranslator 是一个几乎开源、免费且离线的安卓实时翻译应用。

与拥有此应用的用户连接，或连接蓝牙耳机，或将手机放在口袋中，就可以像对方说你的语言一样进行对话。
<br /><br />

![对话模式](https://github.com/niedev/RTranslator/blob/v2.00/images/Conversation_image.png)
<br /><br />
![对讲机模式和费用](https://github.com/niedev/RTranslator/blob/v2.00/images/TextTranslation_and_WalkieTalkie.png)
<br /><br />

<h3>对话模式</h3>

对话模式是 RTranslator 的主要功能。在此模式下，您可以与另一部使用该应用的手机连接。如果对方接受您的连接请求：

- 当您讲话时，您的手机（或蓝牙耳机，如果已连接）将捕捉音频。

- 捕捉到的音频将被转换为文本并发送到对方的手机。

- 对方的手机将把收到的文本翻译成他的语言。

- 对方的手机将把翻译后的文本转换为音频，并通过其扬声器（或对方的蓝牙耳机，如果连接到他的手机）播放。

所有这些都是双向进行的。

每个用户可以连接多个手机，以便您可以在多人之间进行翻译对话，并以任何组合进行交流。
<br /><br />

<h3>对讲机模式</h3>

如果对话模式适合与某人进行长时间对话，那么对讲机模式则适合快速对话，例如在街上询问信息或与店员交谈。

此模式仅翻译两人之间的对话，不适用于蓝牙耳机，且需要轮流说话。虽然这不是实时同步翻译，但可以仅用一部手机实现。

在此模式下，智能手机麦克风将同时监听两种语言（在对讲机模式的同一屏幕上可选择）。<br />
应用将检测对方所说的语言，将音频翻译成另一种语言，转换为音频，然后通过手机扬声器播放。当 TTS 完成后，它将自动恢复监听。
<br /><br />

<h3>文本翻译模式</h3>

此模式只是一个经典的文本翻译器，但始终很有用。
<br /><br />

<h3>常规</h3>

RTranslator 使用 <a href="https://ai.meta.com/research/no-language-left-behind/">Meta 的 NLLB</a> 进行翻译，使用 <a href="https://openai.com/index/whisper/">OpenAi 的 Whisper</a> 进行语音识别，这两者都是几乎开源的尖端 AI，具有卓越的质量，并直接在手机上运行，确保绝对隐私，并且即使在离线状态下使用 RTranslator 也不会降低质量。

此外，RTranslator 即使在后台也能运行，手机处于待机状态或使用其他应用时（仅在使用对话或对讲机模式时）。然而，一些手机在后台限制电量，因此在这种情况下，最好避免后台运行并保持应用打开，屏幕亮着。

<a href="https://www.producthunt.com/posts/rtranslator?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-rtranslator" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=274849&theme=light" alt="RTranslator - 世界上第一个开源的实时翻译应用 | Product Hunt" style="width: 250px; height: 80px;" /></a>
<br /><br />

<h3>2.0 版本的新增功能</h3>

谷歌 API 已被 <a href="https://ai.meta.com/research/no-language-left-behind/">Meta 的 NLLB</a> 用于翻译，<a href="https://openai.com/index/whisper/">OpenAi 的 Whisper</a> 用于语音识别。这些 AI 模型直接在您的手机上运行，因此现在该应用完全免费且无需配置！

新增了经典的文本翻译模式。

改进了蓝牙 LE 设备搜索。

修复了一些错误。
<br /><br />

<h3>性能</h3>

我对 AI 模型进行了大量优化，以尽量减少内存消耗和执行时间，尽管如此，为了避免应用崩溃，您需要一部至少 **6GB 内存** 的手机，并且为了获得良好的执行时间，您需要一部 CPU 足够快的手机。

如果您的手机性能较差（或如果您想要最快的速度），您可以使用 <a href="https://github.com/niedev/RTranslator/tree/v1.00">RTranslator 1.0 版本</a>（但由于它使用谷歌 API，因此不是免费的，需要一些初始设置）。
<br /><br />

<h3>下载</h3>

要安装该应用，请从 https://github.com/niedev/RTranslator/releases/ 下载最新版本的应用 apk 文件并安装（忽略其他文件，这些文件将在首次启动时由应用自动下载）。

<a href='https://github.com/niedev/RTranslator/releases'><img alt='在 GitHub 上获取' src='https://github.com/niedev/RTranslator/blob/v2.00/images/get_it_on_github.png' style="width: 180px; height: 58px;" /></a>

首次启动时，您需要下载翻译和语音识别的模型（1.2GB），下载完成后即可开始翻译。
<br /><br />

<h3>支持的语言</h3>

支持的语言如下：

阿拉伯语，保加利亚语，加泰罗尼亚语，中文，捷克语，丹麦语，德语，希腊语，英语，西班牙语，芬兰语，法语，克罗地亚语，意大利语，日语，韩语，荷兰语，波兰语，葡萄牙语，罗马尼亚语，俄语，斯洛伐克语，瑞典语，泰米尔语，泰语，土耳其语，乌克兰语，乌尔都语，越南语。
<br /><br />

<h3>隐私</h3>

隐私是一项基本权利。这就是为什么 RTranslator 不收集任何个人数据（我甚至没有服务器）。更多信息，请阅读 <a href="https://github.com/niedev/RTranslator/blob/v2.00/privacy/Privacy_Policy_en.md" target="_blank" rel="noopener noreferrer">隐私政策</a>（目前是 RTranslator 1.0 的隐私政策，但我将来会更新它）。
<br /><br />

<h3>库和模型</h3>

RTranslator 代码完全开源，但它使用的一些外部库具有较不宽松的许可证，以下是该应用使用的所有外部库（并注明其许可证）：

<a href="https://github.com/niedev/BluetoothCommunicator">BluetoothCommunicator</a>（开源）：用于设备之间的蓝牙 LE 通信。

<a href="https://github.com/niedev/GalleryImageSelector">GalleryImageSelector</a>（开源）：用于从图库中选择和裁剪个人资料图片。

[OnnxRuntime](https://github.com/microsoft/onnxruntime)（开源）：用作 AI 模型的加速引擎。

<a href="https://github.com/google/sentencepiece">SentencePiece</a>（开源）：用于 NLLB 输入文本的分词。

<a href="https://developers.google.com/ml-kit/language/identification">Ml Kit</a>（闭源）：用于对讲机模式中的语言识别。
<br /><br />
以及以下 AI 模型：

<a href="https://github.com/facebookresearch/fairseq/tree/nllb">NLLB</a>（开源，但仅用于非商业用途）：使用的模型是 NLLB-Distilled-600M 带 KV 缓存。

<a href="https://github.com/openai/whisper">Whisper</a>（开源）：使用的模型是 Whisper-Small-244M 带 KV 缓存。

我将这两个模型转换为 onnx 格式，并量化为 int8（排除了一些权重以确保几乎没有质量损失），此外，我将模型的某些部分分开以减少内存消耗（如果不分开，一些权重在运行时会被重复消耗更多内存）。
<br /><br />

<h3>捐赠给项目创作者</h3>

这是一个开源且完全无广告的应用，该项目没有从中赚取任何钱。

因此，如果您喜欢此应用并想表示感谢和支持该项目，可以通过点击下面的按钮通过 PayPal 捐赠（任何金额都很受欢迎）。

<a href='https://www.paypal.com/donate/?business=3VBKS3WC6AFHN&no_recurring=0&currency_code=EUR'><img alt='Donate' src='https://raw.githubusercontent.com/niedev/RTranslator/v2.00/images/Paypal.png' style="width: 190px; height: 80px;" /></a>

如果您进行了捐赠，或只是留下了星标，非常感谢您 :heart
