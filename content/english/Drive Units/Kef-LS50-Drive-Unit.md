---
title: "Kef LS50 Speaker Drive Unit Testing"
date: 2014-02-01
draft: false
image_webp: images/Reviews/Drivers/Kef/LS50_Driver/IMG_8503_small.webp
image: images/Reviews/Drivers/Kef/LS50_Driver/IMG_8503_small.jpg
description : "Kef LS50"
Tags: ["Kef", "LS50", "Tangerine", "waveguide", "LS50"]
---
Up for test is the raw drive unit from Kef’s flagship LS50 monitor.  This bookshelf speaker set has gotten a whole lot of praise over the years and as of this writing (02/03/2020) is currently priced at $899 on Amazon [(affiliate link here)](https://amzn.to/2SsPByj), if you feel so inclined to purchase them.

About a year ago I ran the gamut on some Kef drivers: the HTS3001SE concetric, [(LS50 5.25″ concentric)]("https://www.erinsaudiocorner.com/drive-units/kef-q100-drive-unit/"), and the R-series concentric.  Knowing the lineage points to the LS50 drive unit as a mix of the Q-series concetric with it’s Z-flex surround and the R-series concetric midrange with it’s ribbed cone for reducing mid-high frequency breakup, I was curious to see the measured performance.  I finally was provided a drive unit to test, so here we go.

Let's get on to the testing, but first ... the obligatory pictures ...

![KefLS50 Speaker](/images/Reviews/Drivers/Kef/LS50_Driver/AKEFLS50B.jpg)

(^Borrowed that one from Kef's site)

![kefLS50](/images/Reviews/Drivers/Kef/LS50_Driver/IMG_8503.jpg)

![kefLS50](/images/Reviews/Drivers/Kef/LS50_Driver/IMG_8504.jpg)

![kefLS50](/images/Reviews/Drivers/Kef/LS50_Driver/IMG_8505.jpg)


Recaling from memory, this driver physically is roughly the same size as the Q100 drive unit I tested previously in all aspects.

<br></br>
#### Test Results

To make things a bit easier to manage, I’ve broken down the test results in to two sections:

1. Woofer Testing
2. Tweeter Testing

#### Part I: Woofer Testing
##### Woofer Thiele-Small Parameters and Impedance

Note:  When determining the full suite of T/S parameters, the effective diameter of the driver is needed to calculate Vas, Bl, etc.  Most of the time this can simply be measured by measuring the diameter of the driver from half-surround to half-surround since the motor must control the entire cone area.  However, in this case, the entire cone does not move.  Therefore, the effective diameter (and resulting Sd) is not the entire diameter of the driver.  The effective diameter here is determined by subtracting the static tweeter assembly from the overall effective diameter of the woofer.  See physical measurements section above for all values.

| Electrical Parameters |        |      |                                                                                |
|-----------------------|--------|------|--------------------------------------------------------------------------------|
| Re                    | 3.01   | Ohm  | electrical voice coil resistance at DC                                         |
| Le                    | 0.197  | mH   | frequency independent part of voice coil inductance                            |
| L2                    | 0.474  | mH   | para-inductance of voice coil                                                  |
| R2                    | 2.46   | Ohm  | electrical resistance due to eddy current losses                               |
| Cmes                  | 332    | µF   | electrical capacitance representing moving mass                                |
| Lces                  | 9.72   | mH   | electrical inductance representing driver compliance                           |
| Res                   | 27.62  | Ohm  | resistance due to mechanical losses                                            |
| fs                    | 88.6   | Hz   | driver resonance frequency                                                     |
| Mechanical Parameters |        |      |                                                                                |
| (using add. mass)     |        |      |                                                                                |
| Mms                   | 10.432 | g    | mechanical mass of driver diaphragm assembly including air load and voice coil |
| Mmd (Sd)              | 9.706  | g    | mechanical mass of voice coil and diaphragm without air load                   |
| Rms                   | 1.137  | kg/s | mechanical resistance of  total-driver losses                                  |
| Cms                   | 0.309  | mm/N | mechanical compliance of driver suspension                                     |
| Kms                   | 3.23   | N/mm | mechanical stiffness of driver suspension                                      |
| Bl                    | 5.604  | N/A  | force factor (Bl product)                                                      |
| Loss factors          |        |      |                                                                                |
| Qtp                   | 0.507  |      | total Q-factor considering all losses                                          |
| Qms                   | 5.107  |      | mechanical Q-factor of driver in free air considering Rms only                 |
| Qes                   | 0.557  |      | electrical Q-factor of driver in free air considering Re only                  |
| Qts                   | 0.502  |      | total Q-factor considering Re and Rms only                                     |
| Other Parameters      |        |      |                                                                                |
| Vas                   | 2.4278 | l    | equivalent air volume of suspension                                            |
| n0                    | 0.291  | %    | reference efficiency (2 pi-radiation using Re)                                 |
| Lm                    | 86.84  | dB   | characteristic sound pressure level (SPL at 1m for 1W @ Re)                    |
| Lnom                  | 88.07  | dB   | nominal sensitivity (SPL at 1m for 1W @ Zn)                                    |
| Madd                  | 9.79   | g    | additional mass                                                                |
| Sd                    | 74.46  | cm²  | diaphragm area                                                                 |

<br></br>

![kefLS50 imp](/images/Reviews/Drivers/Kef/LS50_Driver/ls50-woofer-impedance-1.png)

<br></br>

| Displacement Limits   |      |    | thresholds can be changed in Processing property page |
|-----------------------|------|----|-------------------------------------------------------|
| X Bl @ Bl min=82%     | 6.7  | mm | Displacement limit due to force factor variation      |
| X C @ C min=75%       | 2.9  | mm | Displacement limit due to compliance variation        |
| X L @ Z max=10 %      | >7.0 | mm | Displacement limit due to inductance variation        |
| X d @ d2=10%          | 12.7 | mm | Displacement limit due to IM distortion (Doppler)     |
| Asymmetry (IEC 62458) |      |    |                                                       |
| Ak                    | 7.59 | %  | Stiffness asymmetry Ak(Xpeak)                         |
| Xsym                  | 0.19 | mm | Symmetry point of Bl(x) at maximal excursion          |

<br></br>
![kefLS50 bl](/images/Reviews/Drivers/Kef/LS50_Driver/Force-factor-Bl-X.png)
<br></br>
![kefLS50 bl-sym](/images/Reviews/Drivers/Kef/LS50_Driver/Bl-Symmetry-Range.png)
<br></br>
![kefLS50 cms](/images/Reviews/Drivers/Kef/LS50_Driver/Mechanical-compliance-Cms-X.png)
<br></br>
![kefLS50 kms](/images/Reviews/Drivers/Kef/LS50_Driver/Stiffness-of-suspension-Kms-X.png)
<br></br>
![kefLS50 kms-sym](/images/Reviews/Drivers/Kef/LS50_Driver/Kms-Symmetry-Range.png)
<br></br>
![kefLS50 indx](/images/Reviews/Drivers/Kef/LS50_Driver/Electrical-inductance-LX-I00.png)
<br></br>
![kefLS50 indi](/images/Reviews/Drivers/Kef/LS50_Driver/Inductance-over-current-LX0-I.png)

<br></br>
##### Woofer Frequency Response
Measured at 2.83v/1m.  Stitched with a nearfield measurement at approximately 500hz.
<br></br>**Note:** Due to the rather tall surround and the fact I don’t have the trim ring used to flush mount the driver in a baffle, this driver was not flush mounted.  This will effect the high frequency response to some degree.

* Black = 0 Deg
* Orange = 30 Deg
* Blue = 60 Deg

![kefLS50 FR03060WOOFER](/images/Reviews/Drivers/Kef/LS50_Driver/LS50-woofer-0-30-60.png)

<br></br>
##### Woofer Harmonic Distortion
<br></br> Harmonic Distortion below given at 90dB/1m and 96dB/1m equivalents.
<br></br>
![kefLS50 FRHDWOOFER90](/images/Reviews/Drivers/Kef/LS50_Driver/HD--90db.png)
<br></br>

![kefLS50 FRHDWOOFER96](/images/Reviews/Drivers/Kef/LS50_Driver/HD--96db.png)

<br></br>

#### Part II: Tweeter Testing
##### Small Signal Parameters
| Electrical Parameters |       |     |                                                                |
|-----------------------|-------|-----|----------------------------------------------------------------|
| Re                    | 3.14  | Ohm | electrical voice coil resistance at DC                         |
| Le                    | 0.013 | mH  | frequency independent part of voice coil inductance            |
| L2                    | 0.01  | mH  | para-inductance of voice coil                                  |
| R2                    | 0.41  | Ohm | electrical resistance due to eddy current losses               |
| Cmes                  | 92    | µF  | electrical capacitance representing moving mass                |
| Lces                  | 0.19  | mH  | electrical inductance representing driver compliance           |
| Res                   | 1.02  | Ohm | resistance due to mechanical losses                            |
| fs                    | 1205  | Hz  | driver resonance frequency                                     |
| Loss factors          |       |     |                                                                |
| Qtp                   | 0.536 |     | total Q-factor considering all losses                          |
| Qms                   | 0.709 |     | mechanical Q-factor of driver in free air considering Rms only |
| Qes                   | 2.185 |     | electrical Q-factor of driver in free air considering Re only  |
| Qts                   | 0.535 |     | total Q-factor considering Re and Rms only                     |

<br></br>
##### Tweeter Frequency Response
Measurement taken at 2.83v/1m.
<br></br>**Note:** Due to the rather tall surround and the fact I don’t have the trim ring used to flush mount the driver in a baffle, this driver was not flush mounted.  This will effect the high frequency response to some degree.

* Black = 0 Deg
* Orange = 30 Deg
* Blue = 60 Deg

<br></br>
![kefLS50 FRTWEETER](/images/Reviews/Drivers/Kef/LS50_Driver/LS50-tweeter-0-30-60.png)

<br></br>
##### Tweeter Harmonic Distortion
<br></br> Harmonic Distortion below given at 90dB/1m and 96dB/1m equivalents.
![kefLS50 FRHDTWEETER90](/images/Reviews/Drivers/Kef/LS50_Driver/LS50_Tweeter_HD-@-90db1.png)
<br></br>
![kefLS50 FRHDTWEETER96](/images/Reviews/Drivers/Kef/LS50_Driver/LS50_Tweeter_HD-@-96db1.png)
<br></br>

### End

If you like what you see here and want to help me keep it going, there’s a Paypal Contribute button at the bottom of each page.  Just provide what you can.  Every little bit is truly appreciated.

<br>Thanks!</b>

![wargames](/images/Reviews/Drivers/Kef/LS50_Driver/no_one_wins.gif)



<br></br>
<center>
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="G9NX6FN9VUVHQ" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>
<br></br>
</center>
