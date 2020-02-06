---
title: "Kef Q100 Speaker Drive Unit Testing"
date: 2013-01-13
draft: false
image_webp: images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.webp
image: images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.jpg
description : "Kef Q100"
Tags: ["Kef", "Q100", "Tangerine", "waveguide"]
---
As with the [Kef HTS3001SE I tested](), I ordered a set of the Kef Q100 Bookshelf speakers in order to remove and review the raw Q100 driver itself.  I really wanted to see how this coaxial design performed.  Zaph had already tested this one but I wanted to do Klippel LSI testing on it to see how the suspension performed.  He actually mentioned this in his writeup and I thought it would be cool to provide the results.  Of course, since I had it on the test baffle I did some other standard measurements as well.  The one I was interested in, but didn’t perform on the HTS3001SE driver was tweeter frequency response performance with movement of the woofer.  I don’t necessarily have an easy way to test this so I did something a bit different: I used a 9v battery to statically ‘fix’ the woofer either in the coil out or coil in position and measured the response.  I then compared this to the woofer at rest performance of the tweeter and did a direct comparison.  This is discussed further below.

Let's get on to the testing, but first ... the obligatory pictures ...

![kefq100](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.jpg)

![kefq100](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5289.jpg)

![kefq100](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5290.jpg)

![kefq100](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5291.jpg)

This driver is quite the little beast. A very large motor and pretty substantial surround make this one of the largest 5.25″ drivers I’ve personally seen.  Although I didn’t weigh it, it is fairly heavy due to the woofer’s ferrite magnet as opposed to neodymium.  This results in large and heavy.  I can’t exactly measure the voice coil but comparing it to the tweeter assembly, it appears to be a few mm larger in radius so I’d estimate VC diameter at roughly 55mm.  It is best to rear mount this driver given the very tall surround at approximately 12mm, but for the purpose of my test I front mounted it.

If you look at the ‘Tangerine’ waveguide/lens/whatever you want to call it, you’ll notice there’s actually a phase plug on the tweeter.  The HTS3001SE does not have this.

For those who want to read about the Tangerine waveguide, [click this link (PDF format)](http://forum.vegalab.ru/attachment.php?attachmentid=86280&d=1274426702).  There’s also discussion on the radial ribbing of the other Uni-Q cones, which this driver doesn’t employ.



<br></br>
#### Raw Driver Physical Measurements

First off, given this isn’t sold as an individual driver, I have taken my own measurements.  These are rough measurements taken with my not-so-recently calibrated calipers, but should be good within +/-1mm.

<table>
  <thead>
  <tr>
    <th>Dimension</th>
    <th>mm</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>Outer Diameter</td>
    <td>143</td>
  </tr>
  <tr>
    <td>Mounting Diameter</td>
    <td>120</td>
  </tr>
  <tr>
    <td>Mounting Depth</td>
    <td>83</td>
  </tr>
  <tr>
    <td>Effective Piston Diameter<sup>1</sup></td>
    <td>109</td>
  </tr>
  <tr>
    <td>Effective Piston Diameter<sup>2</sup></td>
    <td>60</td>
  </tr>
  <tr>
    <td>Flange Thickness</td>
    <td>0.34</td>
  </tr>
  <tr>
    <td>Mounting Tab Thickness</td>
    <td>0.65</td>
  </tr>
  <tr>
    <td colspan="2"> 1) Half surround to half surround; including space consumed by coincident tweeter. </td>
  </tr>
  <tr>
    <td colspan="2"> 2) Half surround to half surround; NOT including space consumed by coincident tweeter.</td>
  </tr>
  </tbody>
</table>

<br></br>
#### Test Results

To make things a bit easier to manage, I’ve broken down the test results in to two sections:

1. Woofer Testing
2. Tweeter Testing

#### Part I: Woofer Testing
##### Woofer Thiele-Small Parameters and Impedance

