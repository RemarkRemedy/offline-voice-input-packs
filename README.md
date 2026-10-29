# Offline Voice Input — Ultra NPU packs

App-specific arm64 Android components for Offline Voice Input. The signed APK pins each archive and file SHA-256. These downloads contain no recordings, transcripts, credentials, or private source code.

Parakeet Ultra model: moondream/parakeet-ultra, derived from NVIDIA Parakeet TDT 0.6B v3, CC BY 4.0. ONNX source: Masterx/parakeet-tdt-0.6b-ultra-onnx revision 99b09f030a5a6efeaa13cf2cf54592100ce2c3f1.

Qualcomm runtime: QNN 2.42.0, from ONNX Runtime Android QNN 1.24.3. MediaTek runtime: LiteRT 2.3.0 and Android NeuroPilot SDK 9 adapter. The archives include application model and vendor license notices. The MediaTek adapter is an application component, not a standalone SDK distribution.

The NPU encoder is required. CPU frontend and token decoding remain part of the pipeline. Snapdragon 6s Gen 4, 7s Gen 2, and Dimensity 9500 device tests remain pending.
