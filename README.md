# M445 Extended Range Meter · Meter

Ward-Beck Systems M445, 1995|28. Wiki page: [M445 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.METER.M445-Extended-Range-Meter/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 36 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 43 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 37 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 30 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 9 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 76 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1996 - M445 - 6.jpg](MANUALS/1996%20-%20M445%20-%206.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Audio inputs** | Rear mounted screw-type barrier strip connects audio to the meter when docked: This input is interrupted by the front panel long frame jacks |
| **Audio output** | Output Impedance: 60 ohms or less; balanced |
| **Load impedance** | 5000 ohms or greater; balanced: |
| **Output level** | +4 dBu for 0 VU indication: (+l6 dBu maximum) |
| **Power requirements** | 24 volts DC, 500 mA Provided by &amp; 24 volt ac wall adapter (supplied) |
| **Dimensions** | 19&quot; wide X 3.5&quot; high x 12&quot; deep. (485 mm x 90 mm x 305 mm) e 12.3 lbs (5.6 kg):,.. |
| **Weight** | 4u. 3: 0' ~i T36'. |

## Circuit description

From [1996 - M445 - 14-304-02-001 - SCHEMATIC.wp](MANUALS/1996%20-%20M445%20-%2014-304-02-001%20-%20SCHEMATIC.wp) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

2 Parts List 2-1 to 2-93 Drawings:

Schematic B 14-305-02-001/1 Schematic B 14-305-02-001/2 Component Layout B 14-305-06-001

B SA14-304 LCD/Encoder Board

1 Circuit Description 1-12 Parts List 2-13 Drawings:

Schematic B 14-304-02-001 Component Layout A 14-304-06-001

C SA14-307 Light Bar Board Assembly

1 General 1-12 Circuit Description 3 Parts List 4 Drawings:

Schematic B 14-307-02-001 Component Layout B 14-307-06-001

D SA14-311 Speaker Driver Assembly

1 Circuit Description 1-12 Parts List 2-1 to 2-33 Drawings:

Schematic B 14-311-02-001 Component Layout B 14-311-06-001 A. Transportable Meter

Range: -60 dBu to +30 dBu in 1 dB steps fora reading of 0 VU.

Input Selection: ADC PJ339 type jack on front panel provides direct input, breaking the source on the meters' docking connector.

Source Impedance: 600 or 150 ohms for dBm readings, 600 ohms or less for dBu reading.

Input Impedance: 150,600, or greater than 20,000 ohms.

Attenuator Tracking: ±0.2 dB per step. (non-cumulative).

Meter Ballistics: Comply with ANSI C16.5.

High Pass Filter: -3 dB at 75 Hz.

Frequency Response: ±0.2 dB from 20 Hz to 20 kHz.

Total Harmonic Distortion:

Headset Output: Less than 1%, 20 Hz to 20 kHz.

Measured at any input level and +8 dBu output level.

Typically less than 0.25% with a -2 dBu output level.

Noise: Better than 40 dB below 0 VU reference for all sensitivities.

Output Impedance:

Headset Output: 300 ohms.

Load Impedance:

Headset Output: 600 ohms or greater.

Output Level:

Headset Output: -2 dBu at 0 VU reference, +8 dBu maximum.

Power Source: 4 Panasonic P-60AA re-chargeable NiCd batteries (supplied).

Dimensions: 11.75&quot; wide x 3.5&quot; 8.25&quot; deep (300 mm x 90 mm x 210 mm)

Weight: 4.4 lbs. (2 kg).

B. Rack Mounted Meter Dock

Audio Inputs: Rear mounted screw-type barrier strip connects audio to the meter when docked. This input is interrupted by the front panel long frame jacks.

Audio Output:

Output Impedance: 60 ohms or less, balanced.

Load Impedance: 5000 ohms or greater, balanced.

Output Level: +4 dBu for 0 VU indication. (+16 dBu maximum).

Power Requirements: 24 volts DC, 500 mA.

Provided by a 24 volt ac wall adapter (supplied)

Dimensions: 19&quot; wide x 3.5&quot; high x 12&quot; deep.

(485 mm x 90 mm x 305 mm).

Weight: 12.3 lbs (5.6 kg).

The M445 Extended Range Meter/Monitor combines two instruments in one: A rack-mounted frame and a portable extended range meter, for the measurement and monitoring of stereo analog audio signals.

When the M445 is docked in it's rack mounted frame, the sophisticated battery management circuitry places the battery in &quot;quick-charge&quot; while it assesses the battery condition. The circuitry continuously manages the battery while the meter is docked.

When docked; the M445 activates the meter illumination and speaker amplifiers, enabling confidence monitoring of the measured audio source.

An audio source maybe permanently connected to the rack mounted assembly. This source is connected to the meter directly; whenever there are no plugs present in the M445 front panel long frame jacks. Interruption of the audio connected to the rack chassis allows the M445 to bridge across an audio source on a day today basis, while providing the ability to &quot;patch in&quot; a different audio feed.

A rotary encoder controls the precision attenuator integral to the M445. The liquid crystal display indicates the reference level indicated at the 0 VU position on the meters. The display also indicates whether or not the unit requires charging (by the &quot;lo bat&quot; indicator). If the battery voltage is too low for the M445 to operate accurately; the &quot;low bat&quot; will illuminate, but no digits will be visible in the display. This condition will persist until the meter is docked.

Pushbuttons within the M445 allow you to bridge or match the measured source. When placed in matching mode, either a 600 or 150 Ohm load is presented to the source. Stereo phase integrity can be confirmed by placing the M445 into sum and difference mode. The sum of the left and right input signal is presented on the left-hand meter; and the algebraic difference is demonstrated on the right-hand meter.

The M445 contains a -18 dB per octave high-pass filter. When selected, this filter provides low frequency rejection of hum by -3dB at 75 Hz. The 1/4&quot; standard TRS receptacle on the front panel is capable of driving a 600 ohm headset to a comfortable listening level. Additional monitoring of the measured audio maybe done through the rear mounted terminal strip. This output maybe used to drive an additional audio power amplifier.

The meter docking assembly is powered by an ac adapter, which furnishes 24 volts DC to the dock. This power is distributed to the speaker amplifiers, and to the meter (when docked). The dock; through it's rear-mounted barrier strip and docking connector, distributes all of the power and audio signals through the meter system.

Two security features are standard. A front panel lock prevents the meter from being extracted when engaged. A second locking screw, accessible at the rear of the docking frame, provides a more permanent security lock. Refer to Front Panel drawing B 445-04-002

1) Left Channel VU Meter

