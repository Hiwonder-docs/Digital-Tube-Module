# 1. Digital Tube Module Manual

<img class="common_img" src="../_static/media/chapter_1/section_1/media/image2.png" style="width:300px" />

## 1.1 Digital Tube Module

### 1.1.1 Sensor Introduction

LED digital tube is a 4-digit red LED digital tube used to display numbers, decimal points and some special characters. It features a compact, user-friendly design for displaying sensor values like speed, time, score, temperature, and distance in robotics projects.

### 1.1.2 Working Principle

It has 4 digital tubes, each of which has 8 LED lights. By controlling these 8 lights, you can make a digital tube display numbers, decimal points and part of the letters.

<img class="common_img" src="../_static/media/chapter_1/section_1/media/image3.png" style="width:100px" />

## 1.2 Notice

1.  Do not exceed the rated voltage range during use.

2.  <span class="mark">Handle with care during use.</span>

## 1.3 Specifications

For more information, you may refer to "**[Digital tube sensor schematic](https://drive.google.com/drive/folders/1e4hyrV5j96fYs93Wj5IVg0-WDs9dq7Wf?usp=sharing)**"

### 1.3.1 Pin Instruction

<img class="common_img" src="../_static/media/chapter_1/section_1/media/image2.png" style="width:300px" />

| **Pin** | **Instruction** |
| :-----: | :-------------: |
|   5V    |   Power Input   |
|   GND   |     Ground      |
|   DIN   |   Data Input    |
|   CLK   |   Clock input   |

### 1.3.2 Specifications

<table class="docutils-nobg" border="1">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td colspan="2" style="text-align: center;">
<p><strong>Digital Tube Sensor</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Parameter</strong></p>
</td>
<td style="text-align: center;">
<p><strong>Specification</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Power Supply</strong></p>
</td>
<td style="text-align: center;">
<p><strong>DC 5V</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Communication</strong></p>
</td>
<td style="text-align: center;">
<p><strong>Dual Digital Control</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Indicator Light (PWR) Description</strong></p>
</td>
<td style="text-align: center;">
<p><strong>The PWR LED lights up when powered.</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Connector Type</strong></p>
</td>
<td style="text-align: center;">
<p><strong>5264-4AW</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Product Dimensions</strong></p>
</td>
<td style="text-align: center;">
<p><strong>50mmx20mm</strong></p>
</td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">
<p><strong>Modular installation, compatible with Lego series.</strong></p>
</td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">
<p><strong>Four red LEDs, each including a decimal point</strong></p>
</td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">
<p><strong>Adjustable display brightness</strong></p>
</td>
</tr>
</tbody>
</table>

### 1.3.3 Project Outcome

You can refer to the case tutorials and programs for different platforms in the same directory as this tutorial. This section will demonstrate the testing effect using Arduino IDE as an example.

By using the TM1640 chip to set the LED matrix in the four digital tubes to achieve the effect of displaying numbers, decimal points and some letters.

And the final effect of the digital tube is: "**1234**" are displayed on the four-digit digital tube.