Version [4.61.1](https://github.com/tqdm/tqdm/releases/tag/v4.61.1) of `tqdm` with [Conda's patches](https://github.com/anaconda/conda/tree/0dbf85e0546e0b0dc060c8265ec936591ccbe980/tools/vendoring/patches) applied.

Perfect for when PyInstaller is bloating your program up.

Source was directly extracted from a [pre-patched version](https://github.com/conda/conda-lock/tree/9308e25d106a2f3725f856459c9031cbfffd8e7d/conda_lock/_vendor/conda/_vendor/tqdm).

For more information on what vendoring is, check [this](https://stackoverflow.com/a/26217631/6879778) out.

The package name has been changed to `tqdm_vendored` to prevent against conflicts.

Just make it simple.
