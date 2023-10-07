# 3D package

(Modified from Leo Zhi)

![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/0768aea9-bd1c-47b9-9ac2-28e4c9d5fdb6)# 3D Package

The fundamental distinction between 3D and 2.5D packaging is that while 3D packaging directly drills and wires on the chip, electrically linking the top and lower chips, 2.5D packaging wires and drills on the Interposer. The term “3D integration” currently largely refers to integration performed exclusively with 3D TSV.

The primary distinction between 3D integration and 2.5D integration is that while 3D integration involves directly drilling (TSV) and wiring (RDL) on the chip, electrically linking the top and lower chips, 2.5D integration involves drilling and wiring on the intermediate layer interposer.

Physical structure: All chips and passive devices are located above the XY plane. The chips are stacked on top of each other. Above the XY plane, there are TSVS that go through the chip, and below the XY plane, there are wiring and holes for the substrate.
Electrical connection: Direct electrical connection of the chip through TSV and RDL

In like-chip stacks, where numerous identical chips are stacked vertically next to one another and connected by TSVS that pass through the stack of chips, as seen below, 3D integration is most frequently employed. Memory integration frequently employs similar chip integration techniques, including DRAM stack, FLASH stack, and others.

## SoIC of TSMC
![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/27647506-df17-4cc8-9585-11815609d256)

SoIC-of-TSMC

Wafer-on-wafer bonding is a component of 3D packaging, which includes TSMC’s SoIC technology. SoIC is a technology that unites adjacent chips with various features in a bulge-free bonding structure using TSV technology. The bonding material, which is claimed to be valued at up to a billion dollars in secret material, is the key and the portion that is the most enigmatic.

![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/eb7b23bb-4bd3-4cab-a7fc-de585665cda0)


Comparison-of-CoWoS-InFO_PoP
Advanced WLSI can be built using SoIC technology, which combines homogeneous and heterogeneous tiny chips into a single Soc-like chip with a lower size and thinner profile (aka CoWoS and InFO). The newly integrated chip has the necessary heterogeneous integration capabilities built into it, but it appears externally to be a general-purpose SoC processor.

## Foveros of Intel

![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/a09cad27-d911-487d-a85b-341e8781b82d)

Foveros-of-Intel

A bottom chip that serves as an active intermediary layer is positioned on the packaging base at the bottom of the 3D Foveros structure. The upper layer of chips and modules may communicate with the rest of the system thanks to a number of TSV 3D silicon holes in the intermediate layer that link the solder bumps up and down.

## X-Cube 3D of Samsung

![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/1b3323fe-dcf7-4a71-a5bb-27caf492c5a3)

X-Cube-3D-packaging

Samsung’s X-Cube test chips, which use their own 7nm EUV process, have been able to stack SRAM layers on top of logic layers and interface with one another through TSV.

## eWLB of JCET

![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/8834accb-d918-4a58-82a2-f08fdc671a6d)

ewlb-of-JCET

With the help of JCET’s EWLB-based intermediate layer, high-density interconnection is possible in a well-developed low-loss package structure, resulting in more effective heat dissipation and quicker processing. Through novel face-to-face bonding, which avoids the requirement for more expensive TSV interconnects while enabling high-bandwidth 3D integration, 3D eWLB interconnects (including silicon segmentation) are realized.

## 3D-eSinC of HT-Tech

![image](https://github.com/RIOSMPW/3DChipTech/assets/100336131/c7449e6f-c1e2-4bac-92b1-02dce7ad785a)


3D-eSinC-of-HT-Tech

HT-Tech claims that it would introduce cutting-edge packaging innovations such as 2.5D Interpose FCBGA, FOFCBGA, and 3D FOSiP, as well as 3D Memory packaging technology based on the TCB process, in 2022. Research and development of the 12-inch wafer level packaging of car gauge level, the vehicle Lidar technology and goods, and the RF packaging technology of double side molding.

