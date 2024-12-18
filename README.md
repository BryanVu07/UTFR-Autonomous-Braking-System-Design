4.0 Driverless Brakes Section Design (Mechanical Brakes ends at 3.1.4 Brake Light)


4.0.1 Rules 

**T15 Autonomous System Brake (ASB) Design and Implementation Summary:** [FSG Rules: https://www.formulastudent.de/fileadmin/user_upload/all/2025/rules/FS-Rules_2025_v1.0.pdf]

- **T15.1**: The vehicle must have an ASB with an Emergency Brake System (EBS) for autonomous mode. All components must fit within the rollover protection envelope, with exceptions for the brake system and deactivation points. Manual braking must always be possible, and the highest brake pressure must apply when both manual and autonomous brakes are active.
- **T15.2**: The EBS must use passive systems with mechanical energy storage, ensuring an automatic brake maneuver in case of electrical power loss.
- **T15.3**: Continuous monitoring and a safe state must be ensured in case of failure, with the vehicle braking and stopping autonomously.
- **T15.4**: The EBS must decelerate the vehicle with an average deceleration of 10 m/s² under dry conditions, with a reaction time of under 200 ms.


4.0.2 EBS Pistons

![image](https://github.com/user-attachments/assets/12ee6d72-ceb9-46fe-bb62-9ea7f3e079fd)
![image](https://github.com/user-attachments/assets/beb9b251-92af-4c24-baf8-2c28dbea964d)
![image](https://github.com/user-attachments/assets/0e6907e3-2d38-4b46-9994-b6cdf8eaa83a)


4.0.3 UT24 Autonomous Braking System 

In 2023-2024, UT24 marked the University of Toronto Formula Racing team's first-ever implementation of driverless technology on our electric vehicle. Last June, we celebrated a historic milestone: Canada’s First Driverless FSAE Car Test 🇨🇦🏎️

We are thrilled to announce the successful autonomous test run of UT24 — a groundbreaking achievement for student engineering in Canada!

This milestone signifies an exciting new chapter for our team, highlighting our innovation in the rapidly advancing field of autonomous and electric motorsports technology. Building on our 2022 transition to electric power, our goal last year was to integrate an Autonomous Braking System (ABS) into the car. With most components sourced externally or from sponsors, we faced challenges in time and expertise to create a fully compatible design that adheres to the competition rules. As a result, last year's design will not qualify for the FSG Driverless competition rules, as the pedal was not adjustable in conjunction with the EBS piston linkages attached to the pedal shaft. My responsibility this year is to redesign the system, ensuring both functionality and full adherence to the 2025 FSG Driverless rules.

![Screenshot 2024-11-11 062507](https://github.com/user-attachments/assets/142a62e7-dd65-476f-9778-e47c048f0de2)
https://www.linkedin.com/posts/utfr_canadas-first-driverless-fsae-car-test-activity-7219013523928985600-Te0B?utm_source=share&utm_medium=member_desktop


4.0.3.1 UT24 Emergency Braking System Functionality 

The calculation sheet was created by the UT24 Brakes Lead - Mo Taban, based on a successful EBS run of the UT24 Driverless EV. My responsibility is to update the new design parameters and ensure strict compliance with the physical constraints of the car and the FSAE rules for the Driverless category.

<img width="1121" alt="Screenshot 2024-10-24 at 6 32 30 PM" src="https://github.com/user-attachments/assets/25198e59-e1e5-45f2-9824-97635cbe19cc">
<img width="964" alt="Screenshot 2024-10-24 at 6 32 52 PM" src="https://github.com/user-attachments/assets/43ab3286-acc0-4429-825d-e0c5c9a52a9e">
<img width="1149" alt="Screenshot 2024-10-24 at 6 32 56 PM" src="https://github.com/user-attachments/assets/72e404fd-395b-42b2-add0-a128ed91a457">


4.0.4 UT25 Autonomous Braking System 

4.0.4.1 UT25 Emergency Braking System

This new EBS design features a custom chamber placed directly on top of the master cylinders. When air is introduced into the chamber at 140 psi, it compresses the large piston on top of the master cylinder rod, activating the hydraulic braking system without interfering with the bias bar. The design demonstrates strong mechanical fundamentals, creativity, and confidence in creating custom pneumatic components that replace industry-made pneumatic cylinders. This system is fully compliant with competitions featuring a driverless category, as it allows for adjustability with the brake pedal, unlike the UT24 design.

![Screenshot 2024-12-15 102201](https://github.com/user-attachments/assets/ab475208-5332-42fa-a59b-194430542805)
![image](https://github.com/user-attachments/assets/1ace79a8-a141-43c2-a663-66e31c068555)


4.0.4.2 UT25 EBS Calculations

![image](https://github.com/user-attachments/assets/b6c73a8b-b527-4d0c-93cd-3991c62a6280)
![Screenshot 2024-12-18 160852](https://github.com/user-attachments/assets/e3b10c24-0b40-4944-b1d5-8d40e3738f08)
![Screenshot 2024-12-18 160902](https://github.com/user-attachments/assets/0e82c32a-ecdc-48eb-8cf3-029d6b042318)
![Screenshot 2024-12-18 160909](https://github.com/user-attachments/assets/fd9af9d5-314e-4928-90af-2a311c7d7ce1)


4.0.4.3 Air Tank

![image](https://github.com/user-attachments/assets/b272fa7b-0c77-4ea8-b050-2356f11044e8)


4.0.4.4 Solenoid valves

![image](https://github.com/user-attachments/assets/bb8596ca-5cfc-46d3-9219-6aa1dedb1caf)


4.0.4.5 Air Accumulators

![image](https://github.com/user-attachments/assets/d8692d60-c412-43a6-89e8-f9ccd4f82d2e)


4.0.4.6 Manual On/Off Valve

![image](https://github.com/user-attachments/assets/46de1e00-8e3b-44ef-960c-94766525c79e)






