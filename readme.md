# A triaxial electromagnetic probe design for nondestructive testing of high-voltage overhead transmission lines（updating!）

***Author: Yunxing Pu, Northeastern University.*** 

***This paper has not yet been published, so specific details of the simulations are not provided at this time.***

***Readers are welcome to engage in discussions with me. Contact email: pu_yunxing@163.com***

## Ⅰ. Background

Transmission lines are a crucial component of the power grid. Currently, the majority of high-voltage transmission lines utilize steel-cored aluminum stranded conductors. However, during their operational lifespan, various types of damage can occur. Detecting these types of damages early on is challenging through overall line monitoring of voltage, current, power, and other signals. Nevertheless, the accumulation of these defects can significantly impact the reliability of the transmission system. Currently, there is limited research focused on this specific area, highlighting the urgent need for the development of efficient and reliable methods for detecting internal and external flaws, enabling periodic non-destructive testing of power transmission lines.

<div align=center>
<img src="Fig/fenzhen.jpg" height="250"><img src="Fig\leiji.jpg" height="250" />
</div>
<div align = "center">Fig.1. Wind-induced damage & Lightning strike damage</div>

<div align=center>
<img src="Fig\anzhuang.jpg" width="360" height="210"><img src="Fig\fushi.jpg" width="360" height="210"/>
</div>
<div align = "center">Fig.2. Installation damage & Corrosion damage</div>

## Ⅱ. Principle of PEMEC detection

### Ⅱ.1. Detection target

&emsp;&emsp;This study focuses on the LAG240/30 steel-cored aluminum stranded conductor model, which consists of two outer layers of aluminum and an inner steel core.

<div align=center>
<img src="Fig\jiemian.jpg" width="800" height="250" />
</div>
<div align = "center">Fig.3. Photo of the cross-section and schematic diagram of the LGJ-240/30 cable.</div>



<div align=center>
<img src="Fig\angle.png" height="250" />
</div>
<div align = "center">Fig.4. The Angle of the LGJ-240/30 cable.</div>

&emsp;According to reference materials, the stranding lay angles of the outer layer strands of this ACSR twisted pair transmission line are 12°-13°, and the lay angles of the inner layer strands are 14°-15°.

### Ⅱ.2. 3-D Structure Design

&emsp;The three-dimensional model of this sensor was designed in SolidWorks software. The structure is similar to the diagram published in our previous paper at the ICCSIE 2023 conference.

<div align=center>
<img src="Fig\zongtu.jpg" height="300"><img src="Fig\tantou.png" height="300"/>
</div>
<div align = "center">Fig.5. 3-D Structure Design</div>

&emsp;In comparison, one dimension has been removed - we have eliminated one of the probes, making it a three-axis probe instead of four-axis.

<div align=center>
<img src="Fig\3d-version1.png" height="500">
</div>
<div align = "center">Fig.6. probe-version 1 in comsol</div>



<div align=center>
<img src="Fig\3d.1-version2.jpg" height="300"><img src="Fig\3d.2-version2.jpg" height="300"><img src="Fig\3d.3-version2.jpg" height="300">
</div>
<div align = "center">Fig.7. probe-version 2 in Solidworks</div>



## Ⅲ. Experimental Design

### Ⅲ.1 Flat Panel Validation

*https://abalone-diploma-9b6.notion.site/02547e9283a348938ef3af4ad7d45563?pvs=4&emsp; (Notion note)*

First, we selected a steel plate and an aluminum plate and intentionally created defects in each.

<div align=center>
<img src="Fig\flat defect1.png" height="500"><img src="Fig\al defect.jpg" height="210"/>
</div>
<div align = "center">Fig.8. Flat defect</div>

&emsp;Based on the theory described above, we fabricated the first electromagnetic inspection probe.

<div align=center>
<img src="Fig\tantou1.jpg" height="200"><img src="Fig\experiential plat.jpg" height="500"/>
</div>
<div align = "center">Fig.9. EM Probe & Experiential plat</div>

&emsp;The two different types of damage exhibited similar characteristics when exposed to the pulsed signal from the probe.The digital labels indicate the width of the defects. As the width of the defects increased, both signals exhibited an increasing trend.

<div align=center>
<img src="Fig\al defect2.png" height="400">
</div>
<div align = "center">Fig.10. Detect signal of Al defect</div>

<div align=center>
<img src="Fig\fe defect2.png" height="400"/>
</div>
<div align = "center">Fig.11. Detect signal of Fe defect</div>

### Ⅲ.2 First Version Validation

&emsp;This time, we planned to conduct experiments on actual cable lines. First, we artificially created damage on the cable samples.

<div align=center>
<img src="Fig\outer defect1.png" height="200"/>
</div>
<div align = "center">Fig.12. Outer defect</div>

<div align=center>
<img src="Fig\plat1.jpg" height="500"/>
</div>
<div align = "center">Fig.13. Experiential plat</div>

&emsp;We designed a cylindrical carrier to mount the electromagnetic detection probe.

<div align=center>
<img src="Fig\version1.png" height="500"/>
</div>
<div align = "center">Fig.14. Probe-version 1</div>

<div align=center>
<img src="Fig\version1-detect.png" height="500"/>
</div>
<div align = "center">Fig.15. Dection-version 1</div>

&emsp;We observed the changes in the detection signals for defects in steel strands and aluminum strands separately.

<div align=center>
<img src="Fig\al-version1.png" height="500"/>
</div>
<div align = "center">Fig.16. Dection signal of al strand damages-version 1</div>

<div align=center>
<img src="Fig\fe-version1.png" height="500"/>
</div>
<div align = "center">Fig.17. Dection signal of fe strand damages-version 1</div>

### Ⅲ.3 Second Version Validation

<div align=center>
<img src="Fig\3d.2-version2.jpg" height="500"/>
</div>
<div align = "center">Fig.18. 3d-version2</div>
