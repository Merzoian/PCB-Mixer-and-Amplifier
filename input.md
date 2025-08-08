**Overall** **System** **-** **Operation,** **Measurements,** **and**
**Lab** **Equipment**

Val Marogi

Jacob Lamb

Date 04/03/2025

ECEN 299

Objectives

The objective of this lab was to familiarize ourselves with various lab
equipment and measurement techniques needed for analyzing the
performance of a stereo amplifier system. We focused on measuring the
gain and frequency response of key components, including the buffer,
preamp, mixer, and treble/bass circuits. Additionally, we ensured that
the measurements obtained met the design specifications.

> Procedure Equipment and supplies
>
> • Function Generator • Oscilloscope
>
> • Stereo Amplifier System • Jumper Wires
>
> • Audio Jack • Microphone
>
> • Powered Speakers • DuPont Cables
>
> Procedure
>
> Measure Line Buffer Performance
>
> 1\. **Setup**: The Preamp & Mixer PCB and Treble & Bass PCB were
> removed, leaving only the Buffer PCB installed.
>
> 2\. **Connections**: A function generator was connected to the Buffer
> In pin, and an oscilloscope was used to measure both the input and
> output signals.
>
> 3\. **Measurements**: A 2V peak-to-peak sinusoidal signal was
> injected, and the oscilloscope recorded the output.
>
> 4\. **Results**: The gain was calculated using: A=Vout/Vin
>
> 5\. **Observation**: The buffer circuit was tested to ensure it
> provided unity gain, maintaining signal integrity while preventing
> loading effects from the following stages.
>
> 6\. **Frequency** **Response** **Table** (Left Channel Only):
>
> *Table* *1* *–* *Frequency* *Response* *(You* *only* *need* *to*
> *collect* *data* *for* *the* *Left* *Channel.)*

||
||
||
||
||

> 𝐷𝑒𝑣𝑖𝑎𝑡𝑖𝑜𝑛𝑟𝑖𝑔ℎ𝑡(𝑑𝐵) = 20.𝑙𝑜𝑔10(𝐴𝑅(max) ) − 20.𝑙𝑜𝑔10(𝐴𝑅(min)) = 20.𝑙𝑜𝑔10
> (𝐴𝑅(max) ) = 1.40𝑑𝐵 𝑅(min)
>
> Does the given circuit meet frequency response specifications as
> outlined in Appendix A?
>
> **Yes**, the circuit meets the specified frequency response
> requirements. The measured gains at 20Hz (9.22 dB) and 20kHz (7.82 dB)
> are within the ±3 dB range of the nominal 9.5 dB.

<img src="./kuskfvcd.png"
style="width:4.10556in;height:2.48472in" /><img src="./tu5mmecp.png"
style="width:3.885in;height:2.96111in" />

*Figure* *1and* *2* *shows* *the* *oscilloscope* *measurements* *for*
*the* *Left* *Channel* *at* *20* *Hz* *and* *20* *kHz*

Measure Microphone Preamp Circuit Performance

> 1\. **Setup**: The Preamp & Mixer PCB was inserted into the chassis.
>
> 2\. **Connections**: The function generator was connected to the input
> of the preamp circuit (JB1), and an oscilloscope measured the output
> from JB5.
>
> 3\. **Measurements**: The gain was calculated using the same formula
> as in the buffer section. 4. **Observation**: The preamp circuit
> successfully amplified the weak microphone signal to a
>
> stronger level suitable for further processing.

Measure Mixer Circuit Performance

> 1\. **Setup**: The Preamp & Mixer PCB was configured with the input
> connected to both the microphone and audio sources.
>
> 2\. **Connections**: The oscilloscope was used to measure the left
> channel output. 3. **Measurements**: The sum of the input signals was
> verified.
>
> 4\. **Observation**: The mixer successfully combined signals from
> multiple sources, ensuring a balanced output.
>
> 5\. **Frequency** **Response** **Table**:

<img src="./4th110k3.png"
style="width:3.62028in;height:2.65764in" /><img src="./rj3nrcbi.png"
style="width:4.23403in;height:3.11736in" />

> *Table* *2* *Pre-Amp* *and* *Mixer* *Frequency* *Response*

||
||
||
||
||
||
||

> *Figure* *3and* *4* *shows* *the* *oscilloscope* *measurements* *for*
> *Pre-Amp* *and* *Mixer* *at* *20* *Hz* *and* *20* *KHz.*
>
> Measure Treble and Bass Circuit Performance
>
> **1.** **Setup**: The Buffer, Mixer, and Treble & Bass PCBs were
> inserted into the chassis.
>
> **2.** **Connections**: The function generator was used to inject a
> test signal, and the oscilloscope measured the left and right channel
> responses.
>
> **3.** **Measurements**: The gain was recorded for both the treble and
> bass circuits at different settings (𝛼 = 0 and 𝛼 = 1).
>
> **4.** **Observation**: The treble and bass controls adjusted
> frequency response as expected, boosting or cutting high and low
> frequencies.
>
> ***5.*** **Results**: *Table* *3* *Treble* *and* *Bass* *Frequency*
> *Response* *Measurements.*

<img src="./5kvd2v2r.png"
style="width:3.71944in;height:2.43875in" /><img src="./tv0ydt0a.png"
style="width:3.61319in;height:2.47681in" /><img src="./fw3tpf3a.png" style="width:0.20333in" /><img src="./0ugpevjv.png"
style="width:0.20333in;height:0.13667in" /><img src="./ln2wznlm.png"
style="width:0.20333in;height:0.1525in" /><img src="./feffmyab.png"
style="width:0.20333in;height:0.12166in" /><img src="./cjhz3cmn.png" style="width:0.2075in" /><img src="./n1fxmtzp.png"
style="width:0.20333in;height:0.13667in" /><img src="./2xysvjwi.png"
style="width:0.20333in;height:0.1525in" /><img src="./jvsiguxk.png"
style="width:0.20417in;height:0.12167in" /><img src="./nimormem.png" style="width:0.2075in" />

<img src="./wnxdg4rh.png"
style="width:3.87028in;height:2.98958in" /><img src="./554icgzd.png"
style="width:3.62847in;height:2.73403in" />

> *Figure* *5,6,* *7and* *8* *shows* *the* *oscilloscope* *measurements*
> *for* *Base* *and* *Treble* *when* *its* *1* *at* *20* *Hz* *and*
> *20K* *Hz.*

<img src="./flwt332j.png"
style="width:4.01361in;height:3.60069in" />Laboratory Cleanliness
Picture

Conclusion

This lab provided hands-on experience in measuring the performance of a
stereo amplifier system. The function generator and oscilloscope were
essential tools for verifying circuit behavior. Key takeaways include:

> • The buffer amplifier maintained the expected gain across the tested
> frequency range, ensuring signal integrity.
>
> • The preamp circuit amplified the microphone signal correctly,
> ensuring proper signal strength for mixing.
>
> • The mixer circuit successfully combined multiple audio sources.
>
> • The treble and bass circuits demonstrated expected frequency
> adjustments, effectively enhancing or reducing specific frequency
> bands.

Some challenges encountered included setting up oscilloscope probes
correctly without introducing noise and ensuring the function generator
provided a stable signal.

Future improvements could involve using higher-quality connectors to
minimize signal interference and refining the measurement approach for
the mixer circuit to obtain more realistic gain values.

Overall, the measured values were within the design specifications,
confirming the amplifier system's proper operation with minor areas for
refinement.
