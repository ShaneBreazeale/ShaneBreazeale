### Hi, I'm Shane

Internal medicine physician who also builds software, mostly by taking things apart first.

This profile is two halves of that: tools for the clinic (stethoscopes, ECGs, ventilator teaching) and tools for understanding compiled software. The rest is flight and golf simulators, and small fixes for things that broke. All of it is free and open source.

#### Reverse engineering

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/rsleigh"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/rsleigh" alt="rsleigh" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/rsleigh">rsleigh</a></b><br>
      <sub>Rust · <a href="https://github.com/ShaneBreazeale/rsleigh/releases/latest">v0.7.0</a></sub><br>
      A pure-Rust reverse engineering workbench driven by Ghidra's SLEIGH specs: multi-arch decompilation, P-code, binary triage and LLM-assisted analysis.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/ps5-homebrew-tools"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/ps5-homebrew-tools" alt="ps5-homebrew-tools" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/ps5-homebrew-tools">PS5 homebrew tools</a></b><br>
      <sub>C</sub><br>
      Diagnostic payloads and host tools for PS5 homebrew: process and thread capture, kstuff log decoding, kernel-text capture, offline offset analysis and a native app starter.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/CrackMe_PyVMP_v6"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/CrackMe_PyVMP_v6" alt="PyVMProtect crackmes" width="100%"></a>
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
      <a href="https://github.com/ShaneBreazeale/kardia-rs"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/kardia-rs" alt="kardia-rs" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/kardia-rs">kardia-rs</a></b><br>
      <sub>Rust</sub><br>
      A Rust Bluetooth LE workbench for the Kardia 6L six-lead ECG.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/learn-vents"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/learn-vents" alt="learn-vents" width="100%"></a>
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
      <a href="https://github.com/ShaneBreazeale/bevy-metal-timestamps"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/bevy-metal-timestamps" alt="bevy-metal-timestamps" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/bevy-metal-timestamps">bevy-metal-timestamps</a></b><br>
      <sub>Rust · Bevy 0.20</sub><br>
      Real per-frame GPU time for Bevy on Apple GPUs, using Metal pass-boundary timestamp queries.
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/ShaneBreazeale/pawphone"><img src="https://opengraph.githubassets.com/1/ShaneBreazeale/pawphone" alt="Paw Phone" width="100%"></a>
      <b><a href="https://github.com/ShaneBreazeale/pawphone">Paw Phone</a></b><br>
      <sub>Rust · egui</sub><br>
      A macOS desktop toy where cats message each other over a fictional satellite constellation, with procedurally synthesized audio. No cats were connected to space.
    </td>
  </tr>
</table>

**Fixes:** [macos-postscript-print-fix](https://github.com/ShaneBreazeale/macos-postscript-print-fix) restores PostScript printing to AirPrint printers over Horizon/Citrix and `lp`. [speechmike-horizon-usb-fix](https://github.com/ShaneBreazeale/speechmike-horizon-usb-fix) gets a Philips SpeechMike into Horizon's USB redirection menu. [invisible-unicode-scan](https://github.com/ShaneBreazeale/invisible-unicode-scan) is a GitHub Action that catches the invisible Unicode used in Glassworm-style supply-chain attacks.

**Golf:** launch monitor bridges for GSPro: multi-platform Rust connectors for [Square Golf](https://github.com/ShaneBreazeale/squaregolf-connector/releases/latest) and [Garmin](https://github.com/ShaneBreazeale/garmingolf-connector/releases/latest) (forked from community projects), plus older Python bridges for the [GC2 over USB](https://github.com/ShaneBreazeale/GSPro-gc2-API-Interface) and [Flightscope via OCR](https://github.com/ShaneBreazeale/GSPro-Flightscope-OCR-Interface).

**Elsewhere:** [shaneb.org](https://shaneb.org)
