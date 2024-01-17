# FURION: A software for X-ray beamline system design
## 1. Brief introduction 
The **F**ourier optics-based **U**ltrashort x-**R**ay pulse propagat**ION** package (**FURION**) is a comprehensive optical simulation software primarily used for the design of synchrotron radiation and free-electron laser beamline systems. FURION not only has the capability to simulate ultra-short X-ray pulse propagation, but also possesses some other functionalities, such as particle tracing in four-dimensional phase space, particle tracing in six-dimensional phase space, wavefront propagation, pulse propagation based on six-dimensional matrixes, etc. FURION is also capable of calculating optical properties of materials, including reflectivity, complex refractive index, attenuation coefficient, reflectivity of multilayer, and rocking curve of crystal.

## 2. Features of FURION

### &emsp;2.1. Ray tracing in 4-D phase space: 
FURION can provide geometric ray tracing simulation in the (x, x', y, y') phase space, capable of describing the evolution of transverse beam profile and divergence in beamline systems.
<p align="center">
<img src="https://github.com/Furion-Chuan/Furion.github.io/blob/main/figure1.jpg" width="800px">

### &emsp;2.2. Ray tracing in 6-D phase space: 
FURION can also provide geometric ray tracing simulation in the (x, x', y, y', t, E) phase space, capable of describing the evolution of pulse properties in beamline systems, such as transverse beam profile, divergence, pulse duration, and dispersion. This 6-D phase-space ray tracing can assess the propagation of ultra-short pulses in dispersive beamline systems.
<p align="center">
<img src="https://github.com/Furion-Chuan/Furion.github.io/blob/main/figure2.jpg" width="500px">

### &emsp;2.3. Wavefront propagation：
FURION can provide wavefront propagation based on Fourier optics. In this module, the beam passes through optical elements by using local ray tracing method. FURION offers various free-space propagation models, including the Fresnel propagator, angular spectrum propagator, Kirchhoff integral propagator, Rayleigh-Sommerfeld integral propagator, and Collins integral propagator.

<p align="center">
<img src="https://github.com/Furion-Chuan/Furion.github.io/blob/main/figure3.tif" width="200px">

### &emsp;2.4. Pulse propagation：
FURION is capable of providing ultra-short pulse propagation based on Fourier optics. In this module, it can simulate the propagation of 2D and 3D pulses in beamline systems. It is able to assess dispersive beamline systems and describe the spatiotemporal coupling effects generated by pulses passing through dispersive optical elements, such as pulse front tilt, pulse front rotation, pulse compression, and pulse stretching. This module can invoke 3D FEL pulses generated by Genesis 1.3 and perform start-to-end simulations of FEL beamline systems.

### &emsp;2.5. Pulse propagation base on K matrixes: 
The FURION team developed K-matrixes for different types of X-ray optical elements. Based on the K-matrix method, FURION provides 6-D phase-space ray tracing module and pulse propagation module. It is important to note that the ray tracing here is limited to describing linear transmission and cannot account for higher-order aberrations and astigmatism effects associated with different-shaped curved mirrors, distinguishing it from the direct tracing in sections 2.1 and 2.2. The pulse propagation module based on the K-matrix can rapidly construct the 3-D optical field after passing through beamline systems, but the assessment of diffraction effects requires integration with modules based on Fourier optics.

### &emsp;2.6. X-ray optics: 
- **Mirrors**: FURION is capable of providing various types of mirrors, including planar mirror, spherical mirror, ellipsoidal mirror, toroidal mirror, parabolic mirror, cylindrical mirror, elliptical cylindrical mirror, and parabolic cylindrical mirror.
- **Gratings**: FURION can provide different types of gratings, including toroidal grating, spherical grating, cylindrical grating, planar grating, toroidal VLS grating, spherical VLS grating, cylindrical VLS grating, planar VLS grating, and so on.
- **Crystals**: FURION can provide different types of crystals operating in either Bragg or Laue cases, either in reflection or transmission.
- **Multilayers**: FURION can provide periodic and non-periodic multilayers.

### &emsp;2.7. Optical properties of materials: 
- **Crystals**: FURION calculates the reflectivity and transmissivity of crystals using dynamical theory of X-ray diffraction. 
- **Multilayers**: FURION employs dynamical diffraction theory and matrix iteration method to calculate the reflectivity and transmissivity of multilayers. Typically, periodic multilayers and asymmetry-cut multilayers use the dynamical diffraction method, while periodic and non-periodic multilayers use the matrix iteration method.
- **Gratings**: The efficiency of gratings is calculated using Rigorous Coupled Wave Analysis (RCWA) method.
- **Others**: FURION is also capable of calculating the reflectivity of mirrors, complex refractive index, attenuation coefficient, and so on.


## 3. Software Development Progress and Updates 
Currently, our research and development team is actively working on developing the FURION user interface, with the aim of making it available to professionals in the X-ray community in the near future. If you have any related questions or discussions, please feel free to send your inquiries to:  yangc@mail.iasf.ac.cn.