Note:  When determining the full suite of T/S parameters, the effective diameter of the driver is needed to calculate Vas, Bl, etc.  Most of the time this can simply be measured by measuring the diameter of the driver from half-surround to half-surround since the motor must control the entire cone area.  However, in this case, the entire cone does not move.  Therefore, the effective diameter (and resulting Sd) is not the entire diameter of the driver.  The effective diameter here is determined by subtracting the static tweeter assembly from the overall effective diameter of the woofer.  See physical measurements section above for all values.

<br></br>
<table>
  <thead>
  <tr>
    <th colspan="4">Electrical Parameters</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td >Re</td>
    <td >3.09</td>
    <td >Ohm</td>
    <td >electrical voice coil resistance at DC</td>
  </tr>
  <tr>
    <td >Le</td>
    <td >0.256</td>
    <td >mH</td>
    <td >frequency independent part of voice coil inductance</td>
  </tr>
  <tr>
    <td >L2</td>
    <td >0.427</td>
    <td >mH</td>
    <td >para-inductance of voice coil</td>
  </tr>
  <tr>
    <td >R2</td>
    <td >3.39</td>
    <td >Ohm</td>
    <td >electrical resistance due to eddy current losses</td>
  </tr>
  <tr>
    <td >Cmes</td>
    <td >318</td>
    <td >µF</td>
    <td >electrical capacitance representing moving mass</td>
  </tr>
  <tr>
    <td >Lces</td>
    <td >18.82</td>
    <td >mH</td>
    <td >electrical inductance representing driver compliance</td>
  </tr>
  <tr>
    <td >Res</td>
    <td >29.82</td>
    <td >Ohm</td>
    <td >resistance due to mechanical losses</td>
  </tr>
  <tr>
    <td >fs</td>
    <td >65</td>
    <td >Hz</td>
    <td >driver resonance frequency</td>
  </tr>
  </tbody>
  </table>

  <table>
  <thead>
  <tr>
    <th colspan="4">Mechanical Parameters</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td colspan="4">(using add. mass)</td>
  </tr>
  <tr>
    <td >Mms</td>
    <td >12.834</td>
    <td >g</td>
    <td >mechanical mass of driver diaphragm assembly including air load and voice coil</td>
  </tr>
  <tr>
    <td >Mmd (Sd)</td>
    <td >12.108</td>
    <td >g</td>
    <td >mechanical mass of voice coil and diaphragm without air load</td>
  </tr>
  <tr>
    <td >Rms</td>
    <td >1.352</td>
    <td >kg/s</td>
    <td >mechanical resistance of  total-driver losses</td>
  </tr>
  <tr>
    <td >Cms</td>
    <td >0.467</td>
    <td >mm/N</td>
    <td >mechanical compliance of driver suspension</td>
  </tr>
  <tr>
    <td >Kms</td>
    <td >2.14</td>
    <td >N/mm</td>
    <td >mechanical stiffness of driver suspension</td>
  </tr>
  <tr>
    <td >Bl</td>
    <td >6.35</td>
    <td >N/A</td>
    <td >force factor (Bl product)</td>
  </tr>
  </tbody>
  </table>

  <table>
  <thead>
  <tr>
    <th colspan="4">Loss factors</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td >Qtp</td>
    <td >0.365</td>
    <td ></td>
    <td >total Q-factor considering all losses</td>
  </tr>
  <tr>
    <td >Qms</td>
    <td >3.878</td>
    <td ></td>
    <td >mechanical Q-factor of driver in free air considering Rms only</td>
  </tr>
  <tr>
    <td >Qes</td>
    <td >0.402</td>
    <td ></td>
    <td >electrical Q-factor of driver in free air considering Re only</td>
  </tr>
  <tr>
    <td >Qts</td>
    <td >0.364</td>
    <td ></td>
    <td >total Q-factor considering Re and Rms only</td>
  </tr>
  </tbody>
  </table>

  <table>
  <thead>
  <tr>
    <th colspan="4">Other Parameters</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td >Vas</td>
    <td >3.6615</td>
    <td >l</td>
    <td >equivalent air volume of suspension</td>
  </tr>
  <tr>
    <td >n0</td>
    <td >0.241</td>
    <td >%</td>
    <td >reference efficiency (2 pi-radiation using Re)</td>
  </tr>
  <tr>
    <td >Lm</td>
    <td >86.02</td>
    <td >dB</td>
    <td >characteristic sound pressure level (SPL at 1m for 1W @ Re)</td>
  </tr>
  <tr>
    <td >Lnom</td>
    <td >87.14</td>
    <td >dB</td>
    <td >nominal sensitivity (SPL at 1m for 1W @ Zn)</td>
  </tr>
  <tr>
    <td >Sd</td>
    <td >74.46</td>
    <td >cm²</td>
    <td >diaphragm area</td>
  </tr>
  </tbody>
