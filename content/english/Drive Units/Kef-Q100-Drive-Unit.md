---
title: "Kef Q100 Speaker Drive Unit Testing"
date: 2013-01-13
draft: false
image_webp: images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.webp
image: images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.jpg
description : "Kef Q100"
Tags: ["Kef", "Q100", "Tangerine", "waveguide"]
---
<style>
body { color: white; }
h1 { text-decoration: underline; color: white; }
h2 { text-decoration: underline; color: white; }
h3 { text-decoration: underline; color: white; }
h4 { text-decoration: underline; color: white; }
h5 { text-decoration: underline; color: white; }
</style>

As with the [Kef HTS3001SE I tested](), I ordered a set of the Kef Q100 Bookshelf speakers in order to remove and review the raw Q100 driver itself.  I really wanted to see how this coaxial design performed.  Zaph had already tested this one but I wanted to do Klippel LSI testing on it to see how the suspension performed.  He actually mentioned this in his writeup and I thought it would be cool to provide the results.  Of course, since I had it on the test baffle I did some other standard measurements as well.  The one I was interested in, but didn’t perform on the HTS3001SE driver was tweeter frequency response performance with movement of the woofer.  I don’t necessarily have an easy way to test this so I did something a bit different: I used a 9v battery to statically ‘fix’ the woofer either in the coil out or coil in position and measured the response.  I then compared this to the woofer at rest performance of the tweeter and did a direct comparison.  This is discussed further below.

Let's get on to the testing, but first ... the obligatory pictures ...
<center>

![kefq100 pic 1](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.jpg)

![kefq100 pic 2](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5289.jpg)

![kefq100 pic 3](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5290.jpg)

![kefq100 pic 4](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5291.jpg)
</center>

<br></br>
This driver is quite the little beast. A very large motor and pretty substantial surround make this one of the largest 5.25″ drivers I’ve personally seen.  Although I didn’t weigh it, it is fairly heavy due to the woofer’s ferrite magnet as opposed to neodymium.  This results in large and heavy.  I can’t exactly measure the voice coil but comparing it to the tweeter assembly, it appears to be a few mm larger in radius so I’d estimate VC diameter at roughly 55mm.  It is best to rear mount this driver given the very tall surround at approximately 12mm, but for the purpose of my test I front mounted it.

If you look at the ‘Tangerine’ waveguide/lens/whatever you want to call it, you’ll notice there’s actually a phase plug on the tweeter.  The HTS3001SE does not have this.

