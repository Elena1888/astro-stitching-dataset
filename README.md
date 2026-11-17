# Astronomical Image Stitching Dataset
## About the data
The dataset contains 15 pairs of overlapping images taken with the Hubble Space Telescope (HST) and obtained from the [Mikulski Archive for Space Telescopes (MAST)](https://archive.stsci.edu) in FITS format. The images come from the WFC3, ACS and WFPC2 instruments and show different types of objects: galaxy clusters, spiral and interacting galaxies, globular and open star clusters, emission nebulae and a supernova remnant.

Before stitching, the images were converted to 8-bit JPG images (percentile stretching, gamma correction, noise reduction and contrast enhancement). Each pair was stitched with eight methods: **SIFT, ORB, AKAZE, Astroalign, UDIS, DHS, ACDIS and RopStitch**. This gives 120 possible results; for 30 of them the method did not produce an output image, so **90 stitched images** are included. For five scenes a reference mosaic is also available.

## Data source
Hubble Space Telescope data obtained from the Mikulski Archive for Space Telescopes (MAST) at the Space Telescope Science Institute (STScI), operated by AURA for NASA/ESA. The original FITS files are available at MAST; this repository contains the preprocessed JPG images used in the experiments.

## Image pairs
### 1. Abell S1063
- **Telescope, instrument and filter:** HST/WFC3, F160W

| Input 1 | Input 2 |  
|---|---|
| <img src="AbellS1063/input1/0001.jpg" width="250"> | <img src="AbellS1063/input2/0001.jpg" width="250"> |

### 2. ACO S520
- **Telescope, instrument and filter:** HST/ACS-WFC, F814W
- **Reference mosaic:** available

| Input 1 | Input 2 |  
|---|---|
| <img src="ACOS520/input1/0001.jpg" width="250"> | <img src="ACOS520/input2/0001.jpg" width="250"> |

### 3. ARP 240
- **Telescope, instrument and filter:** HST/WFC3, F160W and F110W

| Input 1 | Input 2 |  
|---|---|
| <img src="ARP240/input1/0001.jpg" width="250"> | <img src="ARP240/input2/0001.jpg" width="250"> |

### 4. IC 4653
- **Telescope, instrument and filter:** HST/WFC3, F606W
-  **Reference mosaic:** available

| Input 1 | Input 2 |  
|---|---|
| <img src="IC4653/input1/0001.jpg" width="250"> | <img src="IC4653/input2/0001.jpg" width="250"> |

### 5. M101
- **Telescope, instrument and filter:** HST/WFC3, F555W
- **Reference mosaic:** available

| Input 1 | Input 2 |  
|---|---|
| <img src="M101/input1/0001.jpg" width="250"> | <img src="M101/input2/0001.jpg" width="250"> |

### 6. M17
- **Telescope, instrument and filter:** HST/WFC3, F160W

| Input 1 | Input 2 |  
|---|---|
| <img src="M17/input1/0001.jpg" width="250"> | <img src="M17/input2/0001.jpg" width="250"> |

### 7. M3
- **Telescope, instrument and filter:** HST/WFPC2, F555W

| Input 1 | Input 2 |  
|---|---|
| <img src="M3/input1/0001.jpg" width="250"> | <img src="M3/input2/0001.jpg" width="250"> |

### 8. M8
- **Telescope, instrument and filter:** HST/WFPC2, F814W and F675W

| Input 1 | Input 2 |  
|---|---|
| <img src="M8/input1/0001.jpg" width="250"> | <img src="M8/input2/0001.jpg" width="250"> |

### 9. NGC 1097
- **Telescope, instrument and filter:** HST/WFC3, F555W

| Input 1 | Input 2 |  
|---|---|
| <img src="NGC1097/input1/0001.jpg" width="250"> | <img src="NGC1097/input2/0001.jpg" width="250"> |

### 10. NGC 288
- **Telescope, instrument and filter:** HST/WFC3, F438W

| Input 1 | Input 2 |  
|---|---|
| <img src="NGC288/input1/0001.jpg" width="250"> | <img src="NGC288/input2/0001.jpg" width="250"> |

### 11. NGC 3201
- **Telescope, instrument and filter:** HST/WFC3, F606W

| Input 1 | Input 2 |  
|---|---|
| <img src="NGC3201/input1/0001.jpg" width="250"> | <img src="NGC3201/input2/0001.jpg" width="250"> |

### 12. NGC 6951
- **Telescope, instrument and filter:** HST/WFC3, F555W

| Input 1 | Input 2 |  
|---|---|
| <img src="NGC6951/input1/0001.jpg" width="250"> | <img src="NGC6951/input2/0001.jpg" width="250"> |

### 13. Omega Centauri
- **Telescope, instrument and filter:** HST/WFC3, F336W

| Input 1 | Input 2 |  
|---|---|
| <img src="Omega Centauri/input1/0001.jpg" width="250"> | <img src="Omega Centauri/input2/0001.jpg" width="250"> |

### 14. SNR 0509-68.7
- **Telescope, instrument and filter:** HST/WFC3, F814W
- **Reference mosaic:** available

| Input 1 | Input 2 |  
|---|---|
| <img src="SNR0509-68.7/input1/0001.jpg" width="250"> | <img src="SNR0509-68.7/input2/0001.jpg" width="250"> |

### 15. Stephan's Quintet
- **Telescope, instrument and filter:** HST/WFC3, F814W
- **Reference mosaic:** available

| Input 1 | Input 2 |  
|---|---|
| <img src="Stephan's Quintet/input1/0001.jpg" width="250"> | <img src="Stephan's Quintet/input2/0001.jpg" width="250"> |
