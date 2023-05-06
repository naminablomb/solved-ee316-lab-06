Download Link: https://assignmentchef.com/product/solved-ee316-lab-06
<br>
<strong> Rectification </strong>

<strong>AC Signals, Transformers and Bridge Rectifiers</strong>

<h1>Purpose</h1>

The goal of this laboratory is to explore AC signals, transformers and diodes. You will learn different methods of reporting AC voltages and learn how transformers and diodes can be utilized to rectify sinusoidal signals.

<h1>Theoretical Background</h1>

<h2>AC Waveforms</h2>

Review the basics of AC waveform from your text book. Some basic information is given below.




The peak voltage is measured from zero (ground) reference to the maximum waveform amplitude. An even more typical way of reporting ac voltage is as the root-mean-squared (rms) voltage (V<sub>rms</sub>). You are probably familiar with rms voltages because this is typically how household voltages, and current, are reported. The rms voltage is defined by:







<em> </em>

The rms values of voltage and current are the most useful because they appear explicitly in power equations when analyzing AC circuits. Note the information that follows on transformers, diodes and the bridge rectifier is not meant to cover the complete theory on any of the devices. The goal here is to give the student a basic understanding of how the devices work and provide practice using the devices. A more complete theoretical development is left to the students’ course work.

<strong><em> </em></strong>

<h2>Transformer</h2>

A transformer is a device made of two or more coils which are deliberately coupled magnetically and obey Faraday’s Law of Induction. A transformer can be used to step up or down AC voltages and currents. The step up or step down process occurs due to an induced EMF in the output side of the transformer. The induced EMF is a direct result of the EMF in the input side of the transformer and magnetic coupling. The input side of the transformer is known as the primary, and the output side is known as the secondary. The schematic symbol of a transformer is shown in Figure 6.1.










Figure 6.1

Vp is the primary (input) voltage, Np is the number of turns of the primary coil, Vs is the secondary (output) voltage, and Ns is the number of turns of the secondary coil. If the secondary side is made up of two coils, the coils may be wound in the opposite direction of each other. This effectively allows for two different output voltages. One voltage between an end tap and the center tap, and one that is twice that output if the output is taken across the two end taps. Note the center tap is usually at ground reference. This is assuming both coils on the secondary side are equal in their turn number. There is no requirement that the turn number be the same, in many cases a transformer will provide many different output voltages due to different coil wrappings. The governing equations for an ideal transformer are

V<sub>s</sub>N<sub>p</sub> = V<sub>p</sub>N<sub>s</sub>




I<sub>s</sub>N<sub>s</sub> = I<sub>p</sub>N<sub>p</sub>

As an example, consider a V<sub>p</sub> = 10 V sinusoidal input, N<sub>p</sub> = 100, and N<sub>s</sub> = 50 then:




V<sub>s</sub> = (0.5)10Vpeak




V<sub>s</sub> = 5Vpeak




V<sub>s</sub> = 3.5Vrms

In this laboratory you will use a configuration of four diodes known as a full-wave bridge rectifier. The configuration will rectify or convert a sinusoidal input signal to a positive waveform. Once the waveform’s ripple frequency is eliminated with the addition of a capacitor, a dc level output can be achieved.

<strong><em> </em></strong>

<h2>DC Value of Full-wave Rectifier Output</h2>

An output voltage waveform that has passed through a bridge rectifier is shown in Figure

6.2.







Figure 6.2

The average value (DC value) of a rectified waveform is defined as







<h2>Ripple frequency</h2>

The ripple frequency arises from AC components in the rectified signal. If the period of the waveform in Figure 6.2 is <em>T<sub>ripple</sub></em>, then the ripple frequency is defined as:

<em>f</em><em><sub>ripple</sub></em> =<em>1/T</em><em>ripple</em>




<h1>Theoretical Analysis</h1>

For parts A, B, C, and D let R<sub>L</sub> = 10 kΩ and the turn ratio of the transformer be 10; that is N<sub>p</sub>/N<sub>s</sub> = 10. Assume V<sub>p</sub> = 120 V<sub>rms</sub>, and f = 60 Hz. Recall that V<sub>pp</sub> = 2 V<sub>p</sub>. Be sure to label your plots and include units.

<ul>

 <li>Referring to Figure 6.3.</li>

 <li>Draw the voltage waveform at node A for two cycles.</li>

 <li>Draw the voltage waveform at nodes C and D for two cycles.</li>

 <li>Determine the phase relationship between the voltages at A, C and D. The transformer is center tapped, so assume the two coils on the secondary side are equal in turn number and wound in opposite directions.</li>

</ul>

<em> </em>

Figure 6.3




<ul>

 <li>Referring to Figure 6.4, draw the output waveform V<sub>out</sub> for a few cycles. Identify the parts of the voltage waveform contributed by the voltages at nodes C and D.</li>

 <li>Calculate the DC value of V<sub>out</sub>.</li>

 <li>Calculate the ripple frequency of the output waveform V<sub>out</sub>. This circuit is a full wave rectifier. If the circuit were only a half wave rectifier, i.e. only one side of the signal makes it through, how would the ripple frequency change?</li>

</ul>

<strong> </strong>

Figure 6.4




<h1>Simulation</h1>

<ul>

 <li>For the simulation, you can use the transformer in the example or the TS_IDEAL transformer. If you use the TS_IDEAL set the primary coil inductance to 100 mH and the secondary coil inductance to 1 mH. Use a 120 V<sub>rms</sub> 60 Hz input.</li>

 <li>Connect your circuit as shown in Figure 6.3 using Multisim. Connect channels A and B of the oscilloscope to nodes A and C in the circuit. Simulate the circuit.</li>

 <li>Mark the primary and secondary peak voltages. Is your secondary voltage ten times less than the primary voltage? Comment on the phase relationship of these two waveforms.</li>

 <li>Measure the time period (T) of both waveforms. Verify that frequency (f) is very close to 60Hz.</li>

 <li>Connect Channel A of the oscilloscope to node D. Still keep channel B connected to node C. Mark the peak voltages. Are these waveforms in phase or out of phase? What does this imply about the transformer configuration?</li>

 <li>Connect your circuit as shown in Figure 6.4.</li>

 <li>Take the peak voltage reading from the oscilloscope. Calculate the value of V<sub>out</sub> (DC).</li>

 <li>Measure the period of the waveform. What is the value of the ripple frequency?</li>

 <li>Take the voltmeter reading (You should have the voltmeter set to DC mode). Compare this result to what you measured with the oscilloscope.</li>

</ul>

<h1>Laboratory Procedure</h1>

<ul>

 <li>Build the circuit as in Figure 6.3. Use the transformers provided by the lab instructor. Connect channel 1 and channel 2 of the oscilloscope at nodes C and D.</li>

 <li>Measure the V<sub>pp</sub> and frequency for the output.</li>

 <li>Calculate the peak and rms voltages.</li>

 <li>What is the phase relationship between the two waveforms?</li>

 <li>Set up your digital multimeter for an AC voltage measurement. Then measure the voltage at node C. What type of reading does your DMM display?</li>

 <li>Compare your results with those of the theoretical analysis and simulation.</li>

 <li>Connect your circuit as shown in Figure 6.4.</li>

 <li>Take the peak voltage reading from the oscilloscope. Calculate the value of V<sub>out</sub> (DC).</li>

 <li>Measure the period of the waveform. What is the value of the ripple frequency?</li>

 <li>Take the voltmeter reading (You should have the voltmeter set to DC mode). Compare this result to what you measured with the oscilloscope.</li>

</ul>

















