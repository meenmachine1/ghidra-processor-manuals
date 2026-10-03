# ghidra-processor-manuals
Uploaded PDFs for Ghidra Processor manuals

This is meant for use with [ghidra-manuals](https://github.com/meenmachine1/ghidra-manuals) which will automatically download and place processor manuals in the correct folders in your Ghidra install.

The manuals are published as assets of the [`manuals` release](https://github.com/meenmachine1/ghidra-processor-manuals/releases/tag/manuals), named `<Processor>-<filename>` (e.g. `ARM-DDI0487H_a_a-profile_architecture_reference_manual.pdf`). That's where ghidra-manuals downloads them from first, and where new or corrected manuals are added (with `tools/publish_mirror.py` in ghidra-manuals).

The PDFs under `Ghidra/` in this repo are kept for older versions of ghidra-manuals that download them from there, but new manuals are only added to the release.
