##### § 1037.660 Idle-reduction technologies. #####

This section specifies requirements that apply for idle-reduction technologies modeled under § 1037.520. It does not apply for idle-reduction technologies you do not model under § 1037.520.

(a) *Minimum requirements.* Idle-reduction technologies must meet all the following requirements to be modeled under § 1037.520 except as specified in paragraphs (b) and (c) of this section:

(1) *Automatic engine shutdown (AES) systems.* The system must shut down the engine within a threshold inactivity period of 60 seconds or less for vocational vehicles and 300 seconds or less for tractors when all the following conditions are met:

(i) The transmission is set to park, or the transmission is in neutral with the parking brake engaged. This is “parked idle.”

(ii) The operator has not reset the system timer within the specified threshold inactivity period by changing the position of the accelerator, brake, or clutch pedal; or by resetting the system timer with some other mechanism we approve.

(iii) You may identify systems as “tamper-resistant” if you make no provision for vehicle owners, dealers, or other service outlets to adjust the threshold inactivity period.

(iv) For Phase 2 and later tractors, you may identify AES systems as “adjustable” if, before delivering to the ultimate purchaser, you enable authorized dealers to modify the vehicle in a way that disables the AES system or makes the threshold inactivity period longer than 300 seconds. However, the vehicle may not be delivered to the ultimate purchaser with the AES system disabled or the threshold inactivity period set longer than 300 seconds. You may allow dealers or repair facilities to make such modifications; this might involve password protection for electronic controls, or special tools that only you provide. Any dealers making any modifications before delivery to the ultimate purchaser must notify you, and you must account for such modifications in your production and ABT reports after the end of the model year. Dealers failing to provide prompt notification are in violation of the tampering prohibition of 40 CFR 1068.101(b)(1). Dealer notifications are deemed to be submissions to EPA. Note that these adjustments may not be made if the AES system was not “adjustable” when first delivered to the ultimate purchaser.

(v) For vocational vehicles, you may use the provisions of § 1037.610 to apply for an appropriate partial emission reduction for AES systems you identify as “adjustable.”

(2) *Neutral idle.* Phase 2 and later vehicles with hydrokinetic torque converters paired with automatic transmissions qualify for neutral-idle credit in GEM modeling if the transmission reduces torque equivalent to shifting into neutral throughout the interval during which the vehicle's brake pedal is depressed and the vehicle is at a zero-speed condition (beginning within five seconds of the vehicle reaching zero speed with the brake depressed). If a vehicle reduces torque partially but not enough to be equivalent to shifting to neutral, you may use the provisions of § 1037.610(g) to apply for an appropriate partial emission reduction; this may involve A to B testing with the powertrain test procedure in 40 CFR 1036.545 or the spin-loss portion of the transmission efficiency test in § 1037.565.

(3) *Stop-start.* Phase 2 and later vocational vehicles qualify for stop-start reduction in GEM modeling if the engine shuts down no more than 5 seconds after the vehicle's brake pedal is depressed when the vehicle is at a zero-speed condition.

(b) *Override conditions*. The system may limit activation of the idle-reduction technology while any of the conditions of this paragraph (b) apply. These conditions allow the system to delay engine shutdown, adjust engine restarting, or delay disengaging transmissions, but do not allow for resetting timers. Engines may restart and transmissions may re-engage during override conditions if the vehicle is set up to do this automatically. We may approve additional override criteria as needed to protect the engine and vehicle from damage and to ensure safe vehicle operation.

(1) For AES systems on tractors, the system may delay shutdown—

(i) When an exhaust emission control device is regenerating. The period considered to be regeneration for purposes of this allowance must be consistent with good engineering judgment and may differ in length from the period considered to be regeneration for other purposes. For example, in some cases it may be appropriate to include a cool down period for this purpose but not for infrequent regeneration adjustment factors.

(ii) When the vehicle's main battery state-of-charge is not sufficient to allow the main engine to be restarted.

(iii) When the vehicle's transmission, fuel, oil, or engine coolant temperature is too low or too high according to the manufacturer's specifications for protecting against system damage. This allows the engine to continue operating until it is in a predefined temperature range, within which the shutdown sequence of paragraph (a) of this section would resume.

