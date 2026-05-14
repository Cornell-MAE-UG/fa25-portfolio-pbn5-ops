---
layout: project
title: Stopping Little Flies
category: Engineering
---

**Team:** Sorry Little Fly  
**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape  

## Problem statement
Spotted lanternflies reproduce rapidly, with each female laying up to 3 egg masses of 30-60 eggs, enabling exponential population growth within a single season. These egg masses often appear directly on the grapevines, providing the SLF’s with immediate access to the grapes’ necessary nutrients throughout their lifecycle. Removing egg masses reduces SLF reproduction, lowering seasonal infestations and protecting future vine health. A plant-safe, scalable tool could be used across vineyards and other sites, targeting the root source of infestations and increasing overall population control. In developing our design, we also had to consider several key constraints that shaped the final concept. First, the device needed to be gentle enough to avoid damaging the grapevine bark while still applying sufficient force to effectively remove egg masses. Additionally, the geometry of the vines are often irregular, cylindrical, and varying in diameter, which requires a design that could conform to different shapes while maintaining consistent contact. We also accounted for ease of use in field conditions, ensuring the mechanism could be operated quickly and repeatedly without excessive user fatigue.



### Final Prototype: Radial Scraping Apparatus
##### What is it?
Our final iteration is a handheld circular frame that fits around the vine, positioning radially arranged fins around an egg-mass covered line. A toggle switch is then activated to initiate the fins’ radial convergence. After the vine is completely covered, the apparatus is pulled downwards to scrape the vine clean of egg masses without damaging the vine itself. The toggle switch is then reversely activated to release the vine from the grip of the device.
##### Main Assembly
Align fins and gear; fasten to baseplate using M3×6 mm screws and washers
Check rotation and lightly sand contacting surfaces if needed for smooth motion
Align top and bottom housing halves, place baseplate/iris assembly inside, and secure with longer M3 screws
##### Gear and Motor Assembly
Mount the motor into the housing, ensuring proper alignment with the gear system
Press-fit the pinion gear onto the motor shaft, aligned with the mating gear
Wire the motor to the 2×AA battery pack, ensuring correct polarity and clear routing
##### How will it be used? (client)
When observing the grape vineyard, the client, upon identifying an egg mass on a grapevine will use our device to remove the egg mass efficiently and effectively. The widespread use of these devices on vineyards would save dramatic quantities of crop yield by providing an easily usable outlet to control SLF population in vineyards.



### Testing Results:
##### Egg Mass Removal Effectiveness Test:
We built a physical grapevine model using flexible stems to mimic real vine compliance and geometry. Simulated egg masses (paper-mâché) were attached in irregular, clustered patterns to replicate real conditions. The test evaluated whether the mechanism could remove egg masses from a curved, compliant surface and characterized its force interaction with the vine. After 5 passes, the mechanism achieved a 20–25% removal rate per pass. The low efficiency was due to the blades not fully encasing the branch, allowing many egg masses to slip through. Some tearing of the mock branch was also observed, indicating potential vine damage in practice.
##### Repeated Use Test:
We tested the motor-driven radial opening/closing mechanism over 40 cycles to assess durability and friction: 20 horizontal, 10 angled upward, and 10 angled downward. The mechanism performed consistently in all 20 horizontal cycles (100% success), with smooth motion and no structural failures; the washer–screw setup remained secure while allowing rotation. However, issues appeared under angled conditions. In the 10 upward trials, the top gear misaligned in ~3/10 cycles and occasionally disengaged, disrupting operation. In the 10 downward trials, performance remained mostly consistent, with only minor friction increases and no major failures.Overall, the system demonstrates reliable repeated motion under ideal alignment (20/20 successful horizontal cycles), but requires improved gear retention and connection stability for consistent performance across orientations.
##### Variable Radial Distances Test:
We tested the mechanism on real branches of large, medium, and small diameters to evaluate how well it maintains contact across varying radial distances. A total of 15 trials were conducted (5 per branch size), with the device run along approximately 25–30 cm of each branch per trial. The goal was to determine whether the mechanism could achieve consistent contact across different sizes.Results showed that while some contact was maintained across all diameters, overall coverage was low. On the largest branch, 4 out of 5 trials showed full tooth contact at some point, though contact length per tooth was limited (about 20–30% of the circumference). On the medium branch, contact was consistent across all 5 trials but shorter in length (about 15–25%). On the smallest branch, full contact occurred in all trials, but coverage was minimal (about 10–15%).Overall, total contact coverage remained low and relatively similar across all sizes (roughly 10–30%), indicating the mechanism does not effectively adapt to changing radial distances. Future improvements will focus on increasing contact area and improving adaptability across branch diameters.
##### Next Steps:
For future work, we plan to incorporate a hinge mechanism that allows the enclosure to fully open and encase branches of varying sizes. Additionally, developing a telescoping handle would improve usability in hard-to-reach areas. This is a feasible next step, as the force required to remove egg masses with the current prototype falls within the limits of such a handle. With sufficient time and resources, remanufacturing the mechanism in aluminum would also be a logical improvement, enhancing the overall structural integrity.



### Conclusion (using test results):
In summary, our test results indicate that the prototype functions somewhat effectively as a handheld tool for removing egg masses from various surfaces. By utilizing a DC motor with a switch, the mechanism can open and close its teeth with a button rather than via labor. The geometry of the teeth allows the device to conform to vines and branches of varying sizes, improving its overall effectiveness. To be an effective handheld tool, we would need to find a way to implement a hinge and clasp system that we were not able to execute in the given time frame due to complications with the flange/gear relationship. With this adjustment, our prototype would functionally aid in assisting a slight decrease in the egg mass population, but would likely not fully combat the infestation as it is a highly labor intensive solution.



### Overcoming Group Issues:
During this group process, there were instances of absence and illness that limited our ability to collaborate in person on the prototype. To address these challenges, we maintained consistent communication and redistributed tasks to ensure progress was not delayed. For example, when two team members were unable to attend a critical lab session due to a school-mandated activity, they completed their assigned work remotely, and the team reconvened the following day to deliver the mock elevator pitch. Approaches like this allowed the team to continue working effectively while maintaining a fair distribution of responsibilities. In the future, we would plan more proactively for potential scheduling conflicts by identifying critical milestones in advance and assigning backup responsibilities for key tasks. Establishing contingency plans and ensuring all team members are prepared to contribute both in-person and remotely would further strengthen our ability to maintain progress despite unforeseen challenges.



### Bill of Materials (final prototype)

| Material | Cost |
|---------|------|
| RPL Housing, Fins, Gears (188g PLA) | $9.40 |
| Rocker Switch (3-position, On-Off-On) | $12.12 |
| Electric Motor | $10.00 |
| Handle Attachment (150g PLA) | $7.50 |
| Wiring (8 copper) | $3.20 |
| Washers/Screws (5 each) | $11.03 |
| **Total Cost** | **$53.25** |

### Cost Analysis:
This product is highly inexpensive to produce, but slightly time intensive to construct. This product would likely have to be produced in bulk, as it is dependent on individual labor.



### References
* <https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly>
* <https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly/spotted-lanternfly-management>
* <https://www.chicagobotanic.org/plant-information/plant-profiles/grapevines>
* <https://extension.psu.edu/spotted-lanternfly-management-in-vineyards>
* <https://pmc.ncbi.nlm.nih.gov/articles/PMC10926464/>


View our [Exhibit Poster]({{ "/assets/SLF/ClientReport.pdf" | relative_url }}) in PDF format.
