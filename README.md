# 2025 Oman Paleogeography
Repository of code and data associated with study of Tonian Shaat dikes of Oman as described in the manuscript:

## Oman was on the northern margin of a wide late Tonian Mozambique Ocean
Nicholas L. Swanson-Hysell<sup>1</sup>, Yiming Zhang<sup>1</sup>, Francis A. Macdonald<sup>2</sup>,  
Isabel Koran<sup>2</sup>, Adrian R. Tasistro-Hart<sup>2</sup>, Annabel F. Jay<sup>3</sup>  

---

<sup>1</sup> Department of Earth and Environmental Sciences, University of Minnesota, Minneapolis, MN, USA  
<sup>2</sup> Department of Earth and Planetary Science, University of California, Berkeley, CA, USA  
<sup>3</sup> Department of Geology, Carleton College, Northfield, MN, USA  

## Code

### dike_orientations.ipynb

This notebook aggregates structural orientation field data collected for planes of Shaat dikes and from the overlying Mesozoic-Cenozoic carbonates. Fisher means are calculated for the plane poles of dikes to derive the mean strike and dip of dike planes. These data are visualized for every dike for which data were collected and used to determine the overall orientation of the population. The stereonet used in the manuscript an output from this code:

<img src="code/output/orientation_stereonet.png" alt="Orientation Stereonet" width="250px" />

### dike_paleomagnetism.ipynb

This notebook conducts statistical tests and develops visualizations of the paleomagnetic directional data.

<img width="250px" alt="Screenshot 2025-04-22 at 12 09 33 PM" src="https://github.com/user-attachments/assets/0f594f77-4e15-44cd-ad01-b02cff7d6d8d" />

### dike_rock_magnetism.ipynb

This notebook using the `rockmagpy` library to visualize results from low temperature remanence experiments.

<img width="400" alt="Screenshot 2025-04-22 at 11 10 03 AM" src="https://github.com/user-attachments/assets/7f4c97e1-a6b2-4911-b6f6-261c53df8273" />

### MagIC_contribution.ipynb

This notebook imports the separate MagIC file exports for the paleomagnetic thermal demagnetization data and the rock magnetic experiments. The metadata for these files are enhanced and they are combined into a single MagIC contribution.

### prior_paleomagnetic_data.ipynb

This notebook compares previously published paleomagnetic data form Cryogenian/Ediacaran units to apparent polar wander paths and makes calculations associated with inclination shallowing and directional comparisons.

<img width="250px" alt="Screenshot 2025-04-22 at 12 11 33 PM" src="https://github.com/user-attachments/assets/63909e53-2039-4e3d-96bf-7f18e5ec9cd3" />

### zircon_U-Pb.ipynb

This notebook using the `radage` package to develop weighted mean U-Pb dates and data visualizations.

<img width="300px" alt="Screenshot 2025-04-22 at 10 08 37 AM" src="https://github.com/user-attachments/assets/8d0fe5a2-c6dc-4bbb-9109-fccb6ae854b5" />

## Data

The paleomagnetic data for this study will be available upon publication at: [10.7288/V4/MAGIC/20369](https://doi.org/10.7288/V4/MAGIC/20369)

### APWP

The file `Torsvik2012a_Gondwana_APWP.csv` provides context for the 540 Ma and onward apparent polar wander path (APWP) for Gondwana. The file `Vaes_APWP.xlsx` is a global apparent polar wander path that is used for the comparison of the Kilner et al. pole with the Cretaceous APWP. 

### field_data

This folder contains structural orientation data as well as additional metadata including higher precision GPS locations for the paleomagnetic sites.

### pmag

This folder contains paleomagnetic and rock magnetic data generated for project research.

#### demag

This folder is the data as analyzed in and exported from Demag_GUI.

#### demag_enhanced

This folder contains enhanced metadata that enriches the MagIC tables generated in the folder demag.

#### rockmag

This folder contains the MagIC file exported from the IRM database containing the results from rock magnetic experiments

### zircon_U-Pb

This folder contains the spreadsheet with U-Pb data: `LASS ICPMS U-Pb.xlsx`

This folder contains the `LASS ICPMS U-Pb.xlsx` spreadsheet with the U-Pb data.