(iv) When the vehicle's main engine is operating in power take-off (PTO) mode. For purposes of this paragraph (b), an engine is considered to be in PTO mode when a switch or setting designating PTO mode is enabled.

(v) When external ambient conditions prevent managing cabin temperatures for the driver's safety.

(vi) When necessary while servicing the vehicle, provided the deactivation of the AES system is accomplished using a diagnostic scan tool. The system must be automatically reactivated when the engine is shut down for more than 60 minutes.

(2) For AES systems on vocational vehicles, the system may limit activation—

(i) When any condition specified in paragraphs (b)(1)(i) through (v) of this section applies.

(ii) When the engine compartment is open.

(3) For neutral idle, the system may delay shifting the transmission to neutral—

(i) When the system meets the PTO conditions specified in paragraph (b)(1)(iv) of this section.

(ii) When the transmission is in reverse gear.

(iii) When the vehicle is ascending or descending a road with grade at or above 6.0%.

(4) For stop-start, the system may limit activation—

(i) When any condition specified in paragraph (b)(2) or (b)(3)(ii) or (iii) of this section applies.

(ii) When air brake pressure is too low according to the manufacturer's specifications for maintaining vehicle-braking capability.

(iii) When an automatic transmission is in “park” or “neutral” and the parking brake is engaged.

(iv) When recent vehicle speeds indicate an abnormally high shutdown and restart frequency, such as with congested driving. For example, a vehicle not exceeding 10 mi/hr for the previous 300 seconds or since the most recent engine start would be a proper basis for overriding engine shutdown. You may also design this override to protect against system damage or malfunction of safety systems.

(v) When the vehicle detects that a system or component is worn or malfunctioning in a way that could reasonably prevent the engine from restarting, such as low battery voltage.

(vi) When the steering angle is at or near the limit of travel.

(vii) When flow of diesel exhaust fluid is limited due to freezing.

(viii) When a sensor failure could prevent the anti-lock braking system from properly detecting vehicle speed.

(ix) When a protection mode designed to prevent component failure is active.

(x) When a fault on a system component needed for starting the engine is active.

(c) *Adjustments to AES systems for Phase 1.* (1) The AES system may include an expiration point (in miles) after which the AES system may be disabled. If your vehicle is equipped with an AES system that expires before 1,259,000 miles, adjust the model input as follows, rounded to the nearest 0.1 g/ton-mile: AES Input = 5 g CO2/ton-mile × (miles at expiration/1,259,000 miles).

(2) For AES systems designed to limit idling to a specific number of hours less than 1,800 hours over any 12-month period, calculate an adjusted AES input using the following equation, rounded to the nearest 0.1 g/ton-mile: AES Input = 5 g CO2/ton-mile × (1—(maximum allowable number of idling hours per year/1,800 hours)). This is an annual allowance that starts when the vehicle is new and resets every 12 months after that. Manufacturers may propose an alternate method based on operating hours or miles instead of years.

(d) *Adjustable parameters.* Provisions that apply generally with respect to adjustable parameters also apply to the AES system operating parameters, except the following are not considered to be adjustable parameters:

(1) Accelerator, brake, and clutch pedals, with respect to resetting the idle timer. Parameters associated with other timer reset mechanisms we approve are also not adjustable parameters.

(2) Bypass parameters allowed for vehicle service under paragraph (b)(1)(ii) of this section.

(3) Parameters that are adjustable only after the expiration point.

(e) *PM limit for diesel APU.* For model year 2020 and earlier tractors with a date of manufacture on or after January 1, 2018, the GEM credit for AES systems with OEM-installed diesel APUs is valid only if the engine is certified under 40 CFR part 1039 with a deteriorated emission level for particulate matter at or below 0.15 g/kW-hr, or if the engine or APU is certified to the standards specified in § 1037.106(g).

[81 FR 74048, Oct. 25, 2016, as amended at 86 FR 34490, June 29, 2021; 89 FR 29788, Apr. 22, 2024]