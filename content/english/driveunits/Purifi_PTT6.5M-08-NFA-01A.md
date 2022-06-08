---
title: "Purifi Audio PTT6.5M-08-NFA-01A 6.5 Inch MidWoofer Review"
date: 2022-06-04
draft: false
image: "https://purifi-audio.com/wp-content/uploads/2021/06/PTT6.5-NFx-front-perspective-trans-440x440-1.png"
description : "Purifi Audio PTT6.5M-08-NFA-01A 6.5 Inch MidWoofer Review"
Tags: ["Purifi", "PTT6.5M-08-NFA-01A", "midbass", "midrange", "Dyn", "woofer", "Review", "Klippel", "Speaker"]
---

## Foreword / YouTube Video Review
This driver was loaned to me by Purifi for review.  I was not paid for the review.

The review on this website is a brief overview and summary of the objective performance of this speaker.  It is not intended to be a deep dive.  Moreso, this is information for those who prefer "just the facts" and prefer to have the data without the filler.  The video below has more discussion.

<iframe width="560" height="315" src="https://www.youtube.com/embed/93ilxMatBOA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<br>
<br>


# Information

Specs from the manufacturer can be found [here](https://purifi-audio.com/ptt6-5m04-nfa-01/).


Retail price is about $385 USD/each from [Purifi](https://purifi-audio.com/vare/ptt6-5m0z-nfa-01/).


<br clear="all" />

<br>


# Test Results
<details>
<summary>
Foreword: Subjective Analysis vs Objective Data of Drive Units (click here)
</summary></br>
While I would love to be able to confidently do so, I do not provide subjective analysis of raw drive units.  Realistically, there is no easy way or meaningful way to do so.  Drive units are parts of a whole.  In order to test, subjectively, you would want to integrate it into a system and find what works best when mated to another driver (like a midwoofer to a tweeter, a midrange to a midwoofer, etc.).  And to give it a fair shake it must be optimized in that inegration which would be a very arduous task to perform for every drive unit I review.  It makes no sense to subjectively critique a single drive unit on its own because it may be used in a different configuration than someone else.  One person may cross it with an LR2 HPF and LR4 LPF where another may use it in a completely different bandpass with completely different crossover and slopes. And if I were to try to create a speaker from it for the point of subjective analysis I am left with the same issue.  The best implementation for a 6.5-inch midwoofer is different than it is for an 8-inch midwoofer.  The data tells the story of performance on an apples-to-apples basis far better than someone's subjective imagination can.
<br clear="all" />

<br>

For all the reasons listed above: What I provide here is objective-heavy analysis.  However, I provide my own subjective experience and provide insight into what I believe might be positive or negative performance characteristics based on the objective data.
</details>

<br>
<br>

## Small Signal Testing (Thiele-Small Results)

Using [Klippel's Distortion Analyzer 2](https://www.klippel.de/products/rd-system/analyzer-hardware/da2-klippel-distortion-analyzer.html), [Linear Lumped Parameter Measurement Module](https://www.klippel.de/nc/en/products/rd-system/modules/lpm-linear-parameter-measurement.html?sword_list%5B0%5D=lpm), [Pro Driver Stand](https://www.klippel.de/nc/en/products/rd-system/accessories/overview-accessories/pro-driver-stand.html?sword_list%5B0%5D=stand) and provided [Panasonic ANR12821 Laser](https://panasonicsensors.com/anr12821) along with [Klippel's Training 1 - Linear Lumped Parameter Measurement tutorial](https://www.youtube.com/watch?v=uhJd8-Z8cgc&t=313s), I measured this drive unit's impedance and small-signal parameters.  Below are the results.

| Electrical Parameters |        |      |                                                                                |
|-----------------------|--------|------|--------------------------------------------------------------------------------|
| Re                    | 6.49   | Ohm  | electrical voice coil resistance at DC                                         |
| Le                    | 0.188  | mH   | frequency independent part of voice coil inductance                            |
| L2                    | 0.473  | mH   | para-inductance of voice coil                                                  |
| R2                    | 2.54   | Ohm  | electrical resistance due to eddy current losses                               |
| Cmes                  | 178.65 | µF   | electrical capacitance representing moving mass                                |
| Lces                  | 36.60  | mH   | electrical inductance representing driver compliance                           |
| Res                   | 77.86  | Ohm  | resistance due to mechanical losses                                            |
| fs                    | 62.2   | Hz   | driver resonance frequency                                                     |
|                       |        |      |                                                                                |
| Mechanical Parameters |        |      |                                                                                |
| (using laser)         |        |      |                                                                                |
| Mms                   | 16.995 | g    | mechanical mass of driver diaphragm assembly including air load and voice coil |
| Mmd (Sd)              | 15.262 | g    | mechanical mass of voice coil and diaphragm without air load                   |
| Rms                   | 1.222  | kg/s | mechanical resistance of  total-driver losses                                  |
| Cms                   | 0.385  | mm/N | mechanical compliance of driver suspension                                     |
| Kms                   | 2.60   | N/mm | mechanical stiffness of driver suspension                                      |
| Bl                    | 9.754  | N/A  | force factor (Bl product)                                                      |
| Lambda s              | 0.063  |      | suspension creep factor                                                        |
|                       |        |      |                                                                                |
| Loss factors          |        |      |                                                                                |
| Qtp                   | 0.419  |      | total Q-factor considering all losses                                          |
| Qms                   | 5.439  |      | mechanical Q-factor of driver in free air considering Rms only                 |
| Qes                   | 0.453  |      | electrical Q-factor of driver in free air considering Re only                  |
| Qts                   | 0.418  |      | total Q-factor considering Re and Rms only                                     |
|                       |        |      |                                                                                |
| Other Parameters      |        |      |                                                                                |
| Vas                   | 9.6323 | l    | equivalent air volume of suspension                                            |
| n0                    | 0.492  | %    | reference efficiency (2 pi-radiation using Re)                                 |
| Lm                    | 89.12  | dB   | characteristic sound pressure level (at 1 m for 1 W @ Re)                      |
| Lnom                  | 87.02  | dB   | nominal sensitivity (SPL at 1 m for 1 W @ Zn)                                  |
| Sd                    | 133.00 | cm²  | diaphragm area                                                                 |

</br></br>

## Large Signal Modeling (Linear Xmax Results)

Using [Klippel's Distortion Analyzer 2](https://www.klippel.de/products/rd-system/analyzer-hardware/da2-klippel-distortion-analyzer.html), [Large Signal Identification Module](https://www.klippel.de/nc/en/products/rd-system/modules/lsi-large-signal-identification-da2.html?sword_list%5B0%5D=lsi), [Pro Driver Stand](https://www.klippel.de/nc/en/products/rd-system/accessories/overview-accessories/pro-driver-stand.html?sword_list%5B0%5D=stand) and provided [Panasonic ANR12821 Laser](https://panasonicsensors.com/anr12821) along with [Klippel's Training 3 - Loudspeaker Nonlinearities tutorial](https://www.youtube.com/watch?v=TJvhZ9pndGA), I measured the linear, nonlinear and thermal parameters of this drive unit.

### Nonlinearities

Traditionally, Xmax has been defined in one of the following ways:
- the physical overhang of the voice coil (height of the voice coil relative to height of the gap)
- 115% times the physical overhang above
- the point where displacement limit(s) is/are exceeded

The third option is where the Klippel LSI module comes in to play. It permits a more "apples to apples" approach of defining the displacement (Xmax) limits based on the XBL, XC, XL and Xd.  The displacement limits XBL, XC, XL and Xd describe the limiting effect for the force factor Bl(x), compliance Cms(x), inductance Le(x) and Doppler effect, respectively, according to the threshold values Blmin, Cmin, Zmax and d2 used by the operator.

</br>

There are one of two sets of thresholds which can be used to define linear excursion:
1) Non-Subwoofer Drivers: The thresholds Blmin= 82 %, Cmin=75 %, Zmax=10 % and d2=10% generate for a two-tone-signal (f1=fs, f2=8.5fs) 10 % total harmonic distortion and 10 % intermodulation distortion.
2) Subwoofer Drivers: The thresholds Blmin= 70 %, Cmin=50 %, Zmax=17 % create 20 % total harmonic distortion which is becoming the standard for acceptable subwoofer distortion thresholds.

</br>

These parameters are defined in more detail in the (Klippel) papers:
* “AN04 – Measurement of Peak Displacement Xmax”
* “AN05 - Displacement Limits due to Driver Nonlinearities”
* “AN17 - Credibility of Nonlinear Parameters”
* “Prediction of Speaker Performance at High Amplitudes”
* “Assessment of Voice Coil Peak Displacement Xmax”
* “Assessing Large Signal Performance of Loudspeakers”

</br></br>

Below are the displacement limits' results for this drive unit obtained from Klippel's LSI module:

| Displacement Limits   |             |         |                                                                   |
|-----------------------|-------------|---------|-------------------------------------------------------------------|
| X Bl @ Bl min=82%     | 3.3         | mm      | Displacement limit due to force factor variation                  |
| X C @ C min=75%       | 5.1         | mm      | Displacement limit due to compliance variation                    |
| X L @ Z max=10 %      | >5.8         | mm      | Displacement limit due to inductance variation                    |
| X d @ d2=10%          | 19.3        | mm      | Displacement limit due to IM distortion (Doppler)                 |


</br>

</br>


We can break the above information down further.  The below text is written by Patrick Turnmire of [Red Rock Acoustics](http://www.redrockacoustics.com/) and used with his permission, substituting data from this drive unit's test results where applicable.

</br>
</br>

#### Large Signal Modeling

At higher amplitudes, loudspeakers produce substantial distortion in the output signal, generated by
nonlinear ties inherent in the transducer. The dominant nonlinear distortions are predictable and are
closely related with the general principle, particular design, material properties and assembling
techniques of the loudspeaker. The Klippel Distortion Analyzer combines nonlinear measurement
techniques with computer simulation to explain the generation of the nonlinear distortions, to identify
their physical causes and to give suggestion for constructional improvements. Better insight into the
nonlinear mechanisms makes it possible to further optimize the transducer in respect with sound
quality, weight, size and cost.

</br>

#### Nonlinear Characteristics

The dominant nonlinearities are modelled by variable parameters such as

|        |                                                                                                                                                                                         |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bl(x)  | instantaneous electro-dynamic coupling factor (force factor of the motor) defined by the integral of the magnetic flux density B over voice coil length l as a function of displacement |
| KMS(x) | mechanical stiffness of driver suspension a function of displacement                                                                                                                    |
| LE(i)  | voice coil inductance as a function of input current (describes nonlinear permeability of the iron path)                                                                                |
| LE(x)  | voice coil inductance as a function of displacement                                                                                                                                     |                                                                                                                                 |

</br>
</br>

#### Nonlinear Parameters

<details>
<summary>
**Click HERE for Explanations of the below data**
</summary>
</br>
<p>


**Bl change with excursion**


The electrodynamic coupling factor, also called Bl-product or force factor Bl(x), is defined by the
integral of the magnetic flux density B over voice coil length l and translates current into force. In
traditional modeling this parameter is assumed to be constant. The force factor Bl(0) at the rest
position corresponds with the Bl-product used in linear modeling. The red curve displays Bl over the
entire displacement range covered during the measurement. You see the typical decay of Bl when the
voice coil moves out of the gap. At the end of the measurement, the black curve shows the confidential
range (interval where the voice coil displacement in this range occurred 99% of the measurement
time). During the measurement, the black curve shows the current working range. The dashed curve
displays Bl(x) mirrored at the rest position of the voice coil – this way, asymmetries can be quickly
identified. Since a laser was connected during the measurement, a coil in / coil out marker is
displayed on the bottom left / bottom right.

</br>
</br>

**Suspension Stiffness change with excursion**

The stiffness KMS(x) describes the mechanical properties of the suspension. Its inverse is the
compliance CMS(x).

</br>
</br>

**Inductance change with excursion**

The inductance components Le (x) and Bl(i) of most drivers have a strong asymmetric characteristic. If
the voice coil moves towards the back plate the inductance usually increases since the magnetic field
generated by the current in the voice coil has a lower magnetic resistance due to the shorter air path.
The nonlinear inductance Le(x) has two nonlinear effects. First the variation of the electrical impedance
with voice coil displacement x affects the input current of the driver. Here the nonlinear source of
distortion is the multiplication of displacement and current. The second effect is the generation of a
reluctance force which may be interpreted as an electromagnetic motor force proportional to the
squared input current.

The flux modulation Bl(i) has two effects too. On the electrical side the back EMF Bl(i)\*v produces
nonlinear distortion due to the multiplication of current i and velocity v. On the mechanical side the
driving force F = Bl(i)\*i comprises a nonlinear term due to the squared current i. This force produces
similar effects as the variable term Le(x).


#### Asymmetrical Nonlinearities

Asymmetrical nonlinearities produce not only second- and higher-order distortions but also a dc-part in
the displacement by rectifying low frequency components.
For an asymmetric stiffness characteristic the dc-components moves the voice coil for any excitation
signal in the direction of the stiffness minimum.
For an asymmetric force factor characteristic the dc-component depends on the frequency of the
excitation signal. A sinusoidal tone below resonance (f<fS) would generate or force moving the voice
coil always in the force factor maximum. This effect is most welcome for stabilizing voice coil position.
However, above the resonance frequency (f>fS) would generate a dc-component moving the voice coil
in the force factor minimum and may cause severe stability problems.
For an asymmetric inductance characteristic the dc-component moves the voice coil for any excitation
signal in the direction of the inductance maximum.
Please note that the dynamically generated DC-components cause interactions between the driver
nonlinearities. An optimal rest position of the coil in the gap may be destroyed by an asymmetric
compliance or inductance characteristic at higher amplitudes. The module Large Signal Simulation
(SIM) allows systematic investigation of the complicated behavior.

</br>

**Bl symmetry xb(x)**

This curve shows the symmetry point in the nonlinear Bl-curve where a negative and positive
displacement x=xpeak will produce the same force factor Bl(xb(x) + x) = Bl(xb(x) – x).

If the shift xb(x) is independent on the displacement amplitude x then the force factor asymmetry is
caused by an offset of the voice coil position and can be simply compensated.

If the optimal shift xb(x) varies with the displacement amplitude x then the force factor asymmetry is
caused by an asymmetrical geometry of the magnetic field and cannot completely be compensated by
coil shifting.

</br>

**Kms Symmetry xc(x)**

This curve shows the symmetry point in the nonlinear compliance curve where a negative and positive
displacement x=xpeak will produce the same compliance value kms(xc(x) + x) = kms(xc(x) – x).

A high value of the symmetry point xc(x) at small displacement amplitudes x » 0 indicates that the rest
position does not agree with the minimum of the stiffness characteristic. This may be caused by an
asymmetry in the geometry of the spider (cup form) or surround (half wave). A high value of the
symmetry point xc(x) at maximal displacement x» xmax may be caused by asymmetric limiting of the
surround.

</br>

</p>
  </details>
</br>

  <img align="left" src="https://dl.dropboxusercontent.com/s/0p7dk17dwb6120h/lsi.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
  <br>

</br>
</br>



#### Parameters at the Rest Position

For accurate system modelling “Large + Cold” parameters are preferable to “Small Signal” parameters because they more closely reflect the parameters in their typical operating range.

| Symbol                | Large + Warm | Large + Cold | Small Signal | Unit | Comment                                                                                                      |
|-----------------------|--------------|--------------|--------------|------|--------------------------------------------------------------------------------------------------------------|
| Note:                 |         |         |         |      | For accurate small signal parameters, use LPM module                                                         |
|-----------------------|---------|---------|---------|------|--------------------------------------------------------------------------------------------------------------|
| Delta Tv [referenced] | 68.8    |         | 0       | K    | Increase of voice coil temperature during the measurement referenced to imported Re(Delta Tv=0K)             |
| Delta Tv = Tv-Ta      | 53.5    | 0       | 0       | K    | Increase of voice coil temperature during the measurement                                                    |
| Xprot                 | 6.7     | 6.7     | 1.1     | mm   | Maximum voice coil excursion (limited by protection system)                                                  |
|                       |         |         |         |      |                                                                                                              |
| Re(Tv)                | 8.23    | 6.84    | 6.84    | Ohm  | Voice coil resistance considering increase of voice coil temperature Tv                                      |
| Le(x=0)               | 0.25    | 0.25    | 0.25    | mH   | Voice coil inductance at the rest position of the voice coil                                                 |
| L2(x=0)               | 0.40    | 0.40    | 0.33    | mH   | Ppara-inductance at the rest position due to the effect of eddy current                                      |
| R2(x=0)               | 1.13    | 1.13    | 1.17    | Ohm  | Resistance at the rest position due to eddy currents                                                         |
| Cmes(x=0)             | 214     | 214     | 193     | µF   | Electrical capacitance representing moving mass                                                              |
| Lces(x=0)             | 53.77   | 53.77   | 44.41   | mH   | Electrical inductance at the rest position representing driver compliance                                    |
| Res(x=0)              | 69.96   | 69.96   | 33.20   | Ohm  | Resistance at the rest position due to mechanical losses                                                     |
|                       |         |         |         |      |                                                                                                              |
| Qms(x=0, Tv)          | 4.41    | 4.41    | 2.19    |      | Mechanical Q-factor considering the mechanical system only                                                   |
| Qes(Tv)               | 0.43    | 0.36    | 0.45    |      | Electrical Q-factor considering Re (Tv) only                                                                 |
| Qts(x=0, Tv)          | 0.39    | 0.33    | 0.37    |      | Total Q-factor considering Re (Tv) and Rms only                                                              |
| fs                    | 47.0    | 47.0    | 54.4    | Hz   | Driver resonance frequency                                                                                   |
|                       |         |         |         |      |                                                                                                              |
| Mms                   | 17.646  | 17.646  |         | g    | (calculated from imported Bl) Mechanical mass of driver diaphragm assembly including voice-coil and air load |
| Rms(x=0)              | 1.181   | 1.181   | 2.994   | kg/s | Mechanical resistance of  total-driver losses                                                                |
| Cms(x=0)              | 0.65    | 0.65    | 0.45    | mm/N | Mechanical compliance of driver suspension at the rest position                                              |
| Kms(x=0)              | 1.54    | 1.54    | 2.24    | N/mm | Mechanical stiffness of driver suspension at the rest position                                               |
| Bl(x=0)               | 9.97    | 9.97    | 9.97    | N/A  | (imported) Force factor at the rest position (Bl product)                                                    |
| Vas                   | 16.2353 | 16.2353 | 11.1422 | l    | Equivalent air volume of suspension                                                                          |
| N0                    | 0.374   | 0.449   | 0.382   | %    | Reference efficiency (2Pi-sr radiation using Re)                                                             |
| Lm                    | 87.9    | 88.7    | 88.0    | dB   | Characteristic sound pressure level                                                                          |
|                       |         |         |         |      |                                                                                                              |
| Sd                    | 133.00  | 133.00  | 133.00  | cm²  | Diaphragm area                                                                                               |

<br>
<br>

## Frequency Response & Impedance

All data collected using [Klippel's Near-Field Scanner](http://www.klippel.de/products/rd-system/modules/nfs-near-field-scanner.html#:~:text=The%20Near%2DField%20Scanner%203D,move%20during%20the%20scanning%20process.).  The Near-Field-Scanner 3D (NFS) offers a fully automated acoustic measurement of direct sound radiated from the source under test. The radiated sound is determined in any desired distance and angle in the 3D space outside the scanning surface. Directivity, sound power, SPL response and many more key figures are obtained for any kind of loudspeaker and audio system in near field applications (e.g. studio monitors, mobile devices) as well as far field applications (e.g. professional audio systems). Utilizing a minimum of measurement points, a comprehensive data set is generated containing the loudspeaker's high resolution, free field sound radiation in the near and far field.  For a detailed explanation of how the NFS works and the science behind it, please watch the below discussion with designer Christian Bellmann:
<iframe width="560" height="315" src="https://www.youtube.com/embed/-s-R1HCYUYs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<br>
<br>

This speaker was measured using the Klippel Near Field Scanner *Baffle* module, permitting accurate "infinite baffle" results.  Per Klippel's documentation ([here](https://www.youtube.com/redirect?event=comments&redir_token=QUFFLUhqbGNYQ0FOZzltZzJTT3V2OGt5bzZ0UVRxdjVvZ3xBQ3Jtc0ttaDhGamFIdzZ4cmNPNFNrYjhqMWdRRUN6anVnQ2Vwa1BWanpYbi1hb2g4Wmd4QVUweE8zbUptOFFmVDYtclk1Ql85dmpwNjVocXdaOVVIQk1lLWw3MUFuSmZid0F5MlktWmJESE1RT0ZjeVNMdWpnOA&q=https%3A%2F%2Fwww.klippel.de%2Fproducts%2Frd-system%2Fmodules%2Fnfs-near-field-scanner.html&stzid=UgxBTCgtGgLmfR7Dvh94AaABAg)):
<br>
*"By scanning on 2 hemi-spheres in front of the speaker, room reflection as well as diffraction effects from the baffle can be removed, providing accurate half space data."*

The test baffle has a sealed volume of approximately 2ft³ which is well above Vas for this driver. If you would like to see the construction of my baffle, please watch [this video](https://youtu.be/PXNC3hc8HrY).
<br><br>


  <img align="left" src="https://dl.dropboxusercontent.com/s/3p1ext9s0irwfy3/PTT6.5M-08-NFA-01A%20Frequency%20Response.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
  <br>

  <img align="left" src="https://dl.dropboxusercontent.com/s/3xr5fg6ipue1noo/PTT6.5M-08-NFA-01A%20Impedance.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
  <br>

## Harmonic Distortion:

Harmonic Distortion at 86dB @ 1m:
  <img align="left" src="https://dl.dropboxusercontent.com/s/itw2o5b0zcnh8el/PTT6.5M-08-NFA-01A%20Harmonic%20Distortion%20%2886dB%20%40%201m%29.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
  <br>

  Harmonic Distortion at 96dB @ 1m:
  <img align="left" src="https://dl.dropboxusercontent.com/s/ccgoclzm8cyo3b9/PTT6.5M-08-NFA-01A%20Harmonic%20Distortion%20%2896dB%20%40%201m%29.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
  <br>

<br><br>

## Intermodulated Distortion (IMD):

Klippel's [3D-DISTORTION MEASUREMENT (DIS) module](https://www.klippel.de/products/rd-system/modules/dis-3d-distortion-measurement.html) is used to calculate the Intermodulated Distortion for this drive unit.

Measurements were completed in the nearfield.  Multiple output levels were tested to provide the trend of distortion component profiles and to provide a comparison against other drive units I have tested.  The SPL provided is relative to 1 meter distance, averaged in the noted bandpass region.

Unlike Harmonic Distortion - which is a measure of only harmonics from a single tone - IMD is tested with two tones at the same time: a low frequency "bass tone" near Fs and a higher frequency "voice tone" much greater than Fs.  For example a speaker driver plays 30Hz at the same time it plays 200Hz.  Any distortion artifacts created by the sum and/or difference of the speaker playing both tones at the same time is a result of IMD.  In this example, the speaker is supposed to play *only* 30Hz & 200Hz at the same time.  Thanks to IMD, it plays 200Hz ± 30Hz.  Second order IMD would be 200 ± 30Hz = 170Hz & 230Hz.  Third order IMD would be 200 ± 60Hz = 140Hz & 260Hz.  If these 'side bands' are high enough in output then they are heard as distortion.  If not, they are not.

With that in mind, I used Klippel's DIS module to test this drive unit in two ways:
1) "Bass tone" fixed at 30Hz, with a "voice sweep" where the 200Hz - 6kHz region is played, one tone at a time (over 50 individual tones).
2) The same as above, but the "bass tone" fixed at 80Hz.

The purpose of me testing with two methods (different "bass tones") is to see the difference between what happens when the driver plays with high(er) excursion vs when a typical HPF is used.  All similarly sized and similarly purposed speakers are tested in the same manner.  For better or worse.  This means a 6-inch midwoofer is tested the same way an 8-inch midwoofer is.  Ultimately, this is for my sanity, because having numerous measurement methods for all sizes of speakers would muddy the waters quickly and wouldn't give us an idea of when performance is great (say, a 6-inch midwoofer that has much less distortion than an 8-inch) or vice-versa.

The above is tested at 2 voltages each with an equivalent 86dB & 96dB @ 1m output.  As is the case with the multiple HD tests, the multiple IMD levels provides an idea of what the speaker's IMD profiles look like as the output of the speaker is increased.



**Test 1: Bass Tone at 30Hz, Voice Tones from 200-6000Hz**

86dB @ 1m:
<img align="left" src="https://dl.dropboxusercontent.com/s/40z37jq1g1ymcf4/imd%201.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
<br>

96dB @ 1m:
<img align="left" src="https://dl.dropboxusercontent.com/s/zlo3h6o3i7y0n0l/imd%202.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
<br>

<br><br>

**Test 2: Bass Tone at 80Hz, Voice Tones from 200-6000Hz**

86dB @ 1m:
<img align="left" src="https://dl.dropboxusercontent.com/s/83c4uiwu8g1piu6/imd%203.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
<br>

96dB @ 1m:
<img align="left" src="https://dl.dropboxusercontent.com/s/38n8im7o8t5djpb/imd%204.png?dl=0" alt="specs" width="100%" style="vertical-align:middle;margin:20px 0px"/><br clear="all" />
<br>

<br><br>



<br><br>

# Support the Cause

If you find this review helpful and want to help support the cause there are a few ways you can do so below.  Your support helps me pay for new items to test, hardware, miscellaneous items needed for testing and costs of the site's server space and bandwidth.  Any help is *very much* appreciated.
<br>

Join my Patreon:
<a href="https://www.patreon.com/bePatron?u=59439731" data-patreon-widget-type="become-patron-button">Become a Patron!</a><script async src="https://c6.patreon.com/becomePatronButton.bundle.js"></script> <form action="https://www.paypal.com/donate" method="post" target="_top">
<input type="hidden" name="hosted_button_id" value="XV7EYYU7S77LE" />
<br>

Donate via PayPal:
<br>
<input type="image" src="https://i.imgur.com/Z608uUQ.png" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>

Or using my product affiliate link below to buy *anything* they sell that you want to try out.  This will earn me a small commission at no additional cost to you.  You can use these links anytime, now or in the future.
<br>
* [Audio Advice](https://www.audioadvice.com/?referral=erins-audio-corner&b=3)
<br>
* [Crutchfield](https://shop-links.co/cgZmmT81jmh)
<br>
* [Amazon](https://amzn.to/3jl4mRC)
<br>
<br>
<br>

You can also join my [Facebook](https://www.facebook.com/groups/607627396679113/) and [YouTube](https://www.youtube.com/user/hardisj) pages if you'd like to follow along with updates.
