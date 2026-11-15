# lab-assistant-models

Model files downloaded by the lab-assistant speech-to-text sidecar. Each set of files is published as a GitHub Release of this repository; the application pins every file's size and SHA-256.

## Phonon 2.5 (ONNX) — release `models-phonon-2.5`

Byte-identical mirror of [`enriqueag/phonon-2.5-onnx`](https://huggingface.co/enriqueag/phonon-2.5-onnx) at revision `5a76001bd8dfc058632290d2ef594236b7ca2bd4`.

| File | Bytes | SHA-256 |
|---|---:|---|
| `encoder.exact2x2.onnx` | 362728506 | `786bb68c5489d2b894b4565e1a123f5ad3d2197e84f5e7ffefca63d1ecf82033` |
| `decoder_joint.int8.onnx` | 17644009 | `ccfe6ed79343be430a1d706dbfc8dec8b88cd2110bd3a695f8448e10ac34f8c9` |
| `vocab.txt` | 93928 | `048eb9ded015a578855d1661c244f4f1101e6d68c82a5c3bce14dff046a11431` |

Phonon 2.5 © 2026 Fermion Research, derived from NVIDIA Parakeet TDT 0.6B v3 © NVIDIA Corporation, exported to ONNX by enriqueag. The files are unmodified.

## Licence

The model weights are licensed under the Creative Commons Attribution 4.0 International licence (CC-BY-4.0). See `LICENSE` and `NOTICE`.
