##### § 1065.308 Continuous gas analyzer system-response and updating-recording verification—for gas analyzers not continuously compensated for other gas species. #####

(a) *Scope and frequency.* This section describes a verification procedure for system response and updating-recording frequency for continuous gas analyzers that output a gas species mole fraction (i.e., concentration) using a single gas detector, i.e., gas analyzers not continuously compensated for other gas species measured with multiple gas detectors. See § 1065.309 for verification procedures that apply to continuous gas analyzers that are continuously compensated for other gas species measured with multiple gas detectors. Perform this verification to determine the system response of the continuous gas analyzer and its sampling system. This verification is required for continuous gas analyzers used for transient or ramped-modal testing. You need not perform this verification for batch gas analyzer systems or for continuous gas analyzer systems that are used only for discrete-mode testing. Perform this verification after initial installation (i.e., test cell commissioning) and after any modifications to the system that would change system response. For example, perform this verification if you add a significant volume to the transfer lines by increasing their length or adding a filter; or if you reduce the frequency at which the gas analyzer updates its output or the frequency at which you sample and record gas-analyzer concentrations.

(b) *Measurement principles.* This test verifies that the updating and recording frequencies match the overall system response to a rapid change in the value of concentrations at the sample probe. Gas analyzers and their sampling systems must be optimized such that their overall response to a rapid change in concentration is updated and recorded at an appropriate frequency to prevent loss of information. This test also verifies that the measurement system meets a minimum response time. You may use the results of this test to determine transformation time, *t*50, for the purposes of time alignment of continuous data in accordance with § 1065.650(c)(2)(i). You may also use an alternate procedure to determine *t*50 in accordance with good engineering judgment. Note that any such procedure for determining *t*50 must account for both transport delay and analyzer response time.

(c) *System requirements.* Demonstrate that each continuous analyzer has adequate update and recording frequencies and has a minimum rise time and a minimum fall time during a rapid change in gas concentration. You must meet one of the following criteria:

(1) The product of the mean rise time, *t*10-90, and the frequency at which the system records an updated concentration must be at least 5, and the product of the mean fall time, *t*90-10, and the frequency at which the system records an updated concentration must be at least 5. If the recording frequency is different than the analyzer's output update frequency, you must use the lower of these two frequencies for this verification, which is referred to as the updating-recording frequency. This verification applies to the nominal updating and recording frequencies. This criterion makes no assumption regarding the frequency content of changes in emission concentrations during emission testing; therefore, it is valid for any testing. Also, the mean rise time must be at or below 10 seconds and the mean fall time must be at or below 10 seconds.

(2) The frequency at which the system records an updated concentration must be at least 5 Hz. This criterion assumes that the frequency content of significant changes in emission concentrations during emission testing do not exceed 1 Hz. Also, the mean rise time must be at or below 10 seconds and the mean fall time must be at or below 10 seconds.

(3) You may use other criteria if we approve the criteria in advance.

(4) You may meet the overall PEMS verification in § 1065.920 instead of the verification in this section for field testing with PEMS.

(d) *Procedure.* Use the following procedure to verify the response of each continuous gas analyzer:

(1) *Instrument setup.* Follow the analyzer manufacturer's start-up and operating instructions. Adjust the measurement system as needed to optimize performance. Run this verification with the analyzer operating in the same manner you will use for emission testing. If the analyzer shares its sampling system with other analyzers, and if gas flow to the other analyzers will affect the system response time, then start up and operate the other analyzers while running this verification test. You may run this verification test on multiple analyzers sharing the same sampling system at the same time. If you use any analog or real-time digital filters during emission testing, you must operate those filters in the same manner during this verification.

(2) *Equipment setup.* We recommend using minimal lengths of gas transfer lines between all connections and fast-acting three-way valves (2 inlets, 1 outlet) to control the flow of zero and blended span gases to the sample system's probe inlet or a tee near the outlet of the probe. If you inject the gas at a tee near the outlet of the probe, you may correct the transformation time, *t*50, for an estimate of the transport time from the probe inlet to the tee. Normally the gas flow rate is higher than the sample flow rate and the excess is overflowed out the inlet of the probe. If the gas flow rate is lower than the sample flow rate, the gas concentrations must be adjusted to account for the dilution from ambient air drawn into the probe. We recommend you use the final, stabilized analyzer reading as the final gas concentration. Select span gases for the species being measured. You may use binary or multi-gas span gases. You may use a gas blending or mixing device to blend span gases. A gas blending or mixing device is recommended when blending span gases diluted in N2 with span gases diluted in air. You may use a multi-gas span gas, such as NO-CO-CO2-C3H8-CH4, to verify multiple analyzers at the same time. If you use standard binary span gases, you must run separate response tests for each analyzer. In designing your experimental setup, avoid pressure pulsations due to stopping the flow through the gas-blending device. The change in gas concentration must be at least 20% of the analyzer's range.

