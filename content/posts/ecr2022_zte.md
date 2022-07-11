---
title: "ZTE at ECR 2022"
date: 2022-07-09T15:40:43+02:00
draft: false
showToc: true
cover:
    image: https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/Vienna%2C_Austria_-_Flickr_-_Pierre_Blaché.jpg/1024px-Vienna%2C_Austria_-_Flickr_-_Pierre_Blaché.jpg
    alt: "Pierre Blaché from Paris, France, CC0, via Wikimedia Commons"
    caption: "Vienna (Pierre Blaché from Paris, France, CC0, via Wikimedia Commons)"
    relative: false 
url: "/ecr2022/"
---

I'll be giving an educational talk about Zero Echo Time (ZTE) MRI at the European Congress of Radiology (ECR) in Vienna on July 15th in the session _Advanced MRI techniques in clinical neuroradiology (RC 1211)_. This post provides supplementary information for this presentation, including useful links to published papers.

## Review papers
The best way to get on top of the literature on ZTE is to read one of the following review papers:

> Wiesinger, F. & Ho, M.-L. **Zero-TE MRI: principles and applications in the head and neck.** BJR 20220059 (2022) doi:[10.1259/bjr.20220059](https://doi.org/10.1259/bjr.20220059)

This is an excellent review paper for a clinical audience. Contains the basics about the technology together with plenty of clinical case examples.

> Ljungberg, E. et al. **Silent zero TE MR neuroimaging: Current state-of-the-art and future directions.** Progress in Nuclear Magnetic Resonance Spectroscopy 123, 73–93 (2021) doi:[10.1016/j.pnmrs.2021.03.002](https://doi.org/10.1016/j.pnmrs.2021.03.002).

This review paper is slightly more technical, illustrating the technical concepts behind ZTE including pulse sequence designs and methods for producing different types of contrast. The paper contains several example application but less focused on clinical indications. 

> Weiger, M. & Pruessmann, K. P. **MRI with Zero Echo Time.** eMagRes 1, 311–322 (2012). doi:[10.1002/9780470034590.emrstm1292](https://doi.org/10.1002/9780470034590.emrstm1292)

This is a technical paper, aimed at MRI physicists and engineers who are interested in ZTE technology and want to develop a deeper understanding of the concepts.  

## References from the presentation

### Part 1. Acoustically Silent MRI
A unique feature of ZTE MRI is the near silent data acquisition. But since there is no such thing as a free lunch, this introduces several limitations on contrast generation with the sequence. A lot of work has therefore been dedicated to producing useful contrast with ZTE.

In the presentation I showcase examples of doing T1-weighted imaging[^r2p2], including some clinical examples[^holdsworth][^matsuo], and some of my own recent work doing motion corrected T1w ZTE with MERLIN[^merlin]. With a gradient refocused version of ZTE called Looping Star[^LS], it is also possible to do quiet T2*-weighted ZTE for QSM[^LS] and fMRI[^nikou].

### Part 2. Imaging tissues with short T2
The effective TE=0 in ZTE yields higher signal from tissues with short T2, such as bone, which can be useful for craniofacial imaging[^lu]. Examples here includes trauma[^cho] and craniofacial malformations[^ho]. It is also possible to use ZTE to produce synthetic CT images for PET/MR and MR radiotherapy applications[^ZT]

### Part 3. Flow and implants
In the last section I highlight some other unique features of the effective TE=0 which includes: flow-insensitivity and imaging around implants. 

Imaging turbulent flow was one of the first applications of ZTE (the pulse sequence was then called RUFIS)[^madio], where it was shown that it could produce highly accurate estimates of flow velocity in the presence of stenosis in a pipe. This advantage was demonstrated in vivo for angiography, where ZTE MRA produced more accurate estimates of stenosis than standard TOF MRA. [^shang] In the context of angiography, ZTE could also be useful for imaging after treatments of aneurysm with stent assisted coil embolization[^irie] [^heo] where the stent and coil typically will cause signal dropout from susceptibility differences. With ZTE, there is less time for phase accumulation and thus less signal dropout.

## Learn more at ECR 2022!
Finally, if you are interested in learning more about ZTE you should check out my colleague Tobias Woods' talk on Sunday.

> **RC 2414 - Developments in magnetic resonance imaging**  
> Zero TE imaging: applications and considerations  
> Tobias Wood, London / UK  
> _Sunday, July 17, 11:30 - 12:30 CEST_


[^r2p2]: Ljungberg, E., Wiesinger, F. & Wood, T. C. Silent Structural Imaging and T1-mapping with a Rapid-Radial Twice-Prepared (R2P2) Sequence. in 4636–4636 (2019).
[^holdsworth]: Holdsworth, S. J., Macpherson, S. J., Yeom, K. W., Wintermark, M. & Zaharchuk, G. Clinical evaluation of silent T1-weighted MRI and silent MR angiography of the brain. American Journal of Roentgenology 210, 404–411 (2018).
[^matsuo]: Matsuo-Hagiyama, C. et al. Comparison of silent and conventional MR imaging for the evaluation of myelination in children. Magnetic Resonance in Medical Sciences 16, 209–216 (2017).
[^merlin]: Ljungberg, E. et al. Motion corrected silent ZTE neuroimaging. Magnetic Resonance in Med 88, 195–210 (2022).
[^LS]: Wiesinger, F., Menini, A. & Solana, A. B. Looping Star. Magnetic Resonance in Medicine 81, 57–68 (2019).
[^nikou]: Damestani, N. L. et al. Revealing the mechanisms behind novel auditory stimuli discrimination: An evaluation of silent functional MRI using looping star. Human Brain Mapping 42, 2833–2850 (2021).
[^lu]: Lu, A., Gorny, K. R. & Ho, M.-L. Zero TE MRI for craniofacial bone imaging. American Journal of Neuroradiology 40, 1562–1566 (2019).
[^cho]: Cho, S. B. et al. Clinical Feasibility of Zero TE Skull MRI in Patients with Head Trauma in Comparison with CT: A Single-Center Study. AMERICAN JOURNAL OF NEURORADIOLOGY 40, 109–115 (2019).
[^ho]: Wiesinger, F. & Ho, M.-L. Zero-TE MRI: principles and applications in the head and neck. BJR 20220059 (2022) doi:[10.1259/bjr.20220059](https://doi.org/10.1259/bjr.20220059)
[^ZT]: Wiesinger, F. et al. Zero TE-based pseudo-CT image conversion in the head and its application in PET/MR attenuation correction and MR-guided radiation therapy planning. Magnetic Resonance in Medicine 80, 1440–1451 (2018).
[^madio]: Madio, D. P., Gach, H. M. & Lowe, I. J. Ultra-fast Velocity Imaging in Stenotically Produced Turbulent Jets Using RUFIS. Magnetic Resonance in Medicine 39, (1998).
[^shang]: Shang, S. et al. Validation of zero TE-MRA in the characterization of cerebrovascular diseases: A feasibility study. American Journal of Neuroradiology 40, 1484–1490 (2019).
[^irie]: Irie, R. et al. Assessing Blood Flow in an Intracranial Stent: A Feasibility Study of MR Angiography Using a Silent Scan after Stent-Assisted Coil Embolization for Anterior Circulation Aneurysms. American Journal of Neuroradiology 36, 967–970 (2015).
[^heo]: Heo, Y. J. et al. Pointwise encoding time reduction with radial acquisition with subtraction-based MRA during the follow-up of stent-assisted coil embolization of anterior circulation aneurysms. American Journal of Neuroradiology 40, 815–819 (2019).