</table>
</center>

<br></br>

![kefq100 imp](/images/Reviews/Drivers/Kef/Q100_Driver/q100-impedance.png)

<br></br>

<table>
  <thead>
  <tr>
    <th colspan="4">Woofer Large Signal Analysis with Klippel’s LSI Module</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>Displacement Limits</td>
    <td></td>
    <td></td>
    <td>thresholds can be changed in Processing property page</td>
  </tr>
  <tr>
    <td>X Bl @ Bl min=82%</td>
    <td>&gt;4.2</td>
    <td>mm</td>
    <td>Displacement limit due to force factor variation</td>
  </tr>
  <tr>
    <td>X C @ C min=75%</td>
    <td>1.9</td>
    <td>mm</td>
    <td>Displacement limit due to compliance variation</td>
  </tr>
  <tr>
    <td>X L @ Z max=10 %</td>
    <td>2.8</td>
    <td>mm</td>
    <td>Displacement limit due to inductance variation</td>
  </tr>
  <tr>
    <td>X d @ d2=10%</td>
    <td>17.1</td>
    <td>mm</td>
    <td>Displacement limit due to IM distortion (Doppler)</td>
  </tr>
  </tbody>
</table>
</center>

<br></br>
![kefq100 bl](/images/Reviews/Drivers/Kef/Q100_Driver/q100-bl.png)
<br></br>
![kefq100 bl-sym](/images/Reviews/Drivers/Kef/Q100_Driver/q100-bl-symmetry.png)
<br></br>
![kefq100 kms-sym](/images/Reviews/Drivers/Kef/Q100_Driver/q100-kms-symmetry.png)
<br></br>
![kefq100 indx](/images/Reviews/Drivers/Kef/Q100_Driver/q100-le.png)
<br></br>
![kefq100 indi](/images/Reviews/Drivers/Kef/Q100_Driver/q100-li.png)

<br></br>
##### Woofer Frequency Response
Measured at 2.83v/1m.  Stitched with a nearfield measurement at approximately 500hz.

![kefq100 FR03060WOOFER](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Drive-Unit-Woofer-0-30-60.png)

<br></br>
##### Woofer Harmonic Distortion

![kefq100 FRHDWOOFER](/images/Reviews/Drivers/Kef/Q100_Driver/kef-q100-woofer-FR-HD-96dB.png)


#### Part II: Tweeter Testing
##### Small Signal Parameters

