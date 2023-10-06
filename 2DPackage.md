# 2D Package

Currently, in the field of advanced packaging, there are three main types that can be distinguished: 2D packaging, 2.5D packaging, and 3D packaging. Each type has its own unique characteristics and applications, offering a wide range of possibilities for various industries. Through continuous research and development, these packaging techniques have evolved to meet the ever-growing demands of modern technology.

2D Packing is a computational problem that involves fitting a set of 2D objects into a container of fixed dimensions in the most efficient way possible. The goal is to minimize wastage of space and optimize the arrangement of objects.

Two important factors for categorizing electronic integration technologies are

 1. Physical structure

All chips and passive devices are physically installed on the substrate plane. The XY plane is in direct contact with chips and passive devices. Substrate wiring and holes are located below the XY plane

 2. Electrical connection (electrical interconnection)

All electrical connections must pass through the substrate (except for very few bonding points directly connected by bonding wire)

The chip integration primarily follows a 2D approach, where the transistors are integrated into the wafer plane. Similarly, PCB integration also follows a 2D approach, where electronic components are mounted flat on the PCB surface. Therefore, both chip and PCB integration can be considered as 2D integration. However, in-package integration presents a more complex scenario.

## InFO of TSMC

![image](https://github.com/RIOSMPW/3DPackageTech/assets/100336131/648af194-006c-4a10-ab3c-1fe99f816055)

InFO-of-TSMC

Taiwan Semiconductor Manufacturing created InFO technology in 2017. InFO technology is similar to Fan-out technology used in most packaging plants and can be thought of as the integration of the multi-chip Fan-out process. The main distinction is that the silicon interposer has been removed, and some RDL layers have been used for concatenation (the A10 processor in the 2016 iPhone7, Taiwan Semiconductor 16nm FinFET process, and InFO technology).

## eWLB of ASE

![image](https://github.com/RIOSMPW/3DPackageTech/assets/100336131/9804f64e-0d4b-475e-88f7-0086ff21f7f7)


Similar to TSMC InFO, both are Fan-out technologies

eWLB-of-ASE
In addition, there is a 2D+ integration

2D+ integration refers to the traditional stackable integration of chips connected by bonding lines. Some people may ask, chip stacking is not 3D, why should it be defined as 2D+ integration?

Mainly based on the following two reasons:

3D integration now primarily refers to integration via 3D TSV. To avoid misunderstanding, we refer to this traditional chip stacking as 2D+ integration.
Although the physical structure is 3D, the electrical interconnection must pass through the substrate, which means that the bonding wire must first be bonded to the substrate before the electrical interconnection can take place. This is equivalent to 2D integration. The improvement over 2D integration is stacking in structure, which can save packaging space, so it is called 2D+ integration.
Physical structure: All chips and passive devices are above the XY plane, some chips do not directly contact the substrate, and the wiring and holes on the substrate are below the XY plane.
Electrical Connection: All electrical connections must pass through the substrate (except for very few bonding points directly connected by bonding wire)
