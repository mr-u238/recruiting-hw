# Recuiting for E-Agle TRT (HW)

Welcome to the recruitment _test_ for the electronics team at E-Agle TRT.

This _test_ is meant to give us the possibility to have a first understanding of the capabilities of our applicants without the them having the pressure of seeing it as an exam.

Moreover it's studied so that the applicants get a first taste of the tools used so that once in the team they can get up and running quickly into the team workflow without having to learn stuff under pressure when it's needed.

## What we'll look into

 - Understanding of basic electronics
 - Components choice and their suitability
 - KiCad
   - Schematic choices, tidyness and good practices
   - Board layout understanding and, again, good practices
 - `git` usage: fork, branch, clone, commit, push, pull
 - Not only _tecnically correct_ but also we'll evaluate if it's usable.

## Assignment

Develop a DCDC converter with power monitoring:

 - Input voltage range: 11V-27V
 - Two outputs of:
   - 5V3A
   - 3.3V0.5A
 - Monitor the input current with a shunt
    - Blink a LED, driven by a transistor, at a frequency between 3-5 Hz when the power at the input is greater than 10W
    - The LED should be off when power is below 3W
    - Use non programmable circuits

 - In the schematic use also a hierarchical sheet
   - _It's not a good practice for this small of a project but it's for letting you learn about hierarchy without the hassle of a more complex assignment_

 - Add comments for the necessary calculations of values

 - Consider JLC PCB as the board manufacturer

## Instructions

 - Fork the repo
 - Branch the master into one called `name_surname` where the work will be done
 - Commit your progress along the way
 - Open a pull request on `eagletrt/recruiting-hw`
 - When you are done, generate the schematic output inside `docs/` and the production (gerber) files in `output/`
 - Submit the recruiting form [here](https://airtable.com/shrorVpRaW3HqUUfT)
 - If you have any questions feel free to contact us at [electronics@eagletrt.it](mailto:electronics@eagletrt.it)