<center>
<br></br>
<table>
  <tr>
    <th colspan="4">Electrical Parameters</th>
  </tr>
  <tr>
    <td>Re</td>
    <td>2.84</td>
    <td>Ohm</td>
    <td>electrical voice coil resistance at DC</td>
  </tr>
  <tr>
    <td>Le</td>
    <td>0.018</td>
    <td>mH</td>
    <td>frequency independent part of voice coil inductance</td>
  </tr>
  <tr>
    <td>L2</td>
    <td>0.011</td>
    <td>mH</td>
    <td>para-inductance of voice coil</td>
  </tr>
  <tr>
    <td>R2</td>
    <td>0.5</td>
    <td>Ohm</td>
    <td>electrical resistance due to eddy current losses</td>
  </tr>
  <tr>
    <td>Cmes</td>
    <td>110</td>
    <td>µF</td>
    <td>electrical capacitance representing moving mass</td>
  </tr>
  <tr>
    <td>Lces</td>
    <td>0.28</td>
    <td>mH</td>
    <td>electrical inductance representing driver compliance</td>
  </tr>
  <tr>
    <td>Res</td>
    <td>1.09</td>
    <td>Ohm</td>
    <td>resistance due to mechanical losses</td>
  </tr>
  <tr>
    <td>fs</td>
    <td>902.6</td>
    <td>Hz</td>
    <td>driver resonance frequency</td>
  </tr>
  <tr>
    <td colspan="4">Loss factors</td>
  </tr>
  <tr>
    <td>Qtp</td>
    <td>0.491</td>
    <td></td>
    <td>total Q-factor considering all losses</td>
  </tr>
  <tr>
    <td>Qms</td>
    <td>0.678</td>
    <td></td>
    <td>mechanical Q-factor of driver in free air considering Rms only</td>
  </tr>
  <tr>
    <td>Qes</td>
    <td>1.769</td>
    <td></td>
    <td>electrical Q-factor of driver in free air considering Re only</td>
  </tr>
  <tr>
    <td>Qts</td>
    <td>0.49</td>
    <td></td>
    <td>total Q-factor considering Re and Rms only</td>
  </tr>
</table>
</center>

<br></br>
##### Tweeter Frequency Response

![kefq100 FRTWEETER](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Drive-Unit-Tweeter-Only-0-30-60.png)
<br></br>
##### Tweeter Harmonic Distortion
![kefq100 FRHDTWEETER](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Tweeter-FR-HD-96dB.png)
<br></br>
<br></br>

##### Tweeter Response vs Woofer Position
I thought it would be interesting to see how the position of the woofer cone impacts the frequency response of the tweeter.  This matters when you’re listening to music and isn’t captured by a standard sine sweep.  To measure this performance I simply connected a 9v battery to the woofer’s terminals in positive polarity, then negative polarity which resulted in an approximate +/-3mm shift in cone direction.  I ran a sine sweep over the tweeter while the woofer was a) at rest, b) fixed out, and c) fixed in.  The pictures below illustrate these different configurations.
<br></br>
Woofer at rest:

![kefq100 woofrest](/images/Reviews/Drivers/Kef/Q100_Driver/Q100-Woofer-At-Rest.jpg)

Woofer fixed out:

![kefq100 woofout](/images/Reviews/Drivers/Kef/Q100_Driver/Q100-Woofer-Out.jpg)


Woofer fixed in:
<br></br>
![kefq100 woofin](/images/Reviews/Drivers/Kef/Q100_Driver/Q100-Woofer-In.jpg)

The following results are of the three positions discussed above overlaid on one another.  The lines are labeled per the woofer position.
Note: The SPL level is not absolute here.  I performed the test at the same volume level throughout but it is not intended to reference any set test paraemter such as 2.83v/1m or 1w/1m.
<br></br>
![kefq100 disptweeter](/images/Reviews/Drivers/Kef/Q100_Driver/Kef-Q100-Drive-Unit-Woofer-Displacement-on-Tweeter-Response-Example.png)

### End

If you like what you see here and want to help me keep it going, there’s a Paypal Contribute button at the bottom of each page.  Just provide what you can.  Every little bit is truly appreciated.

<br>Thanks!</b>

![john_candy_ha](https://66.media.tumblr.com/42cea48d4c1e08498d509c685ab77a54/tumblr_o99hfoHe0C1qfr6udo1_500.gif)



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