(3) *Data collection.* (i) Start the flow of zero gas.

(ii) Allow for stabilization, accounting for transport delays and the slowest analyzer's full response.

(iii) Start recording data. For this verification you must record data at a frequency greater than or equal to that of the updating-recording frequency used during emission testing. You may not use interpolation or filtering to alter the recorded values.

(iv) Switch the flow to allow the blended span gases to flow to the analyzer. If you intend to use the data from this test to determine *t*50 for time alignment, record this time as *t*0.

(v) Allow for transport delays and the slowest analyzer's full response.

(vi) Switch the flow to allow zero gas to flow to the analyzer. If you intend to use the data from this test to determine *t*50 for time alignment, record this time as *t*100.

(vii) Allow for transport delays and the slowest analyzer's full response.

(viii) Repeat the steps in paragraphs (d)(3)(iv) through (vii) of this section to record seven full cycles, ending with zero gas flowing to the analyzers.

(ix) Stop recording.

(e) *Performance evaluation.* (1) If you choose to demonstrate compliance with paragraph (c)(1) of this section, use the data from paragraph (d)(3) of this section to calculate the mean rise time, *t*10-90, and mean fall time, *t*90-10, for each of the analyzers being verified. You may use interpolation between recorded values to determine rise and fall times. If the recording frequency used during emission testing is different from the analyzer's output update frequency, you must use the lower of these two frequencies for this verification. Multiply these times (in seconds) by their respective updating-recording frequencies in Hertz (1/second). The resulting product must be at least 5 for both rise time and fall time. If either value is less than 5, increase the updating-recording frequency, or adjust the flows or design of the sampling system to increase the rise time and fall time as needed. You may also configure analog or digital filters before recording to increase rise and fall times. In no case may the mean rise time or mean fall time be greater than 10 seconds.

(2) If a measurement system fails the criterion in paragraph (e)(1) of this section, ensure that signals from the system are updated and recorded at a frequency of at least 5 Hz. In no case may the mean rise time or mean fall time be greater than 10 seconds.

(3) If a measurement system fails the criteria in paragraphs (e)(1) and (2) of this section, you may use the measurement system only if the deficiency does not adversely affect your ability to show compliance with the applicable standards in this chapter.

(f) *Transformation time, t*50, determination. If you choose to determine *t*50 for purposes of time alignment using data generated in paragraph (d)(3) of this section, calculate the mean *t*0-50 and the mean *t*100-50 from the recorded data. Average these two values to determine the final *t*50 for the purposes of time alignment in accordance with § 1065.650(c)(2)(i).

(g) *Optional procedure.* Instead of using a three-way valve to switch between zero and span gases, you may use a fast-acting two-way valve to switch sampling between ambient air and span gas at the probe inlet. For this alternate procedure, the following provisions apply:

(1) If your probe is sampling from a continuously flowing gas stream (e.g., a CVS tunnel), you may adjust the span gas flow rate to be different than the sample flow rate.

(2) If your probe is sampling from a gas stream that is not continuously flowing (e.g., a raw exhaust stack), you must adjust the span gas flow rate to be less than the sample flow rate so ambient air is always being drawn into the probe inlet. This avoids errors associated with overflowing span gas out of the probe inlet and drawing it back in when sampling ambient air.

(3) When sampling ambient air or ambient air mixed with span gas, all the analyzer readings must be stable within ±0.5% of the target gas concentration step size. If any analyzer reading is outside the specified range, you must resolve the problem and verify that all the analyzer readings meet this specification.

(4) For oxygen analyzers, you may use purified N2 as the zero gas and ambient air (plus purified N2 if needed) as the reference gas. Perform the verification with seven repeat measurements that each consist of stabilizing with purified N2, switching to ambient air and observing the analyzer's rise and stabilized reading, followed by switching back to purified N2 and observing the analyzer's fall and stabilized reading.

[73 FR 59325, Oct. 8, 2008, as amended at 79 FR 23766, Apr. 28, 2014; 88 FR 4674, Jan. 24, 2023]