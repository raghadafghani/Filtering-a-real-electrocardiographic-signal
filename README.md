# Filtering-a-real-electrocardiographic-signal
 given two files ECG1.xlsx and ECG2.xlsx which need to be low-pass and high-pass 
filtered for subsequent processing (peak detection and classification).
# Part 1. Data Visualization 
These data are recordings of actual cardiac electrical signals. They are sampled at 360 Hz.  

**1.1 Insert the real-time column for each signal.**

**1.2 Display each of these signals (reduce the width of the display lines for better readability).**  

**1.3 What filtering types are necessary to improve the readability of data and make automatic processing possible?**  

# Part 2. Filtering the ECG 
We will use two filters, the output of the high-pass filter is HP(n)
and the low pass is LP(n). The input is X(n).<br>


**2.1 The high-pass filter**<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/8739eb03-7ae3-40d4-becf-edc4bd5256e4" alt="Description of Image">
</p>
✓ Calculate its transfer function.<br>
✓ Find and plot the Frequency response.<br>
✓ Which family does it belong to (FIR, IIR)?<br>
✓ Apply this filter to the ECG1 and then ECG2 signal.<br>
✓ How to partially resolve the problems occurring at the start of the signal?<br>  

<br>

**2.2 The low-pass filter**<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/87ecc914-36fb-492c-b520-df3d34857be6" alt="Description of Image">
</p>

✓ Calculate its transfer function.<br>
✓ Find and plot the Frequency response.<br>
✓ Which family does it belong to?<br>
✓ Apply this filter to the ECG1 then the ECG2 signal.<br>


**2.3 Use the output of the high pass filter as the input of the low pass filter and display the 
result obtained for ECG1 and ECG2. Is there a difference if you reverse the filters?**
