# PHONO REFERENTIA

## Initial Test Equipment

### Reference Disc I — Dynamics & Vocals
**Initial Capture Platform — 2026**

This is the equipment used for the first Phono Referentia cartridge captures.

The initial system is deliberately fairly simple. The Technics SL-QD33 provides a standardized P-Mount platform, the Emotiva XPS-1 Gen2 handles the phono stage, and the resulting line-level signal is recorded directly through the computer's Realtek High Definition Audio input using Audacity.

As the project develops, parts of the recording chain may change. When they do, those changes will be documented rather than silently incorporated into the test process.

These recordings establish the first Phono Referentia capture set and the baseline against which later changes to the test platform can be compared.

---

# Turntable

## Technics SL-QD33

The first Phono Referentia test platform is the **Technics SL-QD33**.

The SL-QD33 is a quartz-controlled direct-drive Technics turntable built around the **T4P / P-Mount cartridge standard**.

For the first stage of this project, P-Mount is particularly useful because it removes several setup variables that normally exist when changing cartridges.

A conventional 1/2-inch cartridge installation requires decisions about alignment, overhang, cartridge position in the headshell, tracking force, and potentially tonearm height. Those adjustments are useful and will become part of Phono Referentia testing later, but they also introduce additional variables.

P-Mount was designed around a standardized cartridge interface.

A T4P cartridge plugs directly into the tonearm and is retained by a single screw. The standard was designed around defined mechanical and electrical characteristics, including a nominal tracking force of approximately **1.25 grams**.

That makes the SL-QD33 a useful place to start.

```text
T4P / P-MOUNT

Cartridge
    │
    ▼
Standardized P-Mount Interface
    │
    ▼
Technics SL-QD33 Tonearm
    │
    ▼
Fixed Turntable Geometry
```

When moving from one compatible P-Mount cartridge to another, there is substantially less cartridge setup involved than there would be when repeatedly mounting conventional cartridges in interchangeable headshells.

For the initial Phono Referentia tests, that is an advantage.

The variable I am primarily interested in changing is:

> **The cartridge and stylus.**

Using the SL-QD33 lets the first group of tests concentrate heavily on that variable without immediately adding alignment differences between cartridge installations.

---

## Why Start With P-Mount?

P-Mount cartridges are not the final limit of Phono Referentia.

They are the **first test platform**.

Starting here gives the project a relatively controlled baseline before moving into conventional 1/2-inch cartridges, interchangeable headshells, different cartridge alignments, different tonearms, moving-coil cartridges, and other configurations.

It also provides an opportunity to document a cartridge system that is sometimes overlooked in modern cartridge discussions.

The first test series can therefore answer a fairly narrow question:

> **What differences can I document between cartridges when the turntable, tonearm, phono stage, ADC, record, and basic cartridge geometry remain the same?**

Once that baseline exists, the project can expand.

---

# Phono Preamp

## Emotiva XPS-1 Gen2

The phono stage used for the initial Phono Referentia captures is the **Emotiva XPS-1 Gen2**.

For these tests, the signal path is:

```text
Technics SL-QD33
        │
        ▼
Cartridge / Stylus
        │
        ▼
Emotiva XPS-1 Gen2
        │
        ▼
Line-Level Analog Output
```

The XPS-1 Gen2 performs the phono amplification and RIAA equalization before the signal reaches the recording system.

The same phono stage will be retained across the initial cartridge captures so that a change in cartridge does not also involve a change in phono preamplification.

Any changes to phono-stage settings or hardware will be documented with the corresponding capture.

---

# Analog-to-Digital Capture

## Realtek High Definition Audio

The initial recordings are captured through the computer's **Realtek High Definition Audio** line input.

The installed audio device identifies the underlying Realtek hardware as:

```text
HDAUDIO\FUNC_01&VEN_10EC&DEV_0897&SUBSYS_104387FB&REV_1004
```

The Realtek codec device ID is:

```text
DEV_0897
```

The Windows audio endpoint used for the initial captures was configured as follows:

```text
Device:
SWD\MMDEVAPI\{0.0.1.00000000}.{4abb984c-a303-41a3-a486-c46f6bb21dbb}

Driver Name:
audioendpoint.inf

Driver Package ID:
audioendpoint.inf_amd64_271c4d03bad18da8

Class GUID:
{c166523c-fe0c-4a94-a586-f1a80cfbbf3e}

Driver Date:
03/31/2024

Driver Version:
10.0.26100.1

Driver Provider:
Microsoft

Driver Section:
NO_DRV

Driver Rank:
0xFF0000

Matching Device ID:
MMDEVAPI\AudioEndpoints

Outranked Drivers:
c_swdevice.inf:SWD\GenericRaw:00FF3001

Device Updated:
false

Parent Device:
HDAUDIO\FUNC_01&VEN_10EC&DEV_0897&SUBSYS_104387FB&REV_1004\5&99053d1&0&0001
```

This information is being preserved because the ADC is part of the measurement chain.

Future Phono Referentia captures may use a dedicated external ADC or audio interface. If that happens, the new interface will begin a separately documented capture configuration rather than being treated as equivalent to recordings made through this system.

The original Realtek captures will remain useful because the hardware and recording configuration used to create them are known.

---

# Recording Software

## Audacity

The initial Phono Referentia recordings are made using **Audacity**.

Audacity is used to capture the stereo line-level output from the phono stage and create the archival recording files used for subsequent listening and analysis.

Where processing is performed after capture, those changes should be documented separately from the original recording.

The intent is to preserve the original cartridge capture whenever practical rather than replacing it with a processed version.

---

# Export Parameters

The initial archival capture format is:

| Parameter | Setting |
|---|---|
| **Container** | WAV |
| **Sample Rate** | 192,000 Hz |
| **PCM Format** | Signed 24-bit PCM |
| **Channels** | Stereo |

In shorthand:

```text
WAV
192 kHz
24-bit Signed PCM
Stereo
```

The resulting WAV files are the archival cartridge captures for this test configuration.

---

# Initial Signal Chain

The complete initial Phono Referentia recording chain is:

```text
PHONO REFERENTIA REFERENCE DISC I
                │
                ▼
        TECHNICS SL-QD33
                │
                ▼
       T4P / P-MOUNT CARTRIDGE
                │
                ▼
        EMOTIVA XPS-1 GEN2
                │
                ▼
        ANALOG LINE OUTPUT
                │
                ▼
    REALTEK HIGH DEFINITION AUDIO
             LINE INPUT
                │
                ▼
             AUDACITY
                │
                ▼
        192 kHz / 24-bit PCM
                │
                ▼
         ARCHIVAL WAV CAPTURE
```

---

# What Stays Constant

For the initial P-Mount test series, the intention is to keep the following components constant:

- **Reference record:** Phono Referentia Reference Disc I
- **Turntable:** Technics SL-QD33
- **Tonearm:** SL-QD33 factory tonearm
- **Cartridge interface:** T4P / P-Mount
- **Phono preamp:** Emotiva XPS-1 Gen2
- **ADC:** Realtek High Definition Audio
- **Recording software:** Audacity
- **Export format:** WAV
- **Export sample rate:** 192 kHz
- **Export resolution:** Signed 24-bit PCM

The cartridge and/or stylus becomes the primary changing component.

This does not make the experiment immune to every external variable. Stylus condition, record wear, manufacturing tolerances, environmental conditions, and the analog nature of the playback process still exist.

The purpose is not to pretend those variables disappear.

The purpose is to establish a repeatable test platform, document it, and change as little as practical between captures.

---

# Platform Evolution

The SL-QD33/P-Mount system is **Platform 1**.

It establishes the beginning of the Phono Referentia cartridge archive.

Later test platforms can expand the project to conventional 1/2-inch cartridges and other turntables, tonearms, phono stages, and recording hardware.

When that happens, the equipment change itself becomes part of the record.

The early captures will not be rewritten or discarded simply because better recording hardware becomes available later.

They document where the project started.

That is part of Phono Referentia too.

---

# PHONO REFERENTIA

### *Cartridge Testing for Phono Education*

**Initial Test Platform — 2026**

```text
Technics SL-QD33
        ↓
T4P / P-Mount Cartridge
        ↓
Emotiva XPS-1 Gen2
        ↓
Realtek High Definition Audio
        ↓
Audacity
        ↓
192 kHz / 24-bit PCM WAV
```