For those who want to read about the Tangerine waveguide, [click this link (PDF format)](http://forum.vegalab.ru/attachment.php?attachmentid=86280&d=1274426702).  There’s also discussion on the radial ribbing of the other Uni-Q cones, which this driver doesn’t employ.

<br></br>
#### <center> **Raw Driver Physical Measurements** </center>

First off, given this isn’t sold as an individual driver, I have taken my own measurements.  These are rough measurements taken with my not-so-recently calibrated calipers, but should be good within +/-1mm.
<center>
  <style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#aabcfe;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:5px 0px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#669;background-color:#e8edff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:5px 0px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#039;background-color:#b9c9fe;}
.tg .tg-x028{font-weight:bold;background-color:#000000;color:#ffffff;border-color:#000000;text-align:center;vertical-align:top}
.tg .tg-1zis{color:#000000;border-color:#000000;text-align:center;vertical-align:top}
.tg .tg-pjk6{color:#000000;border-color:#000000;text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-x028">Dimension</th>
    <th class="tg-x028">mm</th>
  </tr>
  <tr>
    <td class="tg-1zis">Outer Diameter</td>
    <td class="tg-1zis">143</td>
  </tr>
  <tr>
    <td class="tg-1zis">Mounting Diameter</td>
    <td class="tg-1zis">120</td>
  </tr>
  <tr>
    <td class="tg-1zis">Mounting Depth</td>
    <td class="tg-1zis">83</td>
  </tr>
  <tr>
    <td class="tg-1zis">Effective Piston Diameter<sup>1</sup></td>
    <td class="tg-1zis">109</td>
  </tr>
  <tr>
    <td class="tg-1zis">Effective Piston Diameter<sup>2</sup></td>
    <td class="tg-1zis">60</td>
  </tr>
  <tr>
    <td class="tg-1zis">Flange Thickness</td>
    <td class="tg-1zis">0.34</td>
  </tr>
  <tr>
    <td class="tg-1zis">Mounting Tab Thickness</td>
    <td class="tg-1zis">0.65</td>
  </tr>
  <tr>
    <td class="tg-pjk6" colspan="2"> 1) Half surround to half surround; including space consumed by coincident tweeter. </td>
  </tr>
  <tr>
    <td class="tg-pjk6" colspan="2"> 2) Half surround to half surround; NOT including space consumed by coincident tweeter.</td>
  </tr>
</table>

</center>

<br></br>
#### <center> **Test Results** </center>

To make things a bit easier to manage, I’ve broken down the test results in to two sections:

1. Woofer Testing
2. Tweeter Testing

<br></br>

#### <center> **Part I: Woofer Testing** </center>
##### <center> **Woofer Thiele-Small Parameters and Impedance** </center>

Note:  When determining the full suite of T/S parameters, the effective diameter of the driver is needed to calculate Vas, Bl, etc.  Most of the time this can simply be measured by measuring the diameter of the driver from half-surround to half-surround since the motor must control the entire cone area.  However, in this case, the entire cone does not move.  Therefore, the effective diameter (and resulting Sd) is not the entire diameter of the driver.  The effective diameter here is determined by subtracting the static tweeter assembly from the overall effective diameter of the woofer.  See physical measurements section above for all values.

<br></br>
<center>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#aabcfe;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:5px 0px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#669;background-color:#e8edff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:5px 0px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#039;background-color:#b9c9fe;}
.tg .tg-x028{font-weight:bold;background-color:#000000;color:#ffffff;border-color:#000000;text-align:center;vertical-align:top}
.tg .tg-4ttr{background-color:#e8edff;color:#000000;border-color:#000000;text-align:left;vertical-align:top}
.tg .tg-9a8f{background-color:#e8edff;color:#000000;border-color:#000000;text-align:center;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-x028" colspan="4">Electrical Parameters</th>
  </tr>
  <tr>
    <td class="tg-9a8f">Re</td>
    <td class="tg-9a8f">3.09</td>
    <td class="tg-9a8f">Ohm</td>
    <td class="tg-9a8f">electrical voice coil resistance at DC</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Le</td>
    <td class="tg-9a8f">0.256</td>
    <td class="tg-9a8f">mH</td>
    <td class="tg-9a8f">frequency independent part of voice coil inductance</td>
  </tr>
  <tr>
    <td class="tg-9a8f">L2</td>
    <td class="tg-9a8f">0.427</td>
    <td class="tg-9a8f">mH</td>
    <td class="tg-9a8f">para-inductance of voice coil</td>
  </tr>
  <tr>
    <td class="tg-9a8f">R2</td>
    <td class="tg-9a8f">3.39</td>
    <td class="tg-9a8f">Ohm</td>
    <td class="tg-9a8f">electrical resistance due to eddy current losses</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Cmes</td>
    <td class="tg-9a8f">318</td>
    <td class="tg-9a8f">µF</td>
    <td class="tg-9a8f">electrical capacitance representing moving mass</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Lces</td>
    <td class="tg-9a8f">18.82</td>
    <td class="tg-9a8f">mH</td>
    <td class="tg-9a8f">electrical inductance representing driver compliance</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Res</td>
    <td class="tg-9a8f">29.82</td>
    <td class="tg-9a8f">Ohm</td>
    <td class="tg-9a8f">resistance due to mechanical losses</td>
  </tr>
  <tr>
    <td class="tg-9a8f">fs</td>
    <td class="tg-9a8f">65</td>
    <td class="tg-9a8f">Hz</td>
    <td class="tg-9a8f">driver resonance frequency</td>
  </tr>
  <tr>
    <td class="tg-x028" colspan="4">Mechanical Parameters</td>
  </tr>
  <tr>
    <td class="tg-4ttr" colspan="4">(using add. mass)</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Mms</td>
    <td class="tg-9a8f">12.834</td>
    <td class="tg-9a8f">g</td>
    <td class="tg-9a8f">mechanical mass of driver diaphragm assembly including air load and voice coil</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Mmd (Sd)</td>
    <td class="tg-9a8f">12.108</td>
    <td class="tg-9a8f">g</td>
    <td class="tg-9a8f">mechanical mass of voice coil and diaphragm without air load</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Rms</td>
    <td class="tg-9a8f">1.352</td>
    <td class="tg-9a8f">kg/s</td>
    <td class="tg-9a8f">mechanical resistance of  total-driver losses</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Cms</td>
    <td class="tg-9a8f">0.467</td>
    <td class="tg-9a8f">mm/N</td>
    <td class="tg-9a8f">mechanical compliance of driver suspension</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Kms</td>
    <td class="tg-9a8f">2.14</td>
    <td class="tg-9a8f">N/mm</td>
    <td class="tg-9a8f">mechanical stiffness of driver suspension</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Bl</td>
    <td class="tg-9a8f">6.35</td>
    <td class="tg-9a8f">N/A</td>
    <td class="tg-9a8f">force factor (Bl product)</td>
  </tr>
  <tr>
    <td class="tg-x028" colspan="4">Loss factors</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Qtp</td>
    <td class="tg-9a8f">0.365</td>
    <td class="tg-9a8f"></td>
    <td class="tg-9a8f">total Q-factor considering all losses</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Qms</td>
    <td class="tg-9a8f">3.878</td>
    <td class="tg-9a8f"></td>
    <td class="tg-9a8f">mechanical Q-factor of driver in free air considering Rms only</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Qes</td>
    <td class="tg-9a8f">0.402</td>
    <td class="tg-9a8f"></td>
    <td class="tg-9a8f">electrical Q-factor of driver in free air considering Re only</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Qts</td>
    <td class="tg-9a8f">0.364</td>
    <td class="tg-9a8f"></td>
    <td class="tg-9a8f">total Q-factor considering Re and Rms only</td>
  </tr>
  <tr>
    <td class="tg-x028" colspan="4">Other Parameters</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Vas</td>
    <td class="tg-9a8f">3.6615</td>
    <td class="tg-9a8f">l</td>
    <td class="tg-9a8f">equivalent air volume of suspension</td>
  </tr>
  <tr>
    <td class="tg-9a8f">n0</td>
    <td class="tg-9a8f">0.241</td>
    <td class="tg-9a8f">%</td>
    <td class="tg-9a8f">reference efficiency (2 pi-radiation using Re)</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Lm</td>
    <td class="tg-9a8f">86.02</td>
    <td class="tg-9a8f">dB</td>
    <td class="tg-9a8f">characteristic sound pressure level (SPL at 1m for 1W @ Re)</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Lnom</td>
    <td class="tg-9a8f">87.14</td>
    <td class="tg-9a8f">dB</td>
    <td class="tg-9a8f">nominal sensitivity (SPL at 1m for 1W @ Zn)</td>
  </tr>
  <tr>
    <td class="tg-9a8f">Sd</td>
    <td class="tg-9a8f">74.46</td>
    <td class="tg-9a8f">cm²</td>
    <td class="tg-9a8f">diaphragm area</td>
  </tr>
</table>

<br></br>

![kefq100 imp](/images/Reviews/Drivers/Kef/Q100_Driver/q100-impedance.png)

<br></br>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#aabcfe;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#669;background-color:#e8edff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#039;background-color:#b9c9fe;}
.tg .tg-x028{font-weight:bold;background-color:#000000;color:#ffffff;border-color:#000000;text-align:center;vertical-align:top}
.tg .tg-wp8o{border-color:#000000;text-align:center;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-x028" colspan="4">Woofer Large Signal Analysis with Klippel’s LSI Module</th>
  </tr>
  <tr>
    <td class="tg-wp8o">Displacement Limits</td>
    <td class="tg-wp8o"></td>
    <td class="tg-wp8o"></td>
    <td class="tg-wp8o">thresholds can be changed in Processing property page</td>
  </tr>
  <tr>
    <td class="tg-wp8o">X Bl @ Bl min=82%</td>
    <td class="tg-wp8o">&gt;4.2</td>
    <td class="tg-wp8o">mm</td>
    <td class="tg-wp8o">Displacement limit due to force factor variation</td>
  </tr>
  <tr>
    <td class="tg-wp8o">X C @ C min=75%</td>
    <td class="tg-wp8o">1.9</td>
    <td class="tg-wp8o">mm</td>
    <td class="tg-wp8o">Displacement limit due to compliance variation</td>
  </tr>
  <tr>
    <td class="tg-wp8o">X L @ Z max=10 %</td>
    <td class="tg-wp8o">2.8</td>
    <td class="tg-wp8o">mm</td>
    <td class="tg-wp8o">Displacement limit due to inductance variation</td>
  </tr>
  <tr>
    <td class="tg-wp8o">X d @ d2=10%</td>
    <td class="tg-wp8o">17.1</td>
    <td class="tg-wp8o">mm</td>
    <td class="tg-wp8o">Displacement limit due to IM distortion (Doppler)</td>
  </tr>
</table>

<br></br>
![kefq100 bl](/images/Reviews/Drivers/Kef/Q100_Driver/q100-bl.png)
<br></br>
![kefq100 bl-sym](/images/Reviews/Drivers/Kef/Q100_Driver/q100-bl-symmetry.png)
<br></br>
![kefq100 bl](/images/Reviews/Drivers/Kef/Q100_Driver/q100-bl.png)
<br></br>
![kefq100 kms-sym](/images/Reviews/Drivers/Kef/Q100_Driver/q100-kms-symmetry.png)
<br></br>
![kefq100 indx](/images/Reviews/Drivers/Kef/Q100_Driver/q100-le.png)
<br></br>
![kefq100 indi](/images/Reviews/Drivers/Kef/Q100_Driver/q100-li.png)

<br></br>
##### **Woofer Frequency Response** #####
</center>
Measured at 2.83v/1m.  Stitched with a nearfield measurement at approximately 500hz.

<center>

![kefq100 FR03060WOOFER](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Drive-Unit-Woofer-0-30-60.png)

<br></br>
##### **Woofer Harmonic Distortion** #####

![kefq100 FRHDWOOFER](/images/Reviews/Drivers/Kef/Q100_Driver/kef-q100-woofer-FR-HD-96dB.png)


<br></br>
<br></br>
#### **Part II: Tweeter Testing**
#####  **Small Signal Parameters**

<br></br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#aabcfe;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#669;background-color:#e8edff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aabcfe;color:#039;background-color:#b9c9fe;}
.tg .tg-x028{font-weight:bold;background-color:#000000;color:#ffffff;border-color:#000000;text-align:center;vertical-align:top}
.tg .tg-1zis{color:#000000;border-color:#000000;text-align:center;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-x028" colspan="4">Electrical Parameters</th>
  </tr>
  <tr>
    <td class="tg-1zis">Re</td>
    <td class="tg-1zis">2.84</td>
    <td class="tg-1zis">Ohm</td>
    <td class="tg-1zis">electrical voice coil resistance at DC</td>
  </tr>
  <tr>
    <td class="tg-1zis">Le</td>
    <td class="tg-1zis">0.018</td>
    <td class="tg-1zis">mH</td>
    <td class="tg-1zis">frequency independent part of voice coil inductance</td>
  </tr>
  <tr>
    <td class="tg-1zis">L2</td>
    <td class="tg-1zis">0.011</td>
    <td class="tg-1zis">mH</td>
    <td class="tg-1zis">para-inductance of voice coil</td>
  </tr>
  <tr>
    <td class="tg-1zis">R2</td>
    <td class="tg-1zis">0.5</td>
    <td class="tg-1zis">Ohm</td>
    <td class="tg-1zis">electrical resistance due to eddy current losses</td>
  </tr>
  <tr>
    <td class="tg-1zis">Cmes</td>
    <td class="tg-1zis">110</td>
    <td class="tg-1zis">µF</td>
    <td class="tg-1zis">electrical capacitance representing moving mass</td>
  </tr>
  <tr>
    <td class="tg-1zis">Lces</td>
    <td class="tg-1zis">0.28</td>
    <td class="tg-1zis">mH</td>
    <td class="tg-1zis">electrical inductance representing driver compliance</td>
  </tr>
  <tr>
    <td class="tg-1zis">Res</td>
    <td class="tg-1zis">1.09</td>
    <td class="tg-1zis">Ohm</td>
    <td class="tg-1zis">resistance due to mechanical losses</td>
  </tr>
  <tr>
    <td class="tg-1zis">fs</td>
    <td class="tg-1zis">902.6</td>
    <td class="tg-1zis">Hz</td>
    <td class="tg-1zis">driver resonance frequency</td>
  </tr>
  <tr>
    <td class="tg-x028" colspan="4">Loss factors</td>
  </tr>
  <tr>
    <td class="tg-1zis">Qtp</td>
    <td class="tg-1zis">0.491</td>
    <td class="tg-1zis"></td>
    <td class="tg-1zis">total Q-factor considering all losses</td>
  </tr>
  <tr>
    <td class="tg-1zis">Qms</td>
    <td class="tg-1zis">0.678</td>
    <td class="tg-1zis"></td>
    <td class="tg-1zis">mechanical Q-factor of driver in free air considering Rms only</td>
  </tr>
  <tr>
    <td class="tg-1zis">Qes</td>
    <td class="tg-1zis">1.769</td>
    <td class="tg-1zis"></td>
    <td class="tg-1zis">electrical Q-factor of driver in free air considering Re only</td>
  </tr>
  <tr>
    <td class="tg-1zis">Qts</td>
    <td class="tg-1zis">0.49</td>
    <td class="tg-1zis"></td>
    <td class="tg-1zis">total Q-factor considering Re and Rms only</td>
  </tr>
</table>

<br></br>
#####  **Tweeter Frequency Response**

![kefq100 FRTWEETER](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Drive-Unit-Tweeter-Only-0-30-60.png)
<br></br>
#####  **Tweeter Harmonic Distortion**
![kefq100 FRHDTWEETER](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Tweeter-FR-HD-96dB.png)
<br></br>
<br></br>

#####  **Tweeter Response vs Woofer Position**
</center>
I thought it would be interesting to see how the position of the woofer cone impacts the frequency response of the tweeter.  This matters when you’re listening to music and isn’t captured by a standard sine sweep.  To measure this performance I simply connected a 9v battery to the woofer’s terminals in positive polarity, then negative polarity which resulted in an approximate +/-3mm shift in cone direction.  I ran a sine sweep over the tweeter while the woofer was a) at rest, b) fixed out, and c) fixed in.  The pictures below show illustrate this.
<br></br>
Woofer at rest:
<br></br>
<center>

![kefq100 woofrest](/images/Reviews/Drivers/Kef/Q100_Driver/Q100-Woofer-At-Rest.jpg)
</center>



<br></br>

Woofer fixed out:
<br></br>
<center>

![kefq100 woofout](/images/Reviews/Drivers/Kef/Q100_Driver/Q100-Woofer-Out.jpg)
</center>



<br></br>
Woofer fixed in:
<br></br>
<center>

![kefq100 woofin](/images/Reviews/Drivers/Kef/Q100_Driver/Q100-Woofer-In.jpg)
</center>

<br></br>
The following results are of the three positions discussed above overlaid on one another.  The lines are labeled per the woofer position.
Note: The SPL level is not absolute here.  I performed the test at the same volume level throughout but it is not intended to reference any set test paraemter such as 2.83v/1m or 1w/1m.
<br></br>
![kefq100 disptweeter](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Drive-Unit-Woofer-Displacement-on-Tweeter-Response-Example.png)


<br></br>
<center>

  ###  **End**

</center>
<br></br>
<br></br>

If you like what you see here and want to help me keep it going or help me buy my wife some flowers so she doesn't beat me for spending all my time in the garage,
there’s a Paypal Contribute button at the bottom of each page.  Thanks!

![john_candy_ha](https://66.media.tumblr.com/42cea48d4c1e08498d509c685ab77a54/tumblr_o99hfoHe0C1qfr6udo1_500.gif)



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
