# Awesome Fiducial Markers

A curated list of awesome fiducial marker resources for Computer Vision, Robotics, and Augmented Reality (AR).

## 📋 Table of Contents

- [Marker Libraries](#marker-lists)
  - [Arbitrary Markers](#fm-arbitrary)
  - [Dot Markers](#fm-dot)
  - [Planar/Circular Markers](#fm-nonsquare)
  - [Matrix-based Markers](#fm-matrix)
- [Complementary Methods](#fm-methods)
- [Contribution](#contribution)

## Marker Libraries <a id="marker-lists"></a>

### Arbitrary Markers <a id="fm-arbitrary"></a>

- [] **ARTTag** ([paper 📃](https://doi.org/10.1145/2945078.2945116), [code 💻](#), [docs 📂](#))
- [] **Cybercode** ([paper 📃](https://doi.org/10.1145/354666.354667), [code 💻](#), [docs 📂](#))
- [] **D-touch** ([paper 📃](#), [code 💻](#), [docs 📂](#))
- [] **Farkas** ([paper 📃](https://doi.org/10.1109/IECON.2012.6388951), [code 💻](#), [docs 📂](#))
- [] **Nishino-1** ([paper 📃](#), [code 💻](#), [docs 📂](#))
- [] **Nishino-2** ([paper 📃](#), [code 💻](#), [docs 📂](#))
- [2023] **VuMark** ([paper 📃](https://doi.org/10.3390/app13031496), [code 💻](https://developer.vuforia.com/downloads/samples), [docs 📂](https://developer.vuforia.com/library/vumarks/vumark-design-guide)) | Customized marker designs with data encoding
- [2021] **Topotag** ([paper 📃](https://doi.ieeecomputersociety.org/10.1109/TVCG.2020.2988466), [github 💻](https://github.com/herohuyongtao/topotag), [docs 📂](https://herohuyongtao.github.io/research/publications/topo-tag/)) | Robust and scalable topological marker system
- [2021] **Seedmarkers** ([paper 📃](https://doi.org/10.1145/3430524.3440645), [github 💻](https://github.com/volzotan/Seedmarkers), [docs 📂](https://volzo.de/thing/seedmarker/)) | Embeddable Markers for Physical Objects
- [2019] **STag** ([paper 📃](https://doi.org/10.1016/j.imavis.2019.06.007), [github 💻](https://github.com/bbenligiray/stag), [ros 🤖](https://github.com/usrl-uofsc/stag_ros/), [docs 📂](https://roboticsknowledgebase.com/wiki/sensing/stag/)) | A marker robust against jitter factors
- [2017] **ChromaTag** ([paper 📃](https://doi.org/10.1109/ICCV.2017.164), [github 💻](https://github.com/CogChameleon/ChromaTag)) | A colored marker with a fast detection algorithm
- [2010] **Topolo Surface** ([paper 📃](https://doi.org/10.2197/ipsjjip.18.16)) | Topological region adjacency and angle information
- [2009] **SIFTTag** ([paper 📃](https://api.semanticscholar.org/CorpusID:10011163)) | Maximum detector response markers for SIFT and SURF
- [2007] **ReacTIVision** ([paper 📃](https://dl.acm.org/doi/abs/10.1145/1226969.1226983), [github 💻](https://github.com/mkalten/reacTIVision), [docs 📂](https://reactivision.sourceforge.net/)) | A framework for table-based tangible interaction
- [2004] **Visual Code** ([paper 📃](https://doi.org/10.1007/11526858_7)) | Markers for interaction with camera phones

### Dot Markers <a id="fm-dot"></a>

- [2018] **RandomDot** ([paper 📃](https://doi.org/10.1109/ICPR.2018.8545845), [code 💻](https://gitlab.com/charmie11/trdm), [docs 📂](https://sites.google.com/view/dryujioyamada/research/transparent-random-dot-markers)) | Markers printed on transparent sheets
- [2012] **Pi-Tag** ([paper 📃](https://link.springer.com/article/10.1007/s00138-012-0469-6), [github 💻](https://github.com/mpetroff/pi-tag-detector), [ros 🤖](http://wiki.ros.org/cob_fiducials)) | A fast image-space marker design based on projective invariants
- [2011] **RUNE-Tag** ([paper 📃](https://doi.org/10.1109/CVPR.2011.5995544), [github 💻](https://github.com/artursg/RUNEtag), [code 💻](http://www.dsi.unive.it/~bergamasco/runetag/RUNEtag.zip)) | An accurate fiducial marker with strong occlusion resilience

### Planar/Circular Markers <a id="fm-nonsquare"></a>

- [2017] **WhyCode** ([paper 📃](https://dl.acm.org/doi/10.1145/3019612.3019709), [github 💻](https://github.com/gestom/whycon-orig), [ros 🤖](https://github.com/jiriUlr/whycon-ros)) | A precise, efficient, and low-cost localization system
- [2015] **WhyCon** ([paper 📃](https://robotica.dc.uba.ar/public/papers/nitsche2015.pdf), [github 💻](https://github.com/gestom/whycon-orig), [ros 🤖](https://github.com/jiriUlr/whycon-ros)) | A precise, efficient, and low-cost localization system
- [2014] **BullsEye** ([paper 📃](https://dl.acm.org/doi/10.1145/2669485.2669503), [web-page 🌐](https://cavi.au.dk/technologies/bullseye)) | High-precision fiducial tracking for table-based tangible interaction
- [2012] **CC-Tag** ([paper 📃](https://doi.org/10.1109/ICIP.2012.6467121), [paper 📃](https://doi.org/10.1109/CVPR.2016.67), [github 💻](https://github.com/alicevision/CCTag), [docs 📂](https://cctag.readthedocs.io/en/latest/)) | A concentric circular marker for camera tracking
- [2011] **FourierTag** ([paper 📃](https://doi.org/10.1109/CRV.2011.13), [github 💻](https://github.com/anqixu/ftag2)) | A smoothly degradable marker with configurable payload capacity
- [2006] **Cantag** ([paper 📃](https://doi.org/10.1109/PERCOM.2006.13), [code 💻](https://www.cl.cam.ac.uk/%7Eacr31/cantag/), [docs 📂](https://www.cl.cam.ac.uk/%7Eacr31/cantag/)) | An open source software toolkit for marker-based vision systems
- [2002] **Intersense** ([paper 📃](https://doi.org/10.1109/ISMAR.2002.1115065)) | A circular data matrix marker for wearable vision-inertial tracking
- [1992] **CCC** ([paper 📃](https://doi.org/10.1117/12.56761)) | Using concentric contrasting circles for feature extraction

### Matrix-based Markers <a id="fm-matrix"></a>

- [2014] **ArUco Marker** ([paper 📃](https://doi.org/10.1016/j.patcog.2014.01.005), [code 💻](https://sourceforge.net/projects/aruco/), [ros 🤖](https://github.com/pal-robotics/aruco_ros), [docs 📂](https://docs.opencv.org/4.x/d5/dae/tutorial_aruco_detection.html)) | Highly reliable fiducial markers under occlusion
- [2011] **AprilTag** ([paper 📃](https://doi.org/10.1109/ICRA.2011.5979561), [github 💻](https://github.com/AprilRobotics/apriltag), [ros 🤖](https://github.com/AprilRobotics/apriltag_ros), [docs 📂](https://april.eecs.umich.edu/software/apriltag)) | A visual fiducial system popular in robotics
- [2010] **CALTag** ([paper 📃](https://diglib.eg.org/handle/10.2312/PE.VMV.VMV10.041-048), [github 💻](https://github.com/brada/caltag), [docs 📂](https://www.cs.ubc.ca/labs/imager/tr/2010/Atcheson_VMV2010_CALTag/)) | High precision markers for camera calibration
- [2007] **BinARyID** ([paper 📃](http://dx.doi.org/10.2312/PE/VE2007Short/059-064)) | An ID-based extension for marker tracking systems
- [2007] **ARToolKitPlus** ([paper 📃](https://api.semanticscholar.org/CorpusID:14966142), [github 💻](https://github.com/paroj/artoolkitplus)) | Pose tracking system on mobile devices
- [2005] **ARTag** ([paper 📃](https://doi.org/10.1109/CVPR.2005.74), [github (not-official) 💻](https://github.com/harshkakashaniya/AR-tag-detection)) | A fiducial marker system using digital techniques
- [1999] **ARToolKit** ([paper 📃](https://doi.org/10.1109/IWAR.1999.803809), [github 💻](https://github.com/artoolkit/ARToolKit5), [docs 📂](http://www.artoolkit.org/)) | A marker tracking and HMD calibration tool
- [1998] **Matrix** ([paper 📃](https://doi.org/10.1109/APCHI.1998.704151)) | Real-time object identification for augmented reality

## Complementary Methods <a id="fm-methods"></a>

- [2023] **DeepTag** ([paper 📃](https://doi.ieeecomputersociety.org/10.1109/TPAMI.2022.3174603), [github 💻](https://github.com/herohuyongtao/deeptag-pytorch), [docs 📂](https://herohuyongtao.github.io/research/publications/deep-tag/)) | A framework for robust fiducial marker design and detection
- [2022] **DynaTags** ([paper 📃](https://dl.acm.org/doi/10.1145/3536221.3556591), [github 💻](https://github.com/FIGLAB/DynaTags), [web-page 🌐](https://www.figlab.com/research/2022/dynatags)) | A low-cost dynamic paper-based fiducial marker

## 🚀 Contribution <a id="contribution"></a>

Please feel free to open [pull requests](https://github.com/alitourani/awesome-fiducial-marker/pulls) to update the list.
