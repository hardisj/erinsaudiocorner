---
title: "Fountek FR89EX Fullrange"
date: 2013-01-02
draft: false
image: "http://www.parts-express.com/data/default/images/catalog/500/296-721_HR_0.jpg"
description : "Fountek FR89EX Fullrange"
Tags: ["Fountek", "FR89EX", "Fullrange"]
---


Another popular choice for fullrange use, the [Fountek FR89EX (PE Affiliate Link here)](https://www.anrdoezrs.net/click-7732025-13715689?url=http%3A%2F%2Fwww.parts-express.com%2Ffountek-fr89ex-3-neodymium-full-range-speaker-driver--296-721&cjsku=296-721) is tested and results provided below.

This is the smaller brother of the FR88EX which I tested [here](https://www.erinsaudiocorner.com/driveunits/fountek_fr88ex/).



<br>
<br>

## Thiele-Small and Impedance Test Results

| Electrical Parameters |        |      |                                                                                |
|-----------------------|--------|------|--------------------------------------------------------------------------------|
| Re                    | 3.61   | Ohm  | electrical voice coil resistance at DC                                         |
| Le                    | 0.029  | mH   | frequency independent part of voice coil inductance                            |
| L2                    | 0.170  | mH   | para-inductance of voice coil                                                  |
| R2                    | 1.47   | Ohm  | electrical resistance due to eddy current losses                               |
| Cmes                  | 266    | µF   | electrical capacitance representing moving mass                                |
| Lces                  | 10.25  | mH   | electrical inductance representing driver compliance                           |
| Res                   | 8.32   | Ohm  | resistance due to mechanical losses                                            |
| fs                    | 96.4   | Hz   | driver resonance frequency                                                     |
| Mechanical Parameters |        |      |                                                                                |
| (using test encl.)    |        |      |                                                                                |
| Mms                   | 2.294  | g    | mechanical mass of driver diaphragm assembly including air load and voice coil |
| Mmd (Sd)              | 2.213  | g    | mechanical mass of voice coil and diaphragm without air load                   |
| Rms                   | 1.035  | kg/s | mechanical resistance of total-driver losses                                   |
| Cms                   | 1.189  | mm/N | mechanical compliance of driver suspension                                     |
| Kms                   | 0.84   | N/mm | mechanical stiffness of driver suspension                                      |
| Bl                    | 2.936  | N/A  | force factor (Bl product)                                                      |
| Loss factors          |        |      |                                                                                |
| Qtp                   | 0.407  |      | total Q-factor considering all losses                                          |
| Qms                   | 1.342  |      | mechanical Q-factor of driver in free air considering Rms only                 |
| Qes                   | 0.582  |      | electrical Q-factor of driver in free air considering Re only                  |
| Qts                   | 0.406  |      | total Q-factor considering Re and Rms only                                     |
| Other Parameters      |        |      |                                                                                |
| Vas                   | 1.2582 | l    | equivalent air volume of suspension                                            |
| n0                    | 0.186  | %    | reference efficiency (2 pi-radiation using Re)                                 |
| Lm                    | 84.89  | dB   | characteristic sound pressure level (SPL at 1m for 1W @ Re)                    |
| Lnom                  | 85.33  | dB   | nominal sensitivity (SPL at 1m for 1W @ Zn)                                    |
| Sd                    | 27.34  | cm²  | diaphragm area                                                                 |

<br>


![](/images/Reviews/Drivers/Fountek/FR89EX/Fountek-FR89EX-impedance.png)

<br>
<br>

## Large Signal Analysis from Klippel LSI Module

| Displacement Limits |      |    | thresholds can be changed in Processing property page |
|---------------------|------|----|-------------------------------------------------------|
| X Bl @ Bl min=82%   | >3.8 | mm | Displacement limit due to force factor variation      |
| X C @ C min=75%     | 2.6  | mm | Displacement limit due to compliance variation        |
| X L @ Z max=10 %    | >3.8 | mm | Displacement limit due to inductance variation        |
| X d @ d2=10%        | 10.7 | mm | Displacement limit due to IM distortion (Doppler)     |

<br>


![](/images/Reviews/Drivers/Fountek/FR89EX/fr89ex-img_Bl-X.png)

![](/images/Reviews/Drivers/Fountek/FR89EX/fr89ex-img_Bl-Symmetry-Range.png)

![](/images/Reviews/Drivers/Fountek/FR89EX/fr89ex-img_Kms-X.png)

![](/images/Reviews/Drivers/Fountek/FR89EX/fr89ex-img_Kms-Symmetry-Range.png)

![](/images/Reviews/Drivers/Fountek/FR89EX/fr89ex-img_LX.png)

![](/images/Reviews/Drivers/Fountek/FR89EX/fr89ex-img_LI.png)



<br>
<br>

## Frequency Response

Response comparison at 0, 30, and 60 degrees.  1/24 Octave resolution.

![](/images/Reviews/Drivers/Fountek/FR89EX/Fountek-FR89EX-0-30-60.png)


<br>
<br>

## Harmonic Distortion

Note:  This test was performed in the farfield, and subsequent to environmental issues such as reflections and noise. Therefore, fundamental response below 200hz is not provided here.

96dB/1m

![](/images/Reviews/Drivers/Fountek/FR89EX/Fundamental--Harmonic-distortion-components-96dB1m1.png)

![](/images/Reviews/Drivers/Fountek/FR89EX/Relative-Harmonic-distortion-96dB1m1.png)


<br>

## Wrap-Up

Really, pretty much everything I said about the FR88EX applies here.  So much of this is unchanged from that review.  However, the results are not the exact same so here we go...

Senstivity is rather low, in the low-to-mid 80's; a little higher than the FR88EX.  But that's kind of expected out of a "fullrange" where sensitivity is sacrificed for linear excursion and high frequency extension.
Increasing distortion levels at 96dB/1m equivalent below 300hz; use a proper crossover here to limit excursion and take some load off the voice coil so it doesn't saturate and thusly become "compressed" (compressed = when the voice coil can't expend heat and therefore as you increase the volume, the output level stops increasing and instead you lose volume).
A few problematic distortion spikes but given their narrow band I can't say how audible they would be without purposely listening to this speaker with test tones.
IMD (intermodulated distortion) should be helped with the use of the inductance limiting shorting ring as evidenced by the symmetrical Le(x) plots.

Now, the *considerable* difference between this and the FR89EX is this driver has worse above 10kHz.  This just plan does not look good.

Of course, one could simply use this as a dedicated midrange in a 3-way - maybe 300hz to 4khz - and for the price it might be worth that.  But the low sensitivity still is a limiting factor.

Fundamentally, I'm not a proponent of fullrange or wideband drivers.  I just prefer to use a 3-way than deal with the shortcomings of most fullranges; shortcomings being: low sensitivity, breakup issues outside of beaming that can't be EQ'd or otherwise corrected via DSP.
But if you have a need for one or want to experiment, this might be worth playing with since it's pretty cheap, though, consider my comments above.

<br>
<br>

## End

If you like what you see here and want to help me keep it going, there’s a Paypal Contribute button at the bottom of each page.  Just provide what you can.  Every little bit is truly appreciated.

You can also join my Facebook and YouTube pages via the links at the bottom of the page if you'd like to follow along with updates.

<br>Thanks!</b>

![](https://thumbs.gfycat.com/HorribleInsistentBoar-size_restricted.gif)


<br></br>
<center>
  <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_s-xclick" />
  <input type="hidden" name="hosted_button_id" value="52ANEATKE6JHQ" />
  <input type="image" src="https://www.dcrc.co/wp-content/uploads/2016/06/PayPal-Donate-Button-PNG-HD-300x103.png" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
  <img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
  </form>
<br></br>
</center>