Meter which indicates the volume units (in dBu) of the input audio signal. A sinusoidal waveform will indicate '0' on this meter when it's amplitude matches the sensitivity indicated on the liquid crystal display. Under normal operating conditions, this meter indicates the signal level of the left channel.

When &quot;sum and difference&quot; mode is selected by mode switch (3), this meter will display the algebraic sum of the left and right channel audio signal.

2) Right Channel VU Meter

Operates as (1), except in normal operation right channel audio is displayed. In &quot;sum and difference&quot; mode, this meter indicates the difference between the left and right channel audio. The difference indication is useful for verifying stereo phase coherence.

3) Mode Switch

When depressed, places the M445 in &quot;sum an difference&quot; mode; otherwise discrete left and right signal levels are displayed on their associated meters.

4) HP Filter Switch

Normally, the M445 measures the audio signal across the full audible band. When assigned, the high pass filter attenuates frequencies below it's 75 Hz corner at a rate of -18 dB per octave.

5) Termination Switch

When released, the termination switch allows the meter to present abridging load to the audio source. Once depressed, the impedance selected by the Impedance Selector (Z), is connected across the audio input terminals.

6) Impedance Selector

This switch terminates the input source with 600 ohms (relaxed) or 150 ohms (engaged): provided the termination switch has been actuated.

7) Monitor Receptacle

A 1/4&quot; standard TRS (tip-ring-sleeve) stereo receptacle for monitoring the metered audio signal. This jack provides a high quality, full bandwidth monitor output. Good quality, high impedance (&gt;600 ohms) headphones will provide optimum audio fidelity.

8) Left and Right Front Panel Inputs

Telephone style, balanced, long frame 1/4&quot; jacks, which have the rear chassis input &quot;normalled&quot; through. When a plug (ADC PJ-2 or equivalent) is inserted, the rear chassis input audio is interrupted, allowing any audio present at the front panel to be measured and/or monitored.

9) Power Switch

Powers the meter's active circuitry, exclusive of the battery management system. When docked; engaging the power switch also activates the meter illumination and the power amplifier which drives the speakers.

10) Liquid Crystal Sensitivity Display

Controlled by (11), this display indicates the audio reference level in dBu. When &quot;lo batt&quot; is displayed in the display, the batteries require charging; which is accomplished whenever the meter is &quot;docked&quot;. Should the batteries deplete to a point where accurate measurements are no longer possible, the audio reference display will blank: However, the &quot;lo batt&quot; will still be visible.

11) Sensitivity Adjustment Control

A rotary encoder which sets the reference level fora '0' indication on the meters of the M445.12) Security Latch

When engaged, this latch prevents the M445 from being extracted.

13) Speaker Level Control

This rotary control adjusts the level of the audio in the monitor speakers.

14) Right Channel Speaker

In &quot;normal&quot; mode, right channel audio maybe monitored via this speaker. In &quot;sum and difference&quot; mode, the difference signal will be present through this speaker.

15) Left Channel Speaker

Discrete left channel audio is monitored in this speaker in &quot;normal&quot; mode, while in &quot;sum and difference&quot;, this speaker contains the sum (L+R) signal. Rack Mounted Dock

