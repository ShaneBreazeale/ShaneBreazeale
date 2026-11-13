### Hi, I'm Shane

Physician who also builds software, mostly by taking things apart first.

This profile is two halves of that: tools for the clinic (stethoscopes, ECGs, ventilator teaching) and tools for understanding compiled software. The rest is flight and golf simulators, and small fixes for things that broke.

#### Reverse engineering

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/rsleigh"><img src="assets/rsleigh.png" alt="rsleigh listing functions in an AArch64 Mach-O and disassembling check_serial, with the FNV-1 constants visible" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/rsleigh">rsleigh</a></b><br>
      <sub>Rust · <a href="https://github.com/ShaneBreazeale/rsleigh/releases/latest">v0.7.0</a></sub><br>
      A pure-Rust reverse engineering workbench driven by Ghidra's SLEIGH specs: multi-arch decompilation, P-code, binary triage and LLM-assisted analysis.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/ps5-homebrew-tools"><img src="assets/ps5-homebrew-tools.png" alt="thread-probe-v2 capture from a PS5 Pro on firmware 13.60, summarized by host/summarize_threads.py" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/ps5-homebrew-tools">PS5 homebrew tools</a></b><br>
      <sub>C</sub><br>
      Diagnostic payloads and host tools for PS5 homebrew: process and thread capture, kstuff log decoding, kernel-text capture, offline offset analysis and a native app starter.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/CrackMe_PyVMP_v6"><img src="assets/pyvmprotect.png" alt="PyVMProtect v6 solve: the captured SHA-256 compare against a 62-character decoy, then the flag" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/CrackMe_PyVMP_v6">PyVMProtect crackmes</a></b><br>
      <sub>Python · <a href="https://github.com/ShaneBreazeale/pyvmprotect-static-lift">original</a> · <a href="https://github.com/ShaneBreazeale/crackme-pyvmprotect-v5">v5</a> · <a href="https://github.com/ShaneBreazeale/CrackMe_PyVMP_v6">v6</a></sub><br>
      Static lifts of three PyVMProtect-obfuscated crackmes, each a custom stack VM: handlers decoded with Unicorn, hash preimage bounds recovered, a Wine audit-hook crack for "The Fortress".
    </td>
  </tr>
</table>

#### For the clinic

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/openstetho"><img src="assets/openstetho.jpg" alt="openstetho's live viewer: heart-sound waveform over the last 5 seconds above a log-mel spectrogram" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/openstetho">openstetho</a></b><br>
      <sub>Python · <a href="https://github.com/ShaneBreazeale/openstetho/releases/latest">v0.4.1</a></sub><br>
      A toolkit for Bluetooth digital stethoscopes: capture, DSP, log-mel spectrograms and murmur classification on the Apple Neural Engine.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/kardia-rs"><img src="assets/kardia-rs.jpg" alt="kardia-rs six-lead limb ECG report from a live Kardia 6L capture, with experimental automated measurements" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/kardia-rs">kardia-rs</a></b><br>
      <sub>Rust</sub><br>
      A Rust Bluetooth LE workbench for the Kardia 6L six-lead ECG.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/learn-vents"><img src="assets/learn-vents.jpg" alt="learn-vents waveform tab: peak and plateau pressures, driving pressure and mechanical power above pressure and flow curves" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/learn-vents">learn-vents</a></b><br>
      <sub>Web · <a href="https://pulmcrit.netlify.app">live</a></sub><br>
      An interactive tool for teaching mechanical ventilation physiology to residents and fellows. Sibling: <a href="https://github.com/ShaneBreazeale/insulinclac">insulinclac</a>, a <a href="https://penrx.netlify.app/">PWA</a> for writing insulin pen prescriptions.
    </td>
  </tr>
</table>

#### Simulation and graphics

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/machtuck"><img src="assets/machtuck.jpg" alt="machtuck: above the anvil, core entry at FL350, the virtual cockpit, and Greenacres from 300 m" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/machtuck">machtuck</a></b><br>
      <sub>WebGL2</sub><br>
      A convective upset simulator for the Learjet 60 (N722BD), in the browser.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/bevy-metal-timestamps"><img src="assets/bevy-metal-timestamps.jpg" alt="bevy-metal-timestamps stress example: 216,000 cubes on an Apple M4, GPU p50 16.40 ms against a 23.33 ms frame" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/bevy-metal-timestamps">bevy-metal-timestamps</a></b><br>
      <sub>Rust · Bevy 0.20</sub><br>
      Real per-frame GPU time for Bevy on Apple GPUs, using Metal pass-boundary timestamp queries.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/squaregolf-connector"><img src="assets/golf-connectors.jpg" alt="SquareGolf Connector desktop app: launch monitor connected, GSPro OpenAPI selected as the output" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/squaregolf-connector">Golf launch monitor connectors</a></b><br>
      <sub>Rust · <a href="https://github.com/ShaneBreazeale/squaregolf-connector/releases/latest">Square Golf</a> · <a href="https://github.com/ShaneBreazeale/garmingolf-connector/releases/latest">Garmin</a></sub><br>
      Multi-platform bridges that send launch monitor shots to golf simulators: a Tauri desktop app for Square Golf (GSPro, Infinite Tees, SquareLaunch) and a Garmin E6 / Play on PC bridge for GSPro. Forked from community projects.
    </td>
  </tr>
</table>

**Fixes:** [macos-postscript-print-fix](https://github.com/ShaneBreazeale/macos-postscript-print-fix) restores PostScript printing to AirPrint printers over Horizon/Citrix and `lp`. [speechmike-horizon-usb-fix](https://github.com/ShaneBreazeale/speechmike-horizon-usb-fix) gets a Philips SpeechMike into Horizon's USB redirection menu. [invisible-unicode-scan](https://github.com/ShaneBreazeale/invisible-unicode-scan) is a GitHub Action that catches the invisible Unicode used in Glassworm-style supply-chain attacks.

**Older golf bridges:** Python interfaces between GSPro and the [GC2 over USB](https://github.com/ShaneBreazeale/GSPro-gc2-API-Interface) and [Flightscope via OCR](https://github.com/ShaneBreazeale/GSPro-Flightscope-OCR-Interface).

**Elsewhere:** [shaneb.org](https://shaneb.org)
