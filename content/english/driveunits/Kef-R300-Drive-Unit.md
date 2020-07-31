---
title: "Kef R300 Speaker Drive Unit Testing"
date: 2013-02-02
draft: false
image: images/Reviews/Drivers/Kef/R300_Driver/IMG_5482.jpg
description : "Kef R300"
Tags: ["Kef", "R300", "Tangerine", "waveguide", "R300"]
---
<iframe src="//rcm-na.amazon-adsystem.com/e/cm?o=1&p=48&l=ur1&category=amazonhomepage&f=ifr&linkID=45d00811e11005f66cf1dcae88dc3060&t=medlemusin-20&tracking_id=medlemusin-20" width="728" height="90" scrolling="no" border="0" marginwidth="0" style="border:none;" frameborder="0"></iframe>
<br clear="all" />
<br>
<br>
<br>

By now you’ve probably seen my testing of the [Kef Q100](https://www.erinsaudiocorner.com/driveunits/kef-q100-drive-unit/) drive unit.  I had read the next step in the Kef Uni-Q line are the drivers in the “R” series.  So, a fella let me borrow the 5 inch midrange drive unit from the R300 speaker to test.  The R300 comes with a separate woofer but I was not sent this.  The only way to obtain these drivers individually is to purchase the speakers they come with (such as the R300 or R500 speaker) and remove them.  Which brings up something worth noting: I am testing these raw drivers as more or less for knowledge purposes.  These kind of tests tell us exactly what the basis for a speaker is (drive units + enclosure + circuit design).  If Kef is starting with a great drive unit then one can logically assume they have likewise extended efforts to use them as a speaker component in a manner which reflects their ‘raw’ performance.  In other words, if the drive unit design is great, odds are so is the complete speaker it’s used in.  Now, let’s get on with it!

![kefR300](/images/Reviews/Drivers/Kef/R300_Driver/IMG_5482.jpg)

![kefR300](/images/Reviews/Drivers/Kef/R300_Driver/IMG_5488.jpg)

![kefR300](/images/Reviews/Drivers/Kef/R300_Driver/IMG_5493.jpg)


Like the Q100, this driver has a very large motor structure and basket.  For a midrange, this is a HUGE drive unit, relative to other mids I’ve used.  You’ll also notice the motor and frame are a bolt-together design.  The spider is below the cone on a tier sitting above where conventional speakers’ spiders are.  The surround of this driver has a curved shape to it, I assume to help it act more like a waveguide as with the cone’s shape.  The voice coil diameter is roughly 45-47mm (I had to spitball this so please take it as only an estimate).  OD is approximately 130mm.  Surface area (minus the tweeter assembly/waveguide) is about 98.01cm².  Actual effective surface area, noting the moving portion of the driver’s cone is 25cm²; the tweeter housing/waveguide is roughly 49mm in diameter.

<br>

#### Test Results

To make things a bit easier to manage, I’ve broken down the test results in to two sections:

1. Tweeter Testing
2. Midrange Testing

#### Part I: Tweeter Testing
##### Tweeter Thiele-Small Parameters and Impedance

| Electrical Parameters |       |     |                                                                |
|-----------------------|-------|-----|----------------------------------------------------------------|
| Re                    | 2.92  | Ohm | electrical voice coil resistance at DC                         |
| Le                    | 0.012 | mH  | frequency independent part of voice coil inductance            |
| L2                    | 0.011 | mH  | para-inductance of voice coil                                  |
| R2                    | 0.34  | Ohm | electrical resistance due to eddy current losses               |
| Cmes                  | 120   | µF  | electrical capacitance representing moving mass                |
| Lces                  | 0.26  | mH  | electrical inductance representing driver compliance           |
| Res                   | 0.94  | Ohm | resistance due to mechanical losses                            |
| fs                    | 907.9 | Hz  | driver resonance frequency                                     |
| Loss factors          |       |     |                                                                |
| Qtp                   | 0.488 |     | total Q-factor considering all losses                          |
| Qms                   | 0.644 |     | mechanical Q-factor of driver in free air considering Rms only |
| Qes                   | 2.005 |     | electrical Q-factor of driver in free air considering Re only  |
| Qts                   | 0.487 |     | total Q-factor considering Re and Rms only                     |

<br>

![kefR300 tweeterimp](/images/Reviews/Drivers/Kef/R300_Driver/tweeter-imp.png)


<br>

##### Tweeter Frequency Response
0, 30, and 60 degrees.  2.83v/1m; Nearfield & Farfield merged at 1800hz.
<br>**Note:** When testing a driver like this, where the waveguide effect is of high importance, it is necessary to make sure all transitions from tweeter to cone to baffle are as smooth as possible.  In the case of this driver, a trim ring is attached to the flange to smooth the transition between it and the baffle.  I did not have this trim ring nor was the drive unit flush mounted on my test baffle.  This mounting effects the high frequency linearity; likely causing the on-axis dip at ~8kHz.


<br>

![kefR300 FRTWEETER](/images/Reviews/Drivers/Kef/R300_Driver/Kef-R300-Drive-Unit-Tweeter-Frequency-Response-0-30-60.png)

<br>

##### Tweeter Harmonic Distortion
<br> Harmonic Distortion below given at 90dB/1m and 96dB/1m equivalents.
![kefR300 FRHDTWEETER90](/images/Reviews/Drivers/Kef/R300_Driver/kef-r300-tweeter-Fundamental--Harmonic-distortion-components-90dB1m.png)
<br>
![kefR300 FRHDTWEETER96](/images/Reviews/Drivers/Kef/R300_Driver/r300-tweeter-Fundamental--Harmonic-distortion-components-96dB1m.png)
<br>


#### Part II: Midrange Testing
##### Midrange Thiele-Small Parameters and Impedance

Note:  When determining the full suite of T/S parameters, the effective diameter of the driver is needed to calculate Vas, Bl, etc.  Most of the time this can simply be measured by measuring the diameter of the driver from half-surround to half-surround since the motor must control the entire cone area.  However, in this case, the entire cone does not move.  Therefore, the effective diameter (and resulting Sd) is not the entire diameter of the driver.  The effective diameter here is determined by subtracting the static tweeter assembly from the overall effective diameter of the woofer.  See physical measurements section above for all values.

| Electrical Parameters |        |      |                                                                                |
|-----------------------|--------|------|--------------------------------------------------------------------------------|
| Re                    | 3.08   | Ohm  | electrical voice coil resistance at DC                                         |
| Le                    | 0.155  | mH   | frequency independent part of voice coil inductance                            |
| L2                    | 0.234  | mH   | para-inductance of voice coil                                                  |
| R2                    | 1.77   | Ohm  | electrical resistance due to eddy current losses                               |
| Cmes                  | 242    | µF   | electrical capacitance representing moving mass                                |
| Lces                  | 3.63   | mH   | electrical inductance representing driver compliance                           |
| Res                   | 9.29   | Ohm  | resistance due to mechanical losses                                            |
| fs                    | 169.5  | Hz   | driver resonance frequency                                                     |
| Mechanical Parameters |        |      |                                                                                |
| (using add. mass)     |        |      |                                                                                |
| Mms                   | 7.416  | g    | mechanical mass of driver diaphragm assembly including air load and voice coil |
| Mmd (Sd)              | 6.9    | g    | mechanical mass of voice coil and diaphragm without air load                   |
| Rms                   | 3.293  | kg/s | mechanical resistance of  total-driver losses                                  |
| Cms                   | 0.119  | mm/N | mechanical compliance of driver suspension                                     |
| Kms                   | 8.41   | N/mm | mechanical stiffness of driver suspension                                      |
| Bl                    | 5.531  | N/A  | force factor (Bl product)                                                      |
| Loss factors          |        |      |                                                                                |
| Qtp                   | 0.603  |      | total Q-factor considering all losses                                          |
| Qms                   | 2.399  |      | mechanical Q-factor of driver in free air considering Rms only                 |
| Qes                   | 0.796  |      | electrical Q-factor of driver in free air considering Re only                  |
| Qts                   | 0.598  |      | total Q-factor considering Re and Rms only                                     |
| Other Parameters      |        |      |                                                                                |
| Vas                   | 0.5905 | l    | equivalent air volume of suspension                                            |
| n0                    | 0.348  | %    | reference efficiency (2 pi-radiation using Re)                                 |
| Lm                    | 87.61  | dB   | characteristic sound pressure level (SPL at 1m for 1W @ Re)                    |
| Lnom                  | 88.74  | dB   | nominal sensitivity (SPL at 1m for 1W @ Zn)                                    |
| Sd                    | 59.26  | cm²  | diaphragm area                                                                 |

<br>

![kefR300 imp](/images/Reviews/Drivers/Kef/R300_Driver/woofer-imp.png)

<br>

It may be pretty obvious that I wasn’t able to resolve all the values below. The limiting suspension resolves first at 1.5mm linear xmax, and to resolve Bl and L(x) would mean pushing on the driver harder than I am comfortable with. Suffice it to say, a high pass filter will help lessen the suspension related distortion, but *most importantly* this driver isn’t intended to cover bass frequencies, nor should it as ideally the 'midrange as a waveguide' should restrict movement as to not cause aberrations in the frequency response.  If memory serves, it’s crossed above 500hz in the R-series towers where it is accompanied by a midwoofer.  So, the excursion related data below is really only for the sake of it.

| Displacement Limits |      |    | thresholds can be changed in Processing property page |
|---------------------|------|----|-------------------------------------------------------|
| X Bl @ Bl min=82%   | >2.5 | mm | Displacement limit due to force factor variation      |
| X C @ C min=75%     | 1.5  | mm | Displacement limit due to compliance variation        |
| X L @ Z max=10 %    | >2.5 | mm | Displacement limit due to inductance variation        |
| X d @ d2=10%        | 7    | mm | Displacement limit due to IM distortion (Doppler)     |

<br></br>
![kefR300 bl](/images/Reviews/Drivers/Kef/R300_Driver/Force-factor-Bl-X.png)
<br></br>
![kefR300 bl-sym](/images/Reviews/Drivers/Kef/R300_Driver/Bl-Symmetry-Range.png)
<br></br>
![kefR300 cms](/images/Reviews/Drivers/Kef/R300_Driver/Mechanical-compliance-Cms-X.png)
<br></br>
![kefR300 kms](/images/Reviews/Drivers/Kef/R300_Driver/Stiffness-of-suspension-Kms-X.png)
<br></br>
![kefR300 kms-sym](/images/Reviews/Drivers/Kef/R300_Driver/Kms-Symmetry-Range.png)
<br></br>
![kefR300 indx](/images/Reviews/Drivers/Kef/R300_Driver/Electrical-inductance-LX-I0.png)
<br></br>
![kefR300 indi](/images/Reviews/Drivers/Kef/R300_Driver/Inductance-over-current-LX0-I.png)

<br>

##### Woofer Frequency Response
Measured at 2.83v/1m.  Stitched with a nearfield measurement at approximately 500hz.
<br>**Note:** Due to the rather tall surround and the fact I don’t have the trim ring used to flush mount the driver in a baffle, this driver was not flush mounted.  This will effect the high frequency response to some degree.


![kefR300 FR03060WOOFER](/images/Reviews/Drivers/Kef/R300_Driver/Kef-R300-Drive-Unit-Woofer-Frequency-Response-0-30-60.png)

<br>

##### Woofer Harmonic Distortion
<br></br>
Harmonic Distortion below given at 90dB/1m and 96dB/1m equivalents.
<br></br>

![kefR300 FRHDWOOFER90](/images/Reviews/Drivers/Kef/R300_Driver/kef-r300-woofer-Fundamental--Harmonic-distortion-components-90dB1m.png)
<br></br>


![kefR300 FRHDWOOFER96](/images/Reviews/Drivers/Kef/R300_Driver/kef-r300-woofer-Fundamental--Harmonic-distortion-components-96dB1m.png)

<br>


#### Miscellaneous Testing

I took some time to do a bit of additional testing with this driver just for fun using [Room EQ Wizard (REW) software](https://www.roomeqwizard.com/) and my calibrated mic.

I used an active crossover with a 3khz/LR2 targeted crossover point between the mid and tweeter.  I then measured the driver at 0, 30, 45, 60, and 90 degrees to see how the response of the driver with this crossover applied measures in all angles.  The results are overlaid below in 1/12 resolution.

NOTE:  SPL was not measured with the standard 2.83v/1m criteria in the following graphics.
<br></br>
![kefR300 FRHDWOOFER96](/images/Reviews/Drivers/Kef/R300_Driver/drive-unit-sound-power.png)

<br></br>

Now, average them together for a single plot average of all the above points:
<br></br>
![kefR300 FRHDWOOFER96](/images/Reviews/Drivers/Kef/R300_Driver/drive-unit-average.png)

<br></br>
Another bit of testing I did was to see how the midrange out-of-band peak between 5-6khz could be tamed.  So, I applied some DSP correction and did a comparison.  The result below is a measurement of the raw woofer response vs the EQ’d response taken on axis (0 degrees).

This isn’t to say it’s needed.  It’s just something I did because I had some time and thought I’d share.
<br></br>
![kefR300 FRHDWOOFER96](/images/Reviews/Drivers/Kef/R300_Driver/r300-woofer-raw-vs-eq.png)

<br>

##### Impulse Response Note

Being this is called a coincident driver and the benefit of these are they are supposed to emanate sound from the point in space *and* time, I measured the tweeter and midrange drive units separately and evaluated the arrival of the impulse response.  The two impulse response lined up to a ‘T’.  Unfortunately, I didn’t save this measurement because I simply forgot to before I had to shut down the computer so am unable to post the results

<br></br>
### Parting Thoughts
The benefit of having a coincident design is excellent.  I’ve toyed with a few here and there, though, I felt the companies’ never quite got it right.  So, when I first started testing the Kef drive units I didn’t expect much, to be honest.  However, the previous Kef Uni-Q units I’ve tested (HTS3001SE & Q100) have proven to be very well designed (within their target price contraints).  My results for the R300 drive unit show the same standard of performance.  I took the time to listen to these along with the Q100 speakers I have and must say that I am now sold on Kef’s coincident driver engineering.  I was extremely impressed by these (two) drive units’ performance in my listening tests.  People tend to get caught up in subjective ‘analysis’ whereas I fall in to a very objective analyzer category.  I tend to ignore subjective reviews in whole and often advise others to use them lightly, unless there is objective data to correlate.  This is why it’s rare I comment on the sound of a speaker/driver.  But, I can unequivocally say, after about 3 weeks of listening to these R-series mids and the Q100 speakers – against my coveted DIY speakers and countless other drive units – these truly are the best drive units I’ve laid ears on in regards to the "space" they provide to recordings when called for.  And, for the price, the Q100 speaker is what I would consider an excellent value for the critical listener on a low budget.


<br></br>


### End

If you like what you see here and want to help me keep it going, there’s a Paypal Contribute button at the bottom of each page.  Just provide what you can.  Every little bit is truly appreciated.

You can also join my Facebook and YouTube pages via the links at the bottom of the page if you'd like to follow along with updates.

<br>Thanks!</b>
<br></br>


![excellent!](https://media1.giphy.com/media/l46CDHTqbmnGZyxKo/giphy.gif)



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
