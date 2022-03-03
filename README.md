## What are Meshtastic Antenna Reports?

<p align=justify> Meshtastic Antenna Reports contain the results of basic usability testing performed on antennas that have been purchased by community members for use with Meshtastic (www.meshtastic.org) hardware. We provide these test results so that others can benefit from our testing when selecting an antenna for their project.<br><br>Templates are provided (MS Publisher 2016 & fillable Adobe Acrobat PDF formats) for other community members that own (or otherwise have access to) a vector network analyzer and who wish to contribute by publishing the results of their own antenna testing.</p>

## 915MHz Test Results Summary

#### Portable Antennas

| Brand        | Model                                                        | Antenna Dimensions     | Price (USD) | Suggested For Use? (Y/N) |
| ------------ | ------------------------------------------------------------ | ---------------------- | ----------- | ------------------- |
| Linx         | [ANT-916-CW-HW-SMA](PDFs/ANT-916-CW-HW-SMA.pdf)       | 120mm (L) x 9.25mm (W) | $9.89       | :heavy_check_mark: Yes   |
| Taoglas      | [TI.92.2113](PDFs/TI.92.2113.pdf)                  | 198mm (L) x 13mm (W)   | $8.09       | :heavy_check_mark: Yes   |
| Pulse Larsen | [W1063M](PDFs/W1063M.pdf)                       | 195mm (L) x 13mm (W)   | $7.04       | :heavy_check_mark: Yes   |
| Maxtena      | [Maxtena MEA-915-SW-SMA.pdf](PDFs/MEA-915-SW-SMA.pdf) | 113mm (L) x 9mm (W)    | $10.50      | :heavy_check_mark: Yes   |

#### Fixed (Base) Antennas

| Brand        | Model                                   | Antenna Dimensions               | Price (USD) | Suggested For Use? (Y/N) |
| ------------ | ------------------------------------------------------------ | ---------------------- | ----------- | ------------------- |
| Seeed        | [318020612](PDFs/318020612.pdf)   | 600mm (L) x 40mm (W)             | $35.00      | ❌ No!                    |
| ARC Wireless | [ARC-PA0913C01](PDFs/ARC-PA0913C01.pdf) | 389mm (L) x 389mm (W) x 31mm (D) | $37.50      | ✔️ Yes                    |

#### Vehicle Antennas

| Brand | Model                                       | Antenna Dimensions      | Price (USD) | Suggested For Use? (Y/N) |
| ------------ | ------------------------------------------------------------ | ---------------------- | ----------- | ------------------- |
| Laird | [TRA9020S3CBN](PDFs/TRA9020S3CBN.pdf) | 68.6mm (L) x 38.1mm (W) | $48.95      | ✔️ Yes                    |

## 433 / 860 / 863 / 868Mhz Test Results Summary

<p align=justify>No testing has been performed (or results submitted) for these frequency bands yet.</p>
<p align=justify>:warning:<B>WARNING</b>:warning: The Seeed Studio antenna (318020612) listed in the 915MHz Test Results Summary is being marketed as covering 860 - 930MHz. The antenna which was tested had a VSWR of over 8 : 1 in the area of 860MHz and <b>will</b> cause damage to hardware. (Update 18Feb2022 - Seeed Studio insists that the antenna should perform well throughout their suggested frequencies. They are providing a replacement antenna for testing. Until that testing is completed please don't risk using this antenna.)</p>

## Contribution Guidelines

When performing tests with the intent to contribute please follow these guidelines whenever possible / practical: 

1. Perform SOLT calibration (short, open & load calibration) before performing tests.
2. Perform your calibration with the coax cable attached that you will use for testing.
3. Calibrate specifically for the frequency sweep you will be performing during the testing.
4. Ensure no metal objects are within 2+ wavelengths of the antenna during testing.
> Example: 915MHz has a wavelength of 33cm or 1.057 feet. Keep metal objects >2ft away.
5. Sweep beyond the ends of the frequency band
> Example: 800-1000MHz for the US915 band
6. Set markers at the start, center and end of the band
> Example: 902MHz, 915MHz & 928MHz
7. Utilize your VNA's "time averaging" and "trace smoothing" functionality
> Suggested: Averaging of 4, Smoothing of 2
8. Include the manufacturer and model number as the caption in your captured VSWR graph.

<p align=justify>Contributors are welcome to convert the provided template to their preferred editor format provided the overall theme / style of the report remains the same. If you do happen to convert the template to another format (OpenOffice, etc) then please submit the newly created template to the /Templates directory for others to utilize also. </p>
<p align=justify>:large_blue_circle: <b>NanoVNA User Note</b> :large_blue_circle:<br> To make calibration / testing easier and to generate a cleaner final VSWR graph try using the <a href="http://github.com/OneOfEleven/NanoVNA-App">NanoVNA App</a>. A binary executable for Win32 is available under the Win32/Releases directory of that repository.</p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>

<p align=justify>Copyright / Trademark Notice: The Meshtastic logo is a registered trademark of Geeksville Industries, LLC. All other logos, brands, content, etc mentioned or used within Meshtastic Antenna Reports are copyright their respective owners. The reports contained herein are published under the GNU Public License (GPL) Version 3. </p>
