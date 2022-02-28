### What are Meshtastic-Antenna-Reports?

<p align=justify> Meshtastic Antenna Reports contain the results of basic usability testing performed on antennas that have been purchased for use with Meshtastic (www.meshtastic.org) hardware. A Microsoft Publisher template is provided for other community members that own (or otherwise have access to) a vector network analyzer and who wish to contribute by publishing the results of their own antenna testing.</p>

### 915MHz Test Results Summary
|Brand|Model|Antenna Type|Suggested For Use? (Y/N)|
|-------------|------------------|------------------|--------------|
|Linx|[ANT-916-CW-HW-SMA](PDFs/Linx%20ANT-916-CW-HW-SMA.pdf)|Omnidirectional Portable Antenna|:heavy_check_mark: Yes|
|Taosglas|[TI.92.2113](PDFs/Taosglas%20TI.92.2113.pdf)|Omnidirectional Portable Antenna|:heavy_check_mark: Yes|
|Seeed|[318020612](PDFs/Seeed%20318020612.pdf)|Omnidirectional Fixed Antenna|:x: No!|
|ARC Wireless|[ARC-PA0913C01](PDFs/ARC-PA0913C01.pdf)|Directional Fixed Antenna|:heavy_check_mark: Yes|

### Contribution Guidelines

When performing tests with the intent to contribute please follow these guidelines whenever possible / practical: 

* Perform SOLT calibration (short, open & load calibration) before performing tests.
* Perform your calibration with the coax cable attached that you will use for testing.
* Calibrate specifically for the frequency sweep you will be performing during the testing.
* Sweep beyond the ends of the frequency band
  * Example: 800-1000MHz for the US915 band
* Set markers at the start, center and end of the band
  * Example: 902MHz, 915MHz & 928MHz
* Utilize your VNA's "time averaging" and "trace smoothing" functionality
  * Suggested: Averaging of 4, Smoothing of 2
* Include the manufacturer and model number as the caption in your captured VSWR graph.
<br>
<p align=justify>Contributors are welcome to convert the provided template to their preferred editor format provided the overall theme / style of the report remains the same. If you do happen to convert the template to another format (OpenOffice, etc) then please submit the newly created template to the /Template directory for others to utilize also. </p>
<br>
<p>:warning:NanoVNA User Note:warning:</p>
<p>To make calibration / testing easier and to generate a cleaner final VSWR graph try using the <a href="http://github.com/OneOfEleven/NanoVNA-App">NanoVNA App</a>. A binary executable for Win32 is available under the Win32/Releases directory of that repository.</p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>

<p align=justify>Copyright / Trademark Notice: The Meshtastic logo is a registered trademark of Geeksville Industries, LLC. All other logos, brands, content, etc mentioned or used within Meshtastic Antenna Reports are copyright their respective owners. The reports contained herein are published under the GNU Public License (GPL) Version 3. </p>
