---
description: Log of all problems experienced when creating furnaces
---

# Malfunction Log

7/3 - Furnace 5 kanthal wire double twisted fried, had to reattached ceramic wire

<br>

7/14 - Furnace 5 ceramic wires fried, first attempt after previous repair, was running for 3+ hours

<br>

| Thermocouple side                                                                                                                                                                                                     | Entry Side                                                                                                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2Faz49oJECjdj0yNK52CKa%2Funknown.png?alt=media\&token=145f953e-b9ed-4b8b-9a27-aa2e01973864) | ![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2FzdowVe2dS1u1mNd0QfuW%2Funknown.png?alt=media\&token=167f0823-ca1e-4d80-b770-3c6f629436f2) |

<br>

Furnace 6 ceramic wires fried, first attempt, ran for 20+ minutes

<br>

| Thermocouple side                                                                                                                                                                                                     | Entry Side                                                                                                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2FbHd6fkD2BScUdZxSAISV%2Funknown.png?alt=media\&token=8ade645f-1331-429f-ace7-9494c5c6f825) | ![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2Fq7z3ZxQmuL1OQzCdTeDK%2Funknown.png?alt=media\&token=541e6ea9-0a7c-488c-b5c8-59c28a9387f5) |

<br>

Ceramic coating on both furnaces was disintegrating where wires had contact

<br>

Ceramic beads seem a little burnt but otherwise intact, Furnace 5 and 6 each had one ceramic wire still in contact with kanthal, being held together with bead despite being fried → possible only the thermocouple wire side was completely fried through, however it’s clear that both wires are under severe heat stress during operation

\
\\<br>

7/15 - Discovered kanthal wire coil on furnace 6 had been burned and rusted through

<br>

To combat this, next tube was made with as few kinks in wiring as possible, and the kanthal wire is used as the connector to the motor control as opposed to ceramic coated copper

| ![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2FSOD7ITUhIOzQLtZyVfJM%2Funknown.png?alt=media\&token=b72f0660-40f6-457b-a83f-ad6c3afd859d) | ![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2FAQieWT5ilYAZm9YsrWpL%2Funknown.png?alt=media\&token=d6509093-ed53-4992-8598-908ab975eb7c) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

<br>

8/25 - Since switching wiring to full kanthal and using one solid piece of wire, shorts have been discovered in the machines after repeated use. Found out the cause was due to the weave casing of wiring was being shredded through

<br>

9/8 - Incorporating the PID controller with a lack of motor control results in too much current being drawn and the kanthal wires becoming so hot they burn through the insulation weave

![](https://2353182699-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXgXjz6D0Vz2o0EOp8JO5%2Fuploads%2FGF9PqqXfMh3w9y24rqO3%2Fimage.png?alt=media\&token=81a50d32-476b-4ab9-8566-e7bc4355b250)<br>

9/9 - Incorporated motor control into PID wiring to control current, but creates a problem where current is not being drawn unless an additional element, such as a lightbulb, is incorporated to trick the system into powering on

<br>
