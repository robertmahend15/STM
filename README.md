<h1>Constructing a Low-Cost Scanning Tunneling Microscope (STM)</h1>

[Home-Built STM — Daniel J. Berard's Reference Design](https://dberard.com/home-built-stm/)

<h2>Description</h2>

Collaborated with Ben Hudson on a low-cost scanning tunneling microscope for Berry College Physics Department. Our goal was to build an instrument for under $1,000 and use it to image the surfaces of graphite and gold. Ben focused on the mechanical scan head, and I was responsible for planning the assembly and integration of the control and measurement electronics.

The microscope applies a bias voltage between a sharp platinum-iridium tip and a conductive sample. When the tip is close enough to the surface, electrons tunnel across the gap and produce a small current. A preamplifier converts that current into a measurable voltage, and a Teensy 3.2 controller uses proportional-integral (PI) feedback to adjust the tip height. During a scan, the recorded height adjustments form a map of the sample surface.

<h2>Main Portfolio Points</h2>

<ul>
  <li>Authored the electronics proposal for integrating a Teensy 3.2 controller, a low-noise preamplifier, and a piezoelectric scan head.</li>
  <li>Traced the measurement and control signals through the 16-bit ADC and DAC, from digitizing the preamplifier output to generating the X, Y, and Z scanner signals and sample bias.</li>
  <li>Specified how the scan head and preamplifier would connect to the controller through a DB25 breakout board and ribbon cables.</li>
  <li>Planned to reduce electrical noise with a shielded, short preamplifier input connection and limit mechanical vibration with a passive isolation table.</li>
  <li>Documented the controller bring-up and scanning procedure using USB serial communication and Berard's C# application to configure scans and display data line by line.</li>
</ul>

<b>Skills:</b> Embedded Systems, Electronics Integration, Analog Signal Conditioning, Data Acquisition, PI Feedback Control, Piezoelectric Actuation, and Experimental Physics.