Refer to Rear Panel drawing B 445-04-003

16) Power Input Connector

This connector mates with the ring-lock cable plug from the external power supply. Twenty-four volts (+24V) DC at 500 mA is required by the M445.

17) Power Fuse

A 1/2 amp, slow-blow fuse to protect the entire M445 from a fault condition. 18) Rear Chassis Connector

Audio inputs (&quot;normalled&quot; through the front panel jacks), and audio monitor outputs maybe connected to external equipment on this barrier strip.

19) Rear Chassis Security Screw

A captive screw which; when engaged, prevents the meter from being withdrawn from the rack mount frame regardless of the position of the front panel lock.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOTMzY1R5azQzSEU/view?resourcekey=0-QaRDBmvyhTbsP3pgZVAdsA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOTMzY1R5azQzSEU&resourcekey=0-QaRDBmvyhTbsP3pgZVAdsA" width="240" alt="1996 - M445 - $_57-1.jpg"></a><br><sub>1996|29 · $_57-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUW1pQWpyQnBZQ2c/view?resourcekey=0-qvgTKQZU_Qr-zzwz53Bruw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUW1pQWpyQnBZQ2c&resourcekey=0-qvgTKQZU_Qr-zzwz53Bruw" width="240" alt="1996 - M445 - $_57-2.jpg"></a><br><sub>1996|29 · $_57-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHpyekNYX2lKWk0/view?resourcekey=0-U2LBqhpnT02wNc1iG6z-SQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHpyekNYX2lKWk0&resourcekey=0-U2LBqhpnT02wNc1iG6z-SQ" width="240" alt="1996 - M445 - $_57-3.jpg"></a><br><sub>1996|29 · $_57-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdFNsMWYxdUlUZVU/view?resourcekey=0-InGiH__idXNnsjFELBEvuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdFNsMWYxdUlUZVU&resourcekey=0-InGiH__idXNnsjFELBEvuQ" width="240" alt="1996 - M445 - $_57-4.jpg"></a><br><sub>1996|29 · $_57-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcXRBbk93NU5xWnc/view?resourcekey=0-i7qD6ENpvx1Z9f8p1m5Ajg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcXRBbk93NU5xWnc&resourcekey=0-i7qD6ENpvx1Z9f8p1m5Ajg" width="240" alt="1996 - M445 - $_57-5.jpg"></a><br><sub>1996|29 · $_57-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUxIbExhMzhQUEE/view?resourcekey=0-CYVTUvTsNtdz97ranmoWag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUxIbExhMzhQUEE&resourcekey=0-CYVTUvTsNtdz97ranmoWag" width="240" alt="1996 - M445 - $_57-6.jpg"></a><br><sub>1996|29 · $_57-6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUFBbThEZjkxUEk/view?resourcekey=0-aPMSEqGsJPCAG-GCYmc2Ig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUFBbThEZjkxUEk&resourcekey=0-aPMSEqGsJPCAG-GCYmc2Ig" width="240" alt="1996 - M445 - Archived - M445 - EXTENDED RANGE METER - MONITOR 003.jpg"></a><br><sub>1996|29 · Archived - M445 - EXTENDED RANGE METER - MONITOR 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2w3MWdzRVlYZWs/view?resourcekey=0-WwuYnK8ka8nJA5mDsIx3hQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2w3MWdzRVlYZWs&resourcekey=0-WwuYnK8ka8nJA5mDsIx3hQ" width="240" alt="1996 - M445 - BACK (2).jpg"></a><br><sub>1996|29 · BACK (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa21zMTdBS1hkRjA/view?resourcekey=0-KnQEzLtRprx1FIzeiTfNgA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa21zMTdBS1hkRjA&resourcekey=0-KnQEzLtRprx1FIzeiTfNgA" width="240" alt="1996 - M445 - FRONT (2).jpg"></a><br><sub>1996|29 · FRONT (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY2xGQTFwVjNZbW8/view?resourcekey=0-WA2MmNFMtXJRYqiqZGjzWw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY2xGQTFwVjNZbW8&resourcekey=0-WA2MmNFMtXJRYqiqZGjzWw" width="240" alt="1996 - M445 - FRONT (3).jpg"></a><br><sub>1996|29 · FRONT (3)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVJRdXQ2MWM3ajA/view?resourcekey=0-_EsSa7bYTfmwY5bqwPJDNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVJRdXQ2MWM3ajA&resourcekey=0-_EsSa7bYTfmwY5bqwPJDNg" width="240" alt="1996 - M445 - VU meter 163.jpg"></a><br><sub>1996|29 · VU meter 163</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVc1UlpVRjlfMnM/view?resourcekey=0-_4e_rf6tf726q_X7GaRMmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVc1UlpVRjlfMnM&resourcekey=0-_4e_rf6tf726q_X7GaRMmw" width="240" alt="1996 - M445 - VU meter 164.jpg"></a><br><sub>1996|29 · VU meter 164</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWFRM24zZTdJcFE/view?resourcekey=0-oB3tQP3Kl3x2jcJqEe_XHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWFRM24zZTdJcFE&resourcekey=0-oB3tQP3Kl3x2jcJqEe_XHQ" width="240" alt="1996 - M445 - VU meter 165.jpg"></a><br><sub>1996|29 · VU meter 165</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcTFlWWZld1liZDA/view?resourcekey=0-lvvShEdjg8c9tifCQivJeQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcTFlWWZld1liZDA&resourcekey=0-lvvShEdjg8c9tifCQivJeQ" width="240" alt="1996 - M445 - VU meter 166.jpg"></a><br><sub>1996|29 · VU meter 166</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMnNoZFdVRjg1ZjQ/view?resourcekey=0-81INL-qD6bbB1BgSCjCXNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMnNoZFdVRjg1ZjQ&resourcekey=0-81INL-qD6bbB1BgSCjCXNg" width="240" alt="1996 - M445 - VU meter 167.jpg"></a><br><sub>1996|29 · VU meter 167</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0JXOWM2MWJNTzA/view?resourcekey=0-7oejS-vb4d3RQcksJd95-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0JXOWM2MWJNTzA&resourcekey=0-7oejS-vb4d3RQcksJd95-w" width="240" alt="1996 - M445 - VU meter 169.jpg"></a><br><sub>1996|29 · VU meter 169</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSFBFVjVYaE1TUEk/view?resourcekey=0-5gXapB_IQHdhBzA7vbqrbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSFBFVjVYaE1TUEk&resourcekey=0-5gXapB_IQHdhBzA7vbqrbw" width="240" alt="1996 - M445 - VU meter 170.jpg"></a><br><sub>1996|29 · VU meter 170</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWVvTWVDM0dFY1E/view?resourcekey=0-4ZXIZRA1NPtZcdVH0ZJLfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWVvTWVDM0dFY1E&resourcekey=0-4ZXIZRA1NPtZcdVH0ZJLfA" width="240" alt="1996 - M445 - VU meter 172.jpg"></a><br><sub>1996|29 · VU meter 172</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ0tYMGd2TlQ4LTQ/view?resourcekey=0-gBOwbHxY7gvvwcobNHUWbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ0tYMGd2TlQ4LTQ&resourcekey=0-gBOwbHxY7gvvwcobNHUWbw" width="240" alt="1996 - M445 - VU meter 173.jpg"></a><br><sub>1996|29 · VU meter 173</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlF1RjhOclA5d28/view?resourcekey=0-9SLpfpyfQ5nrxWNrem9IuA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlF1RjhOclA5d28&resourcekey=0-9SLpfpyfQ5nrxWNrem9IuA" width="240" alt="1996 - M445 - VU meter 174.jpg"></a><br><sub>1996|29 · VU meter 174</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3EyX1dUQ3JIRkU/view?resourcekey=0-ULDemC8eudMX5zcmM5r_3Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3EyX1dUQ3JIRkU&resourcekey=0-ULDemC8eudMX5zcmM5r_3Q" width="240" alt="1996 - M445 - VU meter 175.jpg"></a><br><sub>1996|29 · VU meter 175</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM0dkbUxFVkJoQVE/view?resourcekey=0-lCUXJbOmVvbSkkBDy57lAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM0dkbUxFVkJoQVE&resourcekey=0-lCUXJbOmVvbSkkBDy57lAw" width="240" alt="1996 - M445 - VU meter 176.jpg"></a><br><sub>1996|29 · VU meter 176</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekJ1R1kxencxaFk/view?resourcekey=0-VGjLCgmkvUwyISADmL9ySQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekJ1R1kxencxaFk&resourcekey=0-VGjLCgmkvUwyISADmL9ySQ" width="240" alt="1996 - M445 - VU meter 177.jpg"></a><br><sub>1996|29 · VU meter 177</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGR1YnA2STBTalE/view?resourcekey=0-86H8J6wGkp7YgmwJdmKTbA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGR1YnA2STBTalE&resourcekey=0-86H8J6wGkp7YgmwJdmKTbA" width="240" alt="1996 - M445 - VU meter 178.jpg"></a><br><sub>1996|29 · VU meter 178</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLXFyZlp2QWhlQ00/view?resourcekey=0-AoiB2tFWZnF3lYKGiVZQew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLXFyZlp2QWhlQ00&resourcekey=0-AoiB2tFWZnF3lYKGiVZQew" width="240" alt="1996 - M445 - VU meter 182.jpg"></a><br><sub>1996|29 · VU meter 182</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFpOaWZhTTM2MlU/view?resourcekey=0-Yehvt7whLMYdG-1qO08hRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFpOaWZhTTM2MlU&resourcekey=0-Yehvt7whLMYdG-1qO08hRQ" width="240" alt="1996 - M445 - VU meter 186.jpg"></a><br><sub>1996|29 · VU meter 186</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbnY5UzBCSFFrTjQ/view?resourcekey=0-5AEH1jbiqQJrEkC3PJ2GNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbnY5UzBCSFFrTjQ&resourcekey=0-5AEH1jbiqQJrEkC3PJ2GNQ" width="240" alt="1996 - M445 - VU meter 187.jpg"></a><br><sub>1996|29 · VU meter 187</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaVlGZG1HVkRoVzg/view?resourcekey=0-YXMZaamo9AATpylgxA8OzA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaVlGZG1HVkRoVzg&resourcekey=0-YXMZaamo9AATpylgxA8OzA" width="240" alt="1996 - M445 - VU meter 188.jpg"></a><br><sub>1996|29 · VU meter 188</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY19nSkJzM0RSLTA/view?resourcekey=0-elNaapi-1R6_FNDRwvSZgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY19nSkJzM0RSLTA&resourcekey=0-elNaapi-1R6_FNDRwvSZgg" width="240" alt="1996 - M445 - VU meter 189.jpg"></a><br><sub>1996|29 · VU meter 189</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNkJQTnBoSFpnS1E/view?resourcekey=0-V6so__wLxDZPtJTfU32x0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNkJQTnBoSFpnS1E&resourcekey=0-V6so__wLxDZPtJTfU32x0Q" width="240" alt="1996 - M445 - VU meter 190.jpg"></a><br><sub>1996|29 · VU meter 190</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU05RR3VoVE9qbVE/view?resourcekey=0-saFGk2opbVxe4MrrA2Fmjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU05RR3VoVE9qbVE&resourcekey=0-saFGk2opbVxe4MrrA2Fmjw" width="240" alt="1996 - M445 - B 445-04-001 - M445 EXTENDED RANGE METER-MONITOR - OUTLINE.jpg"></a><br><sub>1996|29 · B 445-04-001 - M445 EXTENDED RANGE METER-MONITOR - OUTLINE · <a href="MECHANICAL/1996%20-%20M445%20-%20B%20445-04-001%20-%20M445%20EXTENDED%20RANGE%20METER-MONITOR%20-%20OUTLINE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcHNJSE1ZcTVydkU/view?resourcekey=0-Xf2bXcclXLiOjuFtlP5c6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcHNJSE1ZcTVydkU&resourcekey=0-Xf2bXcclXLiOjuFtlP5c6w" width="240" alt="1996 - M445 - B 445-04-002 - M445 EXTENDED RANGE METER-MONITOR - FRONT PANEL LAYOUT.jpg"></a><br><sub>1996|29 · B 445-04-002 - M445 EXTENDED RANGE METER-MONITOR - FRONT PANEL LAYOUT · <a href="MECHANICAL/1996%20-%20M445%20-%20B%20445-04-002%20-%20M445%20EXTENDED%20RANGE%20METER-MONITOR%20-%20FRONT%20PANEL%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOUhTTHFEVHFIWWM/view?resourcekey=0-oe_Ho72PDAY1xGduMQoH4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOUhTTHFEVHFIWWM&resourcekey=0-oe_Ho72PDAY1xGduMQoH4A" width="240" alt="1996 - M445 - B 445-04-003 - M445 EXTENDED RANGE METER-MONITOR - REAR PANEL LAYOUT.jpg"></a><br><sub>1996|29 · B 445-04-003 - M445 EXTENDED RANGE METER-MONITOR - REAR PANEL LAYOUT · <a href="MECHANICAL/1996%20-%20M445%20-%20B%20445-04-003%20-%20M445%20EXTENDED%20RANGE%20METER-MONITOR%20-%20REAR%20PANEL%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1Fxfr61KKWonSLh86Qe6Q2WXm1boXvqHP/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1Fxfr61KKWonSLh86Qe6Q2WXm1boXvqHP" width="240" alt="19xx - M445 - DOC - 445-03-007 - NQTES REMOVE ALL BURRS AND SHARP EDGES.jpg"></a><br><sub>19xx - M445 - DOC - 445-03-007 - NQTES REMOVE ALL BURRS AND SHARP EDGES · <a href="MECHANICAL/19xx%20-%20M445%20-%20DOC%20-%20445-03-007%20-%20NQTES%20REMOVE%20ALL%20BURRS%20AND%20SHARP%20EDGES%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1YIUnXsp5vS_2jt56C6pElWH9bALMfktf/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1YIUnXsp5vS_2jt56C6pElWH9bALMfktf" width="240" alt="19xx - M445 - DOC - 445-03-016 - PAINT EXTRA FINE TEXTURED BLACK TEXCOTE.jpg"></a><br><sub>19xx - M445 - DOC - 445-03-016 - PAINT EXTRA FINE TEXTURED BLACK TEXCOTE · <a href="MECHANICAL/19xx%20-%20M445%20-%20DOC%20-%20445-03-016%20-%20PAINT%20EXTRA%20FINE%20TEXTURED%20BLACK%20TEXCOTE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1nHifTvOAWyreBADshTWDy9E_jFqgqACe/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1nHifTvOAWyreBADshTWDy9E_jFqgqACe" width="240" alt="19xx - M445 - DOC - 445-03-026 - REMOVE ALL BURRS AND SHARP EDGES TOLERANCES.jpg"></a><br><sub>19xx - M445 - DOC - 445-03-026 - REMOVE ALL BURRS AND SHARP EDGES TOLERANCES · <a href="MECHANICAL/19xx%20-%20M445%20-%20DOC%20-%20445-03-026%20-%20REMOVE%20ALL%20BURRS%20AND%20SHARP%20EDGES%20TOLERANCES%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1LRXvBOKQ60yQLWiFxY6YYXRJpYYd7m5t/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1LRXvBOKQ60yQLWiFxY6YYXRJpYYd7m5t" width="240" alt="19xx - M445 - DOC - 445-03-028 - NQTES REMOVE ALL BURRS AND SHARP EDGES TOLERANCES.jpg"></a><br><sub>19xx - M445 - DOC - 445-03-028 - NQTES REMOVE ALL BURRS AND SHARP EDGES TOLERANCES · <a href="MECHANICAL/19xx%20-%20M445%20-%20DOC%20-%20445-03-028%20-%20NQTES%20REMOVE%20ALL%20BURRS%20AND%20SHARP%20EDGES%20TOLERANCES%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M445.stl`](MECHANICAL/M445.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M445)

- **Size:** 485 × 90 mm panel, 305 mm deep, 3.2 mm plate (TECHNICAL DATA: 19" wide X 3.5" high x 12" deep. (485 mm x 90 mm x 305 mm) e 12.3 lbs (5.6 kg):,..)
- **From the drawing:** 3 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M445 - front panel.svg`)
- the drawn panel is 3.40 wide to high, the size 5.39: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M445.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN2NWVC1oZEZ1M28/view?resourcekey=0-dBlOz2WjR6KGeyh5dESJLw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN2NWVC1oZEZ1M28&resourcekey=0-dBlOz2WjR6KGeyh5dESJLw" width="240" alt="1996 - M445 - B 445-01-001 - M445 EXTENDED RANGE METER-MONITOR - FUNCTIONAL.jpg"></a><br><sub>1996|29 · B 445-01-001 - M445 EXTENDED RANGE METER-MONITOR - FUNCTIONAL · <a href="SCHEMATICS/1996%20-%20M445%20-%20B%20445-01-001%20-%20M445%20EXTENDED%20RANGE%20METER-MONITOR%20-%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbE00LUhFVlZiaU0/view?resourcekey=0-ZAUOsO60GbSBSncepygFTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbE00LUhFVlZiaU0&resourcekey=0-ZAUOsO60GbSBSncepygFTQ" width="240" alt="1996 - M445 - B 445-02-001 - M445 RACK MOUNT FRAME - SCHEMATIC.jpg"></a><br><sub>1996|29 · B 445-02-001 - M445 RACK MOUNT FRAME - SCHEMATIC · <a href="SCHEMATICS/1996%20-%20M445%20-%20B%20445-02-001%20-%20M445%20RACK%20MOUNT%20FRAME%20-%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY00zQkJRTl9pb0k/view?resourcekey=0-nlNAkgbF57ogM8FTAgGXxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY00zQkJRTl9pb0k&resourcekey=0-nlNAkgbF57ogM8FTAgGXxQ" width="240" alt="1996 - M445 - B 445-02-002 - M445 EXTENDED RANGE METER - SCHEMATIC.jpg"></a><br><sub>1996|29 · B 445-02-002 - M445 EXTENDED RANGE METER - SCHEMATIC · <a href="SCHEMATICS/1996%20-%20M445%20-%20B%20445-02-002%20-%20M445%20EXTENDED%20RANGE%20METER%20-%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblZLcUJzdXRyUnc/view?resourcekey=0-GCwrfwAqqhvmoo0XrINd8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblZLcUJzdXRyUnc&resourcekey=0-GCwrfwAqqhvmoo0XrINd8w" width="240" alt="1996 - M445 - $_57-7.jpg"></a><br><sub>1996|29 · $_57-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTBQUGthTWVoazA/view?resourcekey=0-I-pgKIEs5ydzk-iNm3hTIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTBQUGthTWVoazA&resourcekey=0-I-pgKIEs5ydzk-iNm3hTIg" width="240" alt="1996 - M445 - $_57.jpg"></a><br><sub>1996|29 · $_57</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVJFQ2dxUGhGajQ/view?resourcekey=0-PW-B3ZY_D4AZpx3QrFzzAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVJFQ2dxUGhGajQ&resourcekey=0-PW-B3ZY_D4AZpx3QrFzzAA" width="240" alt="1996 - M445 - 1.jpg"></a><br><sub>1996|29 · 1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNzQweGc3NkktaEU/view?resourcekey=0-UxKZj8In3Y8VrHjFxWqI3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNzQweGc3NkktaEU&resourcekey=0-UxKZj8In3Y8VrHjFxWqI3w" width="240" alt="1996 - M445 - 10.jpg"></a><br><sub>1996|29 · 10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMERGTlNFTU04UlU/view?resourcekey=0-RLt5mVz0EPreb-x8WNRcBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMERGTlNFTU04UlU&resourcekey=0-RLt5mVz0EPreb-x8WNRcBA" width="240" alt="1996 - M445 - 11.jpg"></a><br><sub>1996|29 · 11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVVjZFFfa1NvOW8/view?resourcekey=0-gRrTDsDpOtPuNYDu4oBsdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVVjZFFfa1NvOW8&resourcekey=0-gRrTDsDpOtPuNYDu4oBsdQ" width="240" alt="1996 - M445 - 18.jpg"></a><br><sub>1996|29 · 18</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdzNHRFVlVHphYWc/view?resourcekey=0-IbDq_ELn40KXpYnVwi5J8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdzNHRFVlVHphYWc&resourcekey=0-IbDq_ELn40KXpYnVwi5J8Q" width="240" alt="1996 - M445 - 19.jpg"></a><br><sub>1996|29 · 19</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXE1SnR6MkZ1Wmc/view?resourcekey=0-q3PDh3d1N3snbTpwU0n_rA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXE1SnR6MkZ1Wmc&resourcekey=0-q3PDh3d1N3snbTpwU0n_rA" width="240" alt="1996 - M445 - 2.jpg"></a><br><sub>1996|29 · 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1JZcExiZ1NUNXM/view?resourcekey=0-8KI0ei6Mso-3J278Mrwv-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1JZcExiZ1NUNXM&resourcekey=0-8KI0ei6Mso-3J278Mrwv-w" width="240" alt="1996 - M445 - 22.jpg"></a><br><sub>1996|29 · 22</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMWtNWE9yM3VZSWM/view?resourcekey=0-GMiemkSvlSlWqSr6lzRZvA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMWtNWE9yM3VZSWM&resourcekey=0-GMiemkSvlSlWqSr6lzRZvA" width="240" alt="1996 - M445 - 24.jpg"></a><br><sub>1996|29 · 24</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV01fdTlMc2Y3Tm8/view?resourcekey=0-VIHL-x_ZsGaLKZLBU5BnGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV01fdTlMc2Y3Tm8&resourcekey=0-VIHL-x_ZsGaLKZLBU5BnGw" width="240" alt="1996 - M445 - 26.jpg"></a><br><sub>1996|29 · 26</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVkzTTY0aWpYLWM/view?resourcekey=0-XHGBlKPrYIjqiaUED8q2Bw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVkzTTY0aWpYLWM&resourcekey=0-XHGBlKPrYIjqiaUED8q2Bw" width="240" alt="1996 - M445 - 3.jpg"></a><br><sub>1996|29 · 3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV1NqeGlTU1BjYnM/view?resourcekey=0-boVPGjEepueZ-iE8Bl9Adg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV1NqeGlTU1BjYnM&resourcekey=0-boVPGjEepueZ-iE8Bl9Adg" width="240" alt="1996 - M445 - 4.jpg"></a><br><sub>1996|29 · 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYWdESm9XOTNybmc/view?resourcekey=0-sEQwpRkiBItHgw1biXtJmg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYWdESm9XOTNybmc&resourcekey=0-sEQwpRkiBItHgw1biXtJmg" width="240" alt="1996 - M445 - 5.jpg"></a><br><sub>1996|29 · 5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVhvRWZseGVlNjQ/view?resourcekey=0-UI-s1ivcv1FmgV7ZMTo_dA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVhvRWZseGVlNjQ&resourcekey=0-UI-s1ivcv1FmgV7ZMTo_dA" width="240" alt="1996 - M445 - 6.jpg"></a><br><sub>1996|29 · 6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVE0tXy1qNWRMZlE/view?resourcekey=0-aSpby5qCip2Sz8HlkD2G_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVE0tXy1qNWRMZlE&resourcekey=0-aSpby5qCip2Sz8HlkD2G_Q" width="240" alt="1996 - M445 - 7.jpg"></a><br><sub>1996|29 · 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2NtZXhLWG1HMTg/view?resourcekey=0-UAVBIbLZQ_4wnompEohEZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2NtZXhLWG1HMTg&resourcekey=0-UAVBIbLZQ_4wnompEohEZQ" width="240" alt="1996 - M445 - 8.jpg"></a><br><sub>1996|29 · 8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRXpSTDlPOVNGVHc/view?resourcekey=0-ESJ2-jgTNy8sQt1LN9QKfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRXpSTDlPOVNGVHc&resourcekey=0-ESJ2-jgTNy8sQt1LN9QKfA" width="240" alt="1996 - M445 - 9.jpg"></a><br><sub>1996|29 · 9</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUxfSnlyN0JSM3M/view?resourcekey=0-_iDzBzBJzmTm68GUdLuTqg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUxfSnlyN0JSM3M&resourcekey=0-_iDzBzBJzmTm68GUdLuTqg" width="240" alt="1996 - M445 - Archived - M445 - EXTENDED RANGE METER - MONITOR 001.jpg"></a><br><sub>1996|29 · Archived - M445 - EXTENDED RANGE METER - MONITOR 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeE9STUVYU2NVMHc/view?resourcekey=0-olWM3J_wXNYBx8qEZiR0AA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeE9STUVYU2NVMHc&resourcekey=0-olWM3J_wXNYBx8qEZiR0AA" width="240" alt="1996 - M445 - Archived - M445 - EXTENDED RANGE METER - MONITOR 002.jpg"></a><br><sub>1996|29 · Archived - M445 - EXTENDED RANGE METER - MONITOR 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd3dWZENSY29JVkk/view?resourcekey=0-Z5F66mOBF96kp1r00joruA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd3dWZENSY29JVkk&resourcekey=0-Z5F66mOBF96kp1r00joruA" width="240" alt="1996 - M445 - EXTENDED RANGE METER - MONITOR 001.jpg"></a><br><sub>1996|29 · EXTENDED RANGE METER - MONITOR 001</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeU1DUUFkV0pxTUE/view?resourcekey=0-z3gQH1Y-gc5JqKxoZie87w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeU1DUUFkV0pxTUE&resourcekey=0-z3gQH1Y-gc5JqKxoZie87w" width="240" alt="1996 - M445 - EXTENDED RANGE METER - MONITOR 002.jpg"></a><br><sub>1996|29 · EXTENDED RANGE METER - MONITOR 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZV9NTVJSU3ZGbEU/view?resourcekey=0-BD0UuZEMjeZs887qN329TA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZV9NTVJSU3ZGbEU&resourcekey=0-BD0UuZEMjeZs887qN329TA" width="240" alt="1996 - M445 - EXTENDED RANGE METER - MONITOR 003.jpg"></a><br><sub>1996|29 · EXTENDED RANGE METER - MONITOR 003</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1996 - M445 - B 445-01-001 - M445 EXTENDED RANGE METER-MONITOR - FUNCTIONAL.kicad_sch](KICAD/1996%20-%20M445%20-%20B%20445-01-001%20-%20M445%20EXTENDED%20RANGE%20METER-MONITOR%20-%20FUNCTIONAL.kicad_sch)
- [1996 - M445 - B 445-02-001 - M445 RACK MOUNT FRAME - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20B%20445-02-001%20-%20M445%20RACK%20MOUNT%20FRAME%20-%20SCHEMATIC.kicad_sch)
- [1996 - M445 - B 445-02-002 - M445 EXTENDED RANGE METER - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20B%20445-02-002%20-%20M445%20EXTENDED%20RANGE%20METER%20-%20SCHEMATIC.kicad_sch)
- [1996 - M445 - [DWG 14-304-02-001] - SA14-304 LCD-ENCODER BOARD - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20%5BDWG%2014-304-02-001%5D%20-%20SA14-304%20LCD-ENCODER%20BOARD%20-%20SCHEMATIC.kicad_sch)
- [1996 - M445 - [DWG 14-305-02-001]-1 - SA14-305 STEREO EXTENDED RANGE METER - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20%5BDWG%2014-305-02-001%5D-1%20-%20SA14-305%20STEREO%20EXTENDED%20RANGE%20METER%20-%20SCHEMATIC.kicad_sch)
- [1996 - M445 - [DWG 14-305-02-001]-2 - SA14-305 STEREO EXTENDED RANGE METER - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20%5BDWG%2014-305-02-001%5D-2%20-%20SA14-305%20STEREO%20EXTENDED%20RANGE%20METER%20-%20SCHEMATIC.kicad_sch)
- [1996 - M445 - [DWG 14-307-02-001] - SA14-307 EXTENDED RANGE METER LIGHT BAR - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20%5BDWG%2014-307-02-001%5D%20-%20SA14-307%20EXTENDED%20RANGE%20METER%20LIGHT%20BAR%20-%20SCHEMATIC.kicad_sch)
- [1996 - M445 - [DWG 14-311-02-001] - SA14-311 SPEAKER DRIVER - SCHEMATIC.kicad_sch](KICAD/1996%20-%20M445%20-%20%5BDWG%2014-311-02-001%5D%20-%20SA14-311%20SPEAKER%20DRIVER%20-%20SCHEMATIC.kicad_sch)
- [M445.kicad_sym](KICAD/M445.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
