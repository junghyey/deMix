# deMix
<p align="center">
<img align="right" 
 src="https://github.com/seungjinna/deMix/assets/102386164/01bfe68e-e402-42d7-a695-8bad4b11c4d8"/> 
</p> 

## Introduction 
One of the most popular methods for examining protein conformational changes and dynamics is hydrogen/deuterium exchange (HDX) with mass spectrometry (MS). We previously developed a fully automated algorithm to analyze deuterated isotopic distributions in-depth called deMix (Na et al. 2019 [1]). Here, we introduce the graphical user interface(GUI) version of deMix. The software automatically analyzes HDX data and facilitates the interrogation of data and results. deMix offers visualization of isotopic cluster distributions and sequence coverage maps in heat map form to compare deuteration rates over time.</br>

## What deMix  provides:
1. Peptide centric view (Deuterated Distributions)</br>
- Allows users to compare a natural isotope distribution and the corresponding deuterated isotope distribution in one of HDX experiments across D2O labeling with theoretical, aggregated (over elution time spans), and manually annotated distributions for the chosen peptide.</br>
- Offers a deuteration rate (or deuterium uptake) plot across D2O labeling time for the selected peptide.</br>
2. Protein centric view (Dynamics)</br>
 - Allows users to view the dynamics of the protein.</br>
 - Offers sequence coverage maps for HDX-MS data. Visually represents the HDX rate of each D2O labeling times within the HDX-MS dataset using colors (= Heat Map).</br>
 - Provides interactive protein 3D structure feature that maps the HDX rate onto the structure (integration with Jmol [2]).
3. User-friendly environment</br>
  - Includes intuitive and interactive GUI or features.</br>
  - Allows users to focus more on analysis rather than spend time adapting to the software.</br>

## How to start
1. Download the deMix file based on your OS.</br>
  - [Windows](https://www.dropbox.com/scl/fi/m1k2yqxzjibfym1blk9fr/deMix_ver2_windows.zip?rlkey=zt945f5u0ulkhf433lz6x7257&dl=0)
  - [macOS](https://www.dropbox.com/scl/fi/9tpxvwt2hwpgtkyzmx7nl/deMix_ver2_macos.zip?rlkey=u2g4lsp8lcwwo9fkty3x27ahf&dl=0)
  - [Linux](https://www.dropbox.com/scl/fi/e0m1riji04ozhjava1dvx/deMix_ver2_linux.zip?rlkey=u03fgqukpd1o8kx6y1uufa8ka&dl=0)
2. Requirement(s) </br>
  - Java Version >= 17 </br>
    To check (type this in the command prompt) = java - version
    Download java here: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
3. To run:</br>
  - **Windows:** </br>
  1. Download Windows version. & Extract the compressed file.</br>
  2. Double Click the bat file. → Run anyway/Run</br>
  - **macOS:** </br>
  1. Download Windows version. & Extract the compressed file.</br>
  2. Right-click the deMix → Open with Terminal/Open. </br>
  - **Linux:** </br>
  1. Download the linux version. & Extract the compressed file.</br>
  2. Double Click the .sh</br>

## Data Availability
Download [toy data](https://drive.google.com/drive/folders/14hrLwB3J0-TqThkVecsHuYoMv-T384M-?usp=drive_link)

## Reference:
[1] Na, S., Lee, JJ., Joo, J.W.J. et al. deMix: Decoding Deuterated Distributions from Heterogeneous Protein States via HDX-MS. Sci Rep 9, 3176 (2019). [https://doi.org/10.1038/s41598-019-39512-8](https://doi.org/10.1038/s41598-019-39512-8) </br>
[2] https://jmol.sourceforge.net/

