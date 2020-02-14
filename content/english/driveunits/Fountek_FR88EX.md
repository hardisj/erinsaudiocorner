---
title: "Fountek FR88EX Fullrange"
date: 2013-01-02
draft: false
image: "http://www.parts-express.com/data/default/images/catalog/500/296-719_HR_0.jpg"
description : "Fountek FR88EX Fullrange"
Tags: ["Fountek", "FR88EX", "Fullrange"]
---


Another popular choice for fullrange use, the [Fountek FR88EX (PE Affiliate Link here)](https://www.tkqlhce.com/click-7732025-13715689?url=http%3A%2F%2Fwww.parts-express.com%2Ffountek-fr88ex-3-neodymium-full-range-speaker-driver--296-719&cjsku=296-719) is tested and results provided below.

For data on the FR89EX click here.



<br>
<br>

## Thiele-Small and Impedance Test Results

| Electrical Parameters |        |      |                                                                                |
|-----------------------|--------|------|--------------------------------------------------------------------------------|
| Re                    | 6.43   | Ohm  | electrical voice coil resistance at DC                                         |
| Le                    | 0.042  | mH   | frequency independent part of voice coil inductance                            |
| L2                    | 0.299  | mH   | para-inductance of voice coil                                                  |
| R2                    | 2.53   | Ohm  | electrical resistance due to eddy current losses                               |
| Cmes                  | 170    | µF   | electrical capacitance representing moving mass                                |
| Lces                  | 12.96  | mH   | electrical inductance representing driver compliance                           |
| Res                   | 23.69  | Ohm  | resistance due to mechanical losses                                            |
| fs                    | 107.2  | Hz   | driver resonance frequency                                                     |
| Mechanical Parameters |        |      |                                                                                |
| (using test encl.)    |        |      |                                                                                |
| Mms                   | 2.979  | g    | mechanical mass of driver diaphragm assembly including air load and voice coil |
| Mmd (Sd)              | 2.898  | g    | mechanical mass of voice coil and diaphragm without air load                   |
| Rms                   | 0.739  | kg/s | mechanical resistance of  total-driver losses                                  |
| Cms                   | 0.74   | mm/N | mechanical compliance of driver suspension                                     |
| Kms                   | 1.35   | N/mm | mechanical stiffness of driver suspension                                      |
| Bl                    | 4.185  | N/A  | force factor (Bl product)                                                      |
| Loss factors          |        |      |                                                                                |
| Qtp                   | 0.581  |      | total Q-factor considering all losses                                          |
| Qms                   | 2.714  |      | mechanical Q-factor of driver in free air considering Rms only                 |
| Qes                   | 0.737  |      | electrical Q-factor of driver in free air considering Re only                  |
| Qts                   | 0.579  |      | total Q-factor considering Re and Rms only                                     |
| Other Parameters      |        |      |                                                                                |
| Vas                   | 0.7827 | l    | equivalent air volume of suspension                                            |
| n0                    | 0.126  | %    | reference efficiency (2 pi-radiation using Re)                                 |
| Lm                    | 83.2   | dB   | characteristic sound pressure level (SPL at 1m for 1W @ Re)                    |
| Lnom                  | 81.14  | dB   | nominal sensitivity (SPL at 1m for 1W @ Zn)                                    |
| Sd                    | 27.34  | cm²  | diaphragm area                                                                 |

<br>


![](/images/Reviews/Drivers/Fountek/FR88EX/fr88ex-impedance.png)

<br>
<br>

## Large Signal Analysis from Klippel LSI Module

| Displacement Limits |      |    | thresholds can be changed in Processing property page |
|---------------------|------|----|-------------------------------------------------------|
| X Bl @ Bl min=82%   | >3.5 | mm | Displacement limit due to force factor variation      |
| X C @ C min=75%     | 2.4  | mm | Displacement limit due to compliance variation        |
| X L @ Z max=10 %    | >3.5 | mm | Displacement limit due to inductance variation        |
| X d @ d2=10%        | 9.6  | mm | Displacement limit due to IM distortion (Doppler)     |

<br>


![](/images/Reviews/Drivers/Fountek/FR88EX/fr88ex-img_Bl-X.png)

![](/images/Reviews/Drivers/Fountek/FR88EX/fr88ex-img_Bl-Symmetry-fr88ex-Range.png)

![](/images/Reviews/Drivers/Fountek/FR88EX/fr88ex-img_Kms-X.png)

![](/images/Reviews/Drivers/Fountek/FR88EX/img_Kms-Symmetry-fr88ex-Range.png)

![](/images/Reviews/Drivers/Fountek/FR88EX/fr88ex-img_LX.png)

![](/images/Reviews/Drivers/Fountek/FR88EX/fr88ex-img_LI.png)



<br>
<br>

## Frequency Response

On-Axis merged at approximately 500hz, representing 2.83v/1m.  1/24 octave scaling.

![](/images/Reviews/Drivers/Fountek/FR88EX/Fountek-FR88EX-0-deg-merged.png)

Response comparison at 0, 30, and 60 degrees.  1/24 Octave resolution.

![](/images/Reviews/Drivers/Fountek/FR88EX/Fountek-FR88EX-Frequency-Response-0-30-60.png)


<br>
<br>

## Harmonic Distortion

Note:  This test was performed in the farfield, and subsequent to environmental issues such as reflections and noise. Therefore, fundamental response below 200hz is not provided here.

96dB/1m

![](/images/Reviews/Drivers/Fountek/FR88EX/Fundamental--Harmonic-distortion-components-96dB1m.png)

![](/images/Reviews/Drivers/Fountek/FR88EX/Relative-Harmonic-distortion-96dB1m.png)


<br>

## Wrap-Up

Senstivity is rather low, in the low-to-mid 80's.  But that's kind of expected out of a "fullrange" where sensitivity is sacrificed for linear excursion and high frequency extension.
Increasing distortion levels at 96dB/1m equivalent below 300hz; use a proper crossover here to limit excursion and take some load off the voice coil so it doesn't saturate and thusly become "compressed" (compressed = when the voice coil can't expend heat and therefore as you increase the volume, the output level stops increasing and instead you lose volume).
A few problematic distortion spikes but given their narrow band I can't say how audible they would be without purposely listening to this speaker with test tones.
IMD (intermodulated distortion) should be helped with the use of the inductance limiting shorting ring as evidenced by the symmetrical Le(x) plots.
Frequenccy response is wrought with a lot of little things that concern me (e.g., multiple ups and downs from 100-1kHz, sharp dip at ~1600hz and the subsequent THD spike there, and the strong differences in on/off-axis response above 10khz (which kind of defeats the purpose of using a fullrange)).

Of course, one could simply use this as a dedicated midrange in a 3-way - maybe 300hz to 4khz - and for the price it might be worth that.  But the low sensitivity still is a limiting factor.

Fundamentally, I'm not a proponent of fullrange or wideband drivers.  I just prefer to use a 3-way than deal with the shortcomings of most fullranges; shortcomings being: low sensitivity, breakup issues outside of beaming that can't be EQ'd or otherwise corrected via DSP.
But if you have a need for one or want to experiment, this might be worth playing with since it's pretty cheap, though, consider my comments above.

<br>
<br>

## End

If you like what you see here and want to help me keep it going, there’s a Paypal Contribute button at the bottom of each page.  Just provide what you can.  Every little bit is truly appreciated.

You can also join my Facebook and YouTube pages via the links at the bottom of the page if you'd like to follow along with updates.

<br>Thanks!</b>

![](https://s3media.247sports.com/Uploads/Assets/475/557/9557475.gif)


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
