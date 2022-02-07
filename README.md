# SoundObject binary distribution.

![capture](https://user-images.githubusercontent.com/67182469/148635576-bcc81a03-d5d6-4b11-b905-dd6d36ffbfb1.png)

SoundObject creates a binaural sound with the senses of three-dimensional sound localization from a monaural acoustic source and its positional information. It supports headphones-based as well as stereo speakers-based 3D spatial sound.

Conventional three-dimensional binaural sound processors implement sound localization with the convolution of an acoustic source and head-related impulse response (HRIR) that represents scattering by the head. Since the convolution consumes a large amount of computational resource, SoundObject assumes that scattering by a head consists of scattering by a rigid sphere and pinnae (earlobes), then enables sound localization with simplified sphere and pinna scattering effect filters.

And in many cases, conventional convolution-based binaural sound rarely creates a sense of front distance, while SoundObject enables it by reflected waves in a reverberation room.

Furthermore, Doppler effect inevitably results from a moving acoustic source. Generally, sine waves whose frequency difference is 0.3% are distinguishable as different sounds. This fact implies that the recognizable Doppler effect results from an acoustic source whose speed exceeds approximately 1m/s. Since it is never high speed, SoundObject constantly adds Doppler effect when an acoustic source is moving.

SoundObject is provided as a VST 3 plug-in for digital audio workstations (DAW) and supports 44.1KHz, 48KHz, and 96KHz sampling rates.  OS environments are 64bit Windows 10 and macOS 10.14. Refer to the following document for details.

https://suzumushi0.hatenablog.com/entry/SOv1/SO_EN

SoundObject はモノラル音源とその位置情報から 3 次元の定位感のあるバイノーラルサウンドを生成する．また，ヘッドホンによる 3D サウンドだけでなく，ステレオスピーカによる 3D サウンドにも対応している．

従来の 3 次元バイノーラルサウンドプロセッサーは，頭部による散乱を表す頭部インパルス応答 (Head-Related Impulse Response: HRIR) と音源の畳み込みによって，定位感を実現している．この畳み込みは大量の計算リソースを必要とするため，SoundObject では，頭部による散乱は剛体球による散乱と耳介 (耳たぶ) による散乱によって構成されると想定し，簡易な球散乱効果フィルタと耳介散乱効果フィルタにより定位感を実現している．

また，多くの場合，従来の畳み込みによるバイノーラルサウンドでは前方方向の距離感が殆ど得られないが，SoundObject では残響室による反射波によって，これを実現している．

更に，音源の移動によってドップラー効果は必ず生じる．一般に，周波数が 0.3% 異なる正弦波は異なる音として識別できる．これは，約 1m/s を越える速度の音源から，認識可能なドップラー効果が生じる事を意味している．1m/s は決して高速では無いため，SoundObject では音源の移動の際に必ずドップラー効果を加えている．

SoundObject はディジタルオーディオワークステーション (Digital Audio Workstations: DAW) の VST 3 plug-in として提供され，44.1KHz, 48KHz, 96KHz のサンプリングレートをサポートしている．また，OS 環境は 64 bit の Windows 10 及び macOS 10.14 となる．詳細は以下のドキュメントを参照．

https://suzumushi0.hatenablog.com/entry/SOv1/SO_JP

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a> at no charge.

<img width="100" src="https://user-images.githubusercontent.com/67182469/130337395-b8ab38cd-e66e-4056-b441-49d33337410e.png">
VST is a registered trademark of Steinberg Media Technologies GmbH.
