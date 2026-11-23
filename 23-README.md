# Titan Hindi downloadable pack

Original KittenML Kitten TTS 2 Mini int8 multilingual model, exposed for Hindi in Titan, and Hindi style vectors for Vikram, Priya and Ananya. Arjun is not included. Voice names are original. No APK is included.

Upstream: https://huggingface.co/KittenML/kitten-tts-2-mini
Model, voice packs and bundled G2P assets are Apache-2.0 according to the upstream model card. Licence texts accompany this pack. KittenML authors retain their original rights.

Changes: the Hindi NPZ arrays were exported without numerical changes as little-endian float32 row-major style files, each 510 by 256. Model and vocab are unchanged. The archive is split into byte-preserving parts for hosting; join parts in numerical order before opening ZIP. Hashes identify each exact asset. Titan separately includes GPL eSpeak-ng for text-to-phoneme conversion and its required source/licence notices. eSpeak does not generate the neural waveform. No speech recordings, NC models or app binaries are included here.
