---
title: "Kef Q100 Speaker Drive Unit Testing"
date: 2020-01-25T15:07:35-06:00
draft: false
image_webp: images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.webp
image: images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.jpg
description : "Kef Q100"
---

## <center> **Kef Q100 Speaker Drive Unit Testing** </center>

As with the [Kef HTS3001SE I tested](), I ordered a set of the Kef Q100 Bookshelf speakers in order to remove and review the raw Q100 driver itself.  I really wanted to see how this coaxial design performed.  Zaph had already tested this one but I wanted to do Klippel LSI testing on it to see how the suspension performed.  He actually mentioned this in his writeup and I thought it would be cool to provide the results.  Of course, since I had it on the test baffle I did some other standard measurements as well.  The one I was interested in, but didn’t perform on the HTS3001SE driver was tweeter frequency response performance with movement of the woofer.  I don’t necessarily have an easy way to test this so I did something a bit different: I used a 9v battery to statically ‘fix’ the woofer either in the coil out or coil in position and measured the response.  I then compared this to the woofer at rest performance of the tweeter and did a direct comparison.  This is discussed further below.

On to the testing…



Up first, obligatory pictures:


![kefq100 pic 1](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5288.jpg)

![kefq100 pic 2](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5289.jpg)

![kefq100 pic 3](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5290.jpg)

![kefq100 pic 4](/images/Reviews/Drivers/Kef/Q100_Driver/IMG_5291.jpg)


This driver is quite the little beast. A very large motor and pretty substantial surround make this one of the largest 5.25″ drivers I’ve personally seen.  Although I didn’t weigh it, it is fairly heavy due to the woofer’s ferrite magnet as opposed to neodymium.  This results in large and heavy.  I can’t exactly measure the voice coil but comparing it to the tweeter assembly, it appears to be a few mm larger in radius so I’d estimate VC diameter at roughly 55mm.  It is best to rear mount this driver given the very tall surround at approximately 12mm, but for the purpose of my test I front mounted it.

If you look at the ‘Tangerine’ waveguide/lens/whatever you want to call it, you’ll notice there’s actually a phase plug on the tweeter.  The HTS3001SE does not have this.

For those who want to read about the Tangerine waveguide, [click this link (PDF format)](http://forum.vegalab.ru/attachment.php?attachmentid=86280&d=1274426702).  There’s also discussion on the radial ribbing of the other Uni-Q cones, which this driver doesn’t employ.

#### <center> **Raw Driver Physical Measurements** </center>

First off, given this isn’t sold as an individual driver, I have taken my own measurements.  These are rough measurements taken with my not-so-recently calibrated calipers, but should be good within +/-1mm.

|                                       Dimension                                       |  mm  |
|:-------------------------------------------------------------------------------------:|:----:|
|                                     Outer Diameter                                    |  143 |
|                                   Mounting Diameter                                   |  120 |
|                                     Mounting Depth                                    |  83  |
|                               Effective Piston Diameter*                              |  109 |
|                              Effective Piston Diameter**                              |  60  |
|                                    Flange Thickness                                   | 0.34 |
|                                 Mounting Tab Thickness                                | 0.65 |
| *Half surround to half surround; including space consumed by coincident tweeter.      |      |
| **Half surround to half surround; NOT including space consumed by coincident tweeter. |      |

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#ccc;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:5px 0px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#ccc;color:#333;background-color:#fff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:5px 0px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#ccc;color:#333;background-color:#f0f0f0;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-abip{background-color:#f9f9f9;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-btxf{background-color:#f9f9f9;border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-c3ow">Dimension</th>
    <th class="tg-c3ow">mm</th>
  </tr>
  <tr>
    <td class="tg-c3ow">Outer Diameter</td>
    <td class="tg-abip">143</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Mounting Diameter</td>
    <td class="tg-abip">120</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Mounting Depth</td>
    <td class="tg-abip">83</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Effective Piston Diameter*</td>
    <td class="tg-abip">109</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Effective Piston Diameter**</td>
    <td class="tg-abip">60</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Flange Thickness</td>
    <td class="tg-abip">0.34</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Mounting Tab Thickness</td>
    <td class="tg-abip">0.65</td>
  </tr>
  <tr>
    <td class="tg-0pky">*Half surround to half surround; including space consumed by coincident tweeter.</td>
    <td class="tg-btxf"></td>
  </tr>
  <tr>
    <td class="tg-0pky">**Half surround to half surround; NOT including space consumed by coincident tweeter.</td>
    <td class="tg-btxf"></td>
  </tr>
</table>
