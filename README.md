## Large Human Brain Slab: NPBB299 Nuclei + Colors corrected (2023-01-19)

Neuroglancer ID: [NPBB299-2 Slab 5color (corrected)](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B9.000000000000001e-7%2C%22m%22%5D%2C%22z%22:%5B7.95e-7%2C%22m%22%5D%7D%2C%22position%22:%5B18761.60546875%2C33395.9375%2C245.5%5D%2C%22crossSectionScale%22:103.13880002210429%2C%22projectionScale%22:33962.264150943396%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu//ng/globus/bil/hillman/2023_01_19_largeSlab_NPBB299_2_tiff_corrected.omezans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22#uicontrol%20bool%20sytog24_visable%20checkbox%28default=true%29%3B%5Cn%5Cn#uicontrol%20invlerp%20sytog24_lut%20%28range=%5B0%2C6782%5D%2Cwindow=%5B0%2C10964%5D%29%3B%5Cn%5Cn#uicontrol%20vec3%20sytog24_color%20color%28default=%5C%22#008000%5C%22%29%3B%5Cn%5Cnvec3%20sytog24%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cnif%20%28sytog24_visable%20==%20true%29%5Cnsytog24%20=%20sytog24_color%20%2A%20%28%28toNormalized%28getDataValue%280%29%29%20+%20sytog24_lut%28%29%29%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28sytog24%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22sytog24_lut%22:%7B%22range%22:%5B0%2C8101%5D%7D%7D%2C%22name%22:%222023_01_19_largeSlab_NPBB299_2_tiff_corrected.omezans%22%7D%2C%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu//ng/globus/bil/hillman/2023_04_13_largeSlab_NPBB299_2_tiff_revised_Camera1_tiff_fused.omehans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22#uicontrol%20bool%20neun_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20nnos_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20iba1_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20acta2_visable%20checkbox%28default=false%29%3B%5Cn%5Cn#uicontrol%20invlerp%20neun_lut%20%28range=%5B0%2C2475%5D%2Cwindow=%5B0%2C5945%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20nnos_lut%20%28range=%5B0%2C10475%5D%2Cwindow=%5B0%2C11575%5D%2Cchannel=%5B1%5D%29%3B%5Cn#uicontrol%20invlerp%20iba1_lut%20%28range=%5B0%2C10833%5D%2Cwindow=%5B0%2C11552%5D%2Cchannel=%5B2%5D%29%3B%5Cn#uicontrol%20invlerp%20acta2_lut%20%28range=%5B0%2C65535%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B3%5D%29%3B%5Cn%5Cn#uicontrol%20vec3%20neun_color%20color%28default=%5C%22#800080%5C%22%29%3B%5Cn#uicontrol%20vec3%20nnos_color%20color%28default=%5C%22#00FF00%5C%22%29%3B%5Cn#uicontrol%20vec3%20iba1_color%20color%28default=%5C%22#0000FF%5C%22%29%3B%5Cn#uicontrol%20vec3%20acta2_color%20color%28default=%5C%22#FFFFFF%5C%22%29%3B%5Cn%5Cnvec3%20neun%20=%20vec3%280%29%3B%5Cnvec3%20nnos%20=%20vec3%280%29%3B%5Cnvec3%20iba1%20=%20vec3%280%29%3B%5Cnvec3%20acta2%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cnif%20%28neun_visable%20==%20true%29%5Cnneun%20=%20neun_color%20%2A%20%28%28toNormalized%28getDataValue%280%29%29%20+%20neun_lut%28%29%29%29%3B%5Cn%5Cnif%20%28nnos_visable%20==%20true%29%5Cnnnos%20=%20nnos_color%20%2A%20%28%28toNormalized%28getDataValue%281%29%29%20+%20nnos_lut%28%29%29%29%3B%5Cn%5Cnif%20%28iba1_visable%20==%20true%29%5Cniba1%20=%20iba1_color%20%2A%20%28%28toNormalized%28getDataValue%282%29%29%20+%20iba1_lut%28%29%29%29%3B%5Cn%5Cnif%20%28acta2_visable%20==%20true%29%5Cnacta2%20=%20acta2_color%20%2A%20%28%28toNormalized%28getDataValue%283%29%29%20+%20acta2_lut%28%29%29%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28neun%20+%20nnos%20+%20iba1%20+%20acta2%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22neun_lut%22:%7B%22range%22:%5B54%2C1841%5D%2C%22window%22:%5B0%2C2411%5D%7D%2C%22nnos_lut%22:%7B%22range%22:%5B211%2C3413%5D%2C%22window%22:%5B0%2C4154%5D%7D%2C%22iba1_lut%22:%7B%22range%22:%5B170%2C3247%5D%2C%22window%22:%5B0%2C5946%5D%7D%7D%2C%22channelDimensions%22:%7B%22c%5E%22:%5B1%2C%22%22%5D%7D%2C%22name%22:%222023_04_13_largeSlab_NPBB299_2_tiff_revised_Camera1_tiff_fused.omehans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%222023_04_13_largeSlab_NPBB299_2_tiff_revised_Camera1_tiff_fused.omehans%22%7D%2C%22layout%22:%22xy%22%7D) <br>

Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 546 - NeuN <br>
   Alexa Fluor 594 - nNOS <br>
   Alexa Fluor 647 - Iba-1 <br>
   iFluo Styramide 790 - ACTA2 <br>

Date of imaging: 2023-01-19


   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/large_human_slab_npbb299_nuclei_and_colors_corr.png?raw=true)


-------------


## Large Human Brain Slab: AZ21-JC4A NPY (2023-03-14)

Neuroglancer ID: [AZ21_JC4A NPY slab](https://neuroglancer-demo.appspot.com/#!%7B"dimensions":%7B"x":%5B0.000002%2C"m"%5D%2C"y":%5B0.00000154%2C"m"%5D%2C"z":%5B0.00000134%2C"m"%5D%7D%2C"position":%5B15109.5%2C16577.5%2C175.5%5D%2C"crossSectionScale":57.46268656716418%2C"projectionScale":34477.611940298506%2C"layers":%5B%7B"type":"image"%2C"source":"precomputed://https://brain-api.cbi.pitt.edu//ng/globus/bil/hillman/2023_03_14_largeSlab_AZ21-JC4A_NPY_tiff_revised_tiff_stacks_fused.omehans"%2C"tab":"rendering"%2C"shader":"#uicontrol%20bool%20autof_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20npy_visable%20checkbox%28default=true%29%3B%5Cn%5Cn#uicontrol%20invlerp%20autof_lut%20%28range=%5B0%2C65535%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20npy_lut%20%28range=%5B0%2C65535%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B1%5D%29%3B%5Cn%5Cn#uicontrol%20vec3%20autof_color%20color%28default=%5C"green%5C"%29%3B%5Cn#uicontrol%20vec3%20npy_color%20color%28default=%5C"red%5C"%29%3B%5Cn%5Cnvec3%20autof%20=%20vec3%280%29%3B%5Cnvec3%20npy%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cnif%20%28autof_visable%20==%20true%29%5Cnautof%20=%20autof_color%20%2A%20%20autof_lut%28%29%3B%5Cn%5Cnif%20%28npy_visable%20==%20true%29%5Cnnpy%20=%20npy_color%20%2A%20%20npy_lut%28%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28autof%20+%20npy%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D"%2C"shaderControls":%7B"autof_lut":%7B"range":%5B0%2C2307%5D%7D%2C"npy_lut":%7B"range":%5B0%2C1189%5D%2C"window":%5B353%2C6298%5D%7D%7D%2C"channelDimensions":%7B"c%5E":%5B1%2C""%5D%7D%2C"name":"2023_03_14_largeSlab_AZ21-JC4A_NPY_tiff_revised_tiff_stacks_fused.omehans"%7D%5D%2C"selectedLayer":%7B"visible":true%2C"layer":"2023_03_14_largeSlab_AZ21-JC4A_NPY_tiff_revised_tiff_stacks_fused.omehans"%7D%2C"layout":"xy"%7D) <br>

Label: <br>
   Alexa Fluor 647 - NPY <br>
   ( + Autofluorescence excited by 488nm laser) <br>
   
Imaged at at the bottom of a 5mm thick sample (5mm deep) <br>
Date of imaging: 2023-01-25


   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/large_human_slab_npy.png?raw=true)


-------------


## Large Human Brain Slab: NPBB299 Nuclei - corrected (2023-01-19)

Neuroglancer ID: [NPBB299-2 Slab nuclei-only (corrected)](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B9.000000000000001e-7%2C%22m%22%5D%2C%22z%22:%5B7.95e-7%2C%22m%22%5D%7D%2C%22position%22:%5B21207.724609375%2C33457.63671875%2C247.5%5D%2C%22crossSectionScale%22:91.10594001952546%2C%22projectionScale%22:39.75%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%7B%22url%22:%22precomputed://https://brain-api.cbi.pitt.edu/ng/globus/bil/hillman/2023_01_19_largeSlab_NPBB299_2_tiff_corrected.omezans%22%2C%22transform%22:%7B%22matrix%22:%5B%5B1%2C0%2C0.88%2C0%5D%2C%5B0%2C1%2C0%2C0%5D%2C%5B0%2C0%2C1%2C0%5D%5D%2C%22outputDimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B9.000000000000001e-7%2C%22m%22%5D%2C%22z%22:%5B7.95e-7%2C%22m%22%5D%7D%7D%7D%2C%22tab%22:%22rendering%22%2C%22shader%22:%22//%20Init%20for%20each%20channel:%5Cn%5Cn//%20Channel%20visability%20check%20boxes%5Cn#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn%5Cn//%20Lookup%20tables%5Cn#uicontrol%20invlerp%20lut_0%20%28range=%5B0%2C65535%5D%2Cwindow=%5B0%2C65535%5D%29%3B%5Cn%5Cn//%20Colors%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22green%5C%22%29%3B%5Cn%5Cn//RGB%20vector%20at%200%20%28ie%20channel%20off%29%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cn//%20For%20each%20color%2C%20if%20visable%2C%20get%20data%2C%20adjust%20with%20lut%2C%20then%20apply%20to%20color%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%28%28toNormalized%28getDataValue%280%29%29%20+%20lut_0%28%29%29%29%3B%5Cn%5Cn//%20Add%20RGB%20values%20of%20all%20channels%5Cnvec3%20rgb%20=%20%28channel0%29%3B%5Cn%5Cn//Retain%20RGB%20value%20with%20max%20of%201%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5Cn//%20Render%20the%20resulting%20pixel%20map%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22lut_0%22:%7B%22range%22:%5B0%2C8937%5D%7D%7D%2C%22name%22:%222023_01_19_largeSlab_NPBB299_2_tiff_corrected.omezans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%222023_01_19_largeSlab_NPBB299_2_tiff_corrected.omezans%22%7D%2C%22layout%22:%22xy%22%7D) <br>

Label: <br>
   SytoG24 - nuclei <br>
   (not shown) Alexa Fluor 546 - NeuN <br>
   (not shown) Alexa Fluor 594 - nNOS <br>
   (not shown) Alexa Fluor 647 - Iba-1 <br>
   (not shown) iFluo Styramide 790 - ACTA2 <br>

Date of imaging: 2023-01-19

   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/large_human_slab_npbb299_nuclei_corr.png?raw=true)

   

-------------


## Large Human Brain Slab: NPBB299 Nuclei + Colors (uncorrected)

Neuroglancer ID: [NPBB299-2 Slab 5color (before correction)](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B0.0000014299999999999999%2C%22m%22%5D%2C%22z%22:%5B0.0000012629999999999998%2C%22m%22%5D%7D%2C%22position%22:%5B20345.71484375%2C21298.7109375%2C137.5%5D%2C%22crossSectionScale%22:86.16292890825164%2C%22projectionScale%22:63.14999999999999%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%7B%22url%22:%22precomputed://https://brain-api.cbi.pitt.edu/ng/globus/bil/hillman/2023_01_19_largeSlab_NPBB299_2_tiff/2023_01_19_largeSlab_NPBB299_2_tiff_colors2.omezans%22%2C%22transform%22:%7B%22matrix%22:%5B%5B1%2C0%2C0.88%2C0%2C0%5D%2C%5B0%2C1%2C0%2C0%2C0%5D%2C%5B0%2C0%2C1%2C0%2C0%5D%2C%5B0%2C0%2C0%2C1%2C0%5D%5D%2C%22outputDimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B0.0000014299999999999999%2C%22m%22%5D%2C%22z%22:%5B0.0000012629999999999998%2C%22m%22%5D%2C%22c%5E%22:%5B1%2C%22%22%5D%7D%7D%7D%2C%22tab%22:%22rendering%22%2C%22shader%22:%22//%20Init%20for%20each%20channel:%5Cn%5Cn//%20Channel%20visability%20check%20boxes%5Cn#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel1_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel2_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel3_visable%20checkbox%28default=true%29%3B%5Cn%5Cn//%20Lookup%20tables%5Cn#uicontrol%20invlerp%20lut_0%20%28range=%5B0%2C15365%5D%2Cwindow=%5B0%2C23047%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_1%20%28range=%5B0%2C15365%5D%2Cwindow=%5B0%2C23047%5D%2Cchannel=%5B1%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_2%20%28range=%5B0%2C15365%5D%2Cwindow=%5B0%2C23047%5D%2Cchannel=%5B2%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_3%20%28range=%5B0%2C15365%5D%2Cwindow=%5B0%2C23047%5D%2Cchannel=%5B3%5D%29%3B%5Cn%5Cn//%20Colors%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22green%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel1_color%20color%28default=%5C%22red%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel2_color%20color%28default=%5C%22purple%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel3_color%20color%28default=%5C%22blue%5C%22%29%3B%5Cn%5Cn//RGB%20vector%20at%200%20%28ie%20channel%20off%29%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cnvec3%20channel1%20=%20vec3%280%29%3B%5Cnvec3%20channel2%20=%20vec3%280%29%3B%5Cnvec3%20channel3%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cn//%20For%20each%20color%2C%20if%20visable%2C%20get%20data%2C%20adjust%20with%20lut%2C%20then%20apply%20to%20color%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%28%28toNormalized%28getDataValue%280%29%29%20+%20lut_0%28%29%29%29%3B%5Cn%5Cnif%20%28channel1_visable%20==%20true%29%5Cnchannel1%20=%20channel1_color%20%2A%20%28%28toNormalized%28getDataValue%281%29%29%20+%20lut_1%28%29%29%29%3B%5Cn%5Cnif%20%28channel2_visable%20==%20true%29%5Cnchannel2%20=%20channel2_color%20%2A%20%28%28toNormalized%28getDataValue%282%29%29%20+%20lut_2%28%29%29%29%3B%5Cn%5Cnif%20%28channel3_visable%20==%20true%29%5Cnchannel3%20=%20channel3_color%20%2A%20%28%28toNormalized%28getDataValue%283%29%29%20+%20lut_3%28%29%29%29%3B%5Cn%5Cn//%20Add%20RGB%20values%20of%20all%20channels%5Cnvec3%20rgb%20=%20%28channel0%20+%20channel1%20+%20channel2%20+%20channel3%29%3B%5Cn%5Cn//Retain%20RGB%20value%20with%20max%20of%201%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5Cn//%20Render%20the%20resulting%20pixel%20map%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22lut_0%22:%7B%22range%22:%5B0%2C61%5D%2C%22window%22:%5B0%2C200%5D%7D%2C%22lut_1%22:%7B%22range%22:%5B0%2C191%5D%2C%22window%22:%5B1%2C518%5D%2C%22channel%22:%5B0%5D%7D%2C%22lut_2%22:%7B%22range%22:%5B0%2C758%5D%2C%22window%22:%5B0%2C1000%5D%2C%22channel%22:%5B3%5D%7D%2C%22lut_3%22:%7B%22range%22:%5B0%2C980%5D%2C%22window%22:%5B0%2C2000%5D%7D%7D%2C%22crossSectionRenderScale%22:0.125%2C%22channelDimensions%22:%7B%22c%5E%22:%5B1%2C%22%22%5D%7D%2C%22name%22:%222023_01_19_largeSlab_NPBB299_2_tiff_colors2.omezans%22%7D%2C%7B%22type%22:%22image%22%2C%22source%22:%7B%22url%22:%22precomputed://https://brain-api.cbi.pitt.edu/ng/globus/bil/hillman/2023_01_19_largeSlab_NPBB299_2_tiff/2023_01_19_largeSlab_NPBB299_2_tiff_nuc.omezans%22%2C%22transform%22:%7B%22matrix%22:%5B%5B1%2C0%2C0.88%2C0%5D%2C%5B0%2C1%2C0%2C0%5D%2C%5B0%2C0%2C1%2C0%5D%5D%2C%22outputDimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B0.0000014299999999999999%2C%22m%22%5D%2C%22z%22:%5B0.0000012629999999999998%2C%22m%22%5D%7D%7D%7D%2C%22tab%22:%22rendering%22%2C%22shader%22:%22//#uicontrol%20invlerp%20normalized%5Cn#uicontrol%20bool%20channel_NUC_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20invlerp%20lut_NUC%20%28range=%5B0%2C1571%5D%2Cwindow=%5B0%2C2356%5D%29%3B%5Cn#uicontrol%20vec3%20channel_NUC_color%20color%28default=%5C%22green%5C%22%29%3B%5Cnvec3%20channel_NUC%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cnif%20%28channel_NUC_visable%20==%20true%29%5Cnchannel_NUC%20=%20channel_NUC_color%20%2A%20%28%28toNormalized%28getDataValue%28%29%29%20+%20lut_NUC%28%29%29%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28channel_NUC%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%5Cn%22%2C%22shaderControls%22:%7B%22lut_NUC%22:%7B%22range%22:%5B0%2C1182%5D%7D%2C%22channel_NUC_color%22:%22#ffffff%22%7D%2C%22name%22:%222023_01_19_largeSlab_NPBB299_2_tiff_nuc.omezans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%222023_01_19_largeSlab_NPBB299_2_tiff_colors2.omezans%22%7D%2C%22layout%22:%22xy%22%7D) <br>

Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 546 - NeuN <br>
   Alexa Fluor 594 - nNOS <br>
   Alexa Fluor 647 - Iba-1 <br>
   iFluo Styramide 790 - ACTA2 <br>

Date of imaging: 2023-01-19

   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/large_human_slab_npbb299_nuclei_and_colors.png?raw=true)

   
   
-------------


## (Combinatorial Slide) Small Human Brain Sample 1: Nuclei + Colors

Neuroglancer ID: [Combinatorial Slide Human 1](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B7e-7%2C%22m%22%5D%2C%22z%22:%5B6.18e-7%2C%22m%22%5D%7D%2C%22position%22:%5B1535.51220703125%2C3002.915771484375%2C214.5%5D%2C%22crossSectionScale%22:15.059710595610103%2C%22projectionScale%22:12465.949718925523%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu/ng/public_h20/holis/brainpi_links/2023_01_22_combinatorialSlide_humanBrain1_tiff_Alan/tiff_stacks_fused_colors.omezans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22//%20Init%20for%20each%20channel:%5Cn%5Cn//%20Channel%20visability%20check%20boxes%5Cn#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel1_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel2_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel3_visable%20checkbox%28default=true%29%3B%5Cn%5Cn//%20Lookup%20tables%5Cn#uicontrol%20invlerp%20lut_0%20%28range=%5B0%2C562%5D%2Cwindow=%5B0%2C843%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_1%20%28range=%5B0%2C562%5D%2Cwindow=%5B0%2C843%5D%2Cchannel=%5B1%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_2%20%28range=%5B0%2C562%5D%2Cwindow=%5B0%2C843%5D%2Cchannel=%5B2%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_3%20%28range=%5B0%2C562%5D%2Cwindow=%5B0%2C843%5D%2Cchannel=%5B3%5D%29%3B%5Cn%5Cn//%20Colors%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22green%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel1_color%20color%28default=%5C%22red%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel2_color%20color%28default=%5C%22purple%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel3_color%20color%28default=%5C%22blue%5C%22%29%3B%5Cn%5Cn//RGB%20vector%20at%200%20%28ie%20channel%20off%29%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cnvec3%20channel1%20=%20vec3%280%29%3B%5Cnvec3%20channel2%20=%20vec3%280%29%3B%5Cnvec3%20channel3%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cn//%20For%20each%20color%2C%20if%20visable%2C%20get%20data%2C%20adjust%20with%20lut%2C%20then%20apply%20to%20color%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%28%28toNormalized%28getDataValue%280%29%29%20+%20lut_0%28%29%29%29%3B%5Cn%5Cnif%20%28channel1_visable%20==%20true%29%5Cnchannel1%20=%20channel1_color%20%2A%20%28%28toNormalized%28getDataValue%281%29%29%20+%20lut_1%28%29%29%29%3B%5Cn%5Cnif%20%28channel2_visable%20==%20true%29%5Cnchannel2%20=%20channel2_color%20%2A%20%28%28toNormalized%28getDataValue%282%29%29%20+%20lut_2%28%29%29%29%3B%5Cn%5Cnif%20%28channel3_visable%20==%20true%29%5Cnchannel3%20=%20channel3_color%20%2A%20%28%28toNormalized%28getDataValue%283%29%29%20+%20lut_3%28%29%29%29%3B%5Cn%5Cn//%20Add%20RGB%20values%20of%20all%20channels%5Cnvec3%20rgb%20=%20%28channel0%20+%20channel1%20+%20channel2%20+%20channel3%29%3B%5Cn%5Cn//Retain%20RGB%20value%20with%20max%20of%201%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5Cn//%20Render%20the%20resulting%20pixel%20map%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22channel0_visable%22:false%2C%22channel1_visable%22:false%2C%22channel2_visable%22:false%2C%22channel3_visable%22:false%2C%22lut_0%22:%7B%22range%22:%5B4%2C42%5D%2C%22window%22:%5B0%2C161%5D%7D%2C%22lut_1%22:%7B%22range%22:%5B14%2C154%5D%2C%22window%22:%5B3%2C849%5D%7D%2C%22lut_2%22:%7B%22range%22:%5B234%2C1456%5D%2C%22window%22:%5B0%2C2509%5D%7D%2C%22lut_3%22:%7B%22range%22:%5B201%2C2731%5D%2C%22window%22:%5B0%2C4185%5D%7D%7D%2C%22channelDimensions%22:%7B%22c%5E%22:%5B1%2C%22%22%5D%7D%2C%22name%22:%22tiff_stacks_fused_colors.omezans%22%7D%2C%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu/ng/public_h20/holis/brainpi_links/2023_01_22_combinatorialSlide_humanBrain1_tiff_Alan/tiff_stacks_fused_nuclei.omezans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22//#uicontrol%20invlerp%20normalized%5Cn#uicontrol%20bool%20channel_NUC_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20invlerp%20lut_NUC%20%28range=%5B0%2C1571%5D%2Cwindow=%5B0%2C2356%5D%29%3B%5Cn#uicontrol%20vec3%20channel_NUC_color%20color%28default=%5C%22green%5C%22%29%3B%5Cnvec3%20channel_NUC%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cnif%20%28channel_NUC_visable%20==%20true%29%5Cnchannel_NUC%20=%20channel_NUC_color%20%2A%20%28%28toNormalized%28getDataValue%28%29%29%20+%20lut_NUC%28%29%29%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28channel_NUC%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22name%22:%22tiff_stacks_fused_nuclei.omezans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%22tiff_stacks_fused_colors.omezans%22%7D%2C%22layout%22:%22xy%22%7D) <br>

Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 546 - NeuN <br>
   Alexa Fluor 594 - GAD1 & ACTA2 <br>
   Alexa Fluor 647 - PV & ALDH1L1 <br>
   iFluo Styramide 790 - nNOS & Iba-1 <br>

Date of imaging: 2023-01-14


   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/small_human_slab_combinatorial_1.png?raw=true)


-------------


## (Combinatorial Slide) Small Human Brain Sample 2: Nuclei + Colors

Neuroglancer ID: [Combinatorial Slide Human 2](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B7e-7%2C%22m%22%5D%2C%22z%22:%5B6.18e-7%2C%22m%22%5D%7D%2C%22position%22:%5B1828.5819091796875%2C3359.9150390625%2C314.5%5D%2C%22crossSectionScale%22:11.023176380641601%2C%22projectionScale%22:16384%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu//ng/public_h20/holis/brainpi_links/2023_01_22_combinatorialSlide_humanBrain2_tiff_Alan/tiff_stacks_fused_colors.omezans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel1_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel2_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel3_visable%20checkbox%28default=true%29%3B%5Cn%5Cn#uicontrol%20invlerp%20channel0_lut%20%28range=%5B0%2C1411%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20channel1_lut%20%28range=%5B0%2C2882%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B1%5D%29%3B%5Cn#uicontrol%20invlerp%20channel2_lut%20%28range=%5B0%2C11558%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B2%5D%29%3B%5Cn#uicontrol%20invlerp%20channel3_lut%20%28range=%5B0%2C65239%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B3%5D%29%3B%5Cn%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22green%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel1_color%20color%28default=%5C%22red%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel2_color%20color%28default=%5C%22purple%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel3_color%20color%28default=%5C%22blue%5C%22%29%3B%5Cn%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cnvec3%20channel1%20=%20vec3%280%29%3B%5Cnvec3%20channel2%20=%20vec3%280%29%3B%5Cnvec3%20channel3%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%20channel0_lut%28%29%3B%5Cn%5Cnif%20%28channel1_visable%20==%20true%29%5Cnchannel1%20=%20channel1_color%20%2A%20%20channel1_lut%28%29%3B%5Cn%5Cnif%20%28channel2_visable%20==%20true%29%5Cnchannel2%20=%20channel2_color%20%2A%20%20channel2_lut%28%29%3B%5Cn%5Cnif%20%28channel3_visable%20==%20true%29%5Cnchannel3%20=%20channel3_color%20%2A%20%20channel3_lut%28%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28channel0%20+%20channel1%20+%20channel2%20+%20channel3%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22channel3_visable%22:false%2C%22channel1_lut%22:%7B%22range%22:%5B0%2C1599%5D%7D%2C%22channel2_lut%22:%7B%22range%22:%5B0%2C3629%5D%7D%2C%22channel3_lut%22:%7B%22range%22:%5B0%2C3460%5D%7D%7D%2C%22channelDimensions%22:%7B%22c%5E%22:%5B1%2C%22%22%5D%7D%2C%22name%22:%22%20tiff_stacks_fused_colors.omezans%22%7D%2C%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu//ng/public_h20/holis/brainpi_links/2023_01_22_combinatorialSlide_humanBrain2_tiff_Alan/tiff_stacks_fused_nuclei.omezans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn%5Cn#uicontrol%20invlerp%20channel0_lut%20%28range=%5B0%2C28193%5D%2Cwindow=%5B0%2C65535%5D%29%3B%5Cn%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22green%5C%22%29%3B%5Cn%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%20channel0_lut%28%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28channel0%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22channel0_lut%22:%7B%22range%22:%5B0%2C3334%5D%2C%22window%22:%5B1194%2C7140%5D%7D%7D%2C%22name%22:%22tiff_stacks_fused_nuclei.omezans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%22%20tiff_stacks_fused_colors.omezans%22%7D%2C%22layout%22:%22xy%22%7D) <br>


Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 546 - NeuN <br>
   Alexa Fluor 594 - GAD1 & ACTA2 <br>
   Alexa Fluor 647 - PV & ALDH1L1 <br>
   iFluo Styramide 790 - nNOS & Iba-1 <br>

Date of imaging: 2023-01-14

   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/small_human_slab_combinatorial_2.png?raw=true)


-------------


## Whole Mouse Brain viral labeled: Nuclei + Colors 

Neuroglancer ID: [Whole Mouse Brain - viral label - SR3B6](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B7.7e-7%2C%22m%22%5D%2C%22z%22:%5B6.800000000000001e-7%2C%22m%22%5D%7D%2C%22position%22:%5B3145%2C7311.99658203125%2C-4290.99951171875%5D%2C%22crossSectionScale%22:50%2C%22projectionScale%22:24993.236434227092%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%7B%22url%22:%22precomputed://https://brain-api.cbi.pitt.edu/ng/public_h20/holis/brainpi_links/out_trim_lighting8.omezans%22%2C%22transform%22:%7B%22matrix%22:%5B%5B1%2C0%2C0%2C0%2C0%5D%2C%5B0%2C1%2C0%2C0%2C0%5D%2C%5B0%2C0%2C-1%2C0%2C0%5D%2C%5B0%2C0%2C0%2C1%2C0%5D%5D%2C%22outputDimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B7.7e-7%2C%22m%22%5D%2C%22z%22:%5B6.800000000000001e-7%2C%22m%22%5D%2C%22c%5E%22:%5B1%2C%22%22%5D%7D%7D%7D%2C%22tab%22:%22rendering%22%2C%22shader%22:%22//%20Init%20for%20each%20channel:%5Cn%5Cn//%20Channel%20visability%20check%20boxes%5Cn#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel1_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel2_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel3_visable%20checkbox%28default=true%29%3B%5Cn%5Cn//%20Lookup%20tables%5Cn#uicontrol%20invlerp%20lut_0%20%28range=%5B0%2C63304%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_1%20%28range=%5B0%2C63304%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B1%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_2%20%28range=%5B0%2C63304%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B2%5D%29%3B%5Cn#uicontrol%20invlerp%20lut_3%20%28range=%5B0%2C63304%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B3%5D%29%3B%5Cn%5Cn//%20Colors%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22green%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel1_color%20color%28default=%5C%22red%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel2_color%20color%28default=%5C%22purple%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel3_color%20color%28default=%5C%22blue%5C%22%29%3B%5Cn%5Cn//RGB%20vector%20at%200%20%28ie%20channel%20off%29%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cnvec3%20channel1%20=%20vec3%280%29%3B%5Cnvec3%20channel2%20=%20vec3%280%29%3B%5Cnvec3%20channel3%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cn//%20For%20each%20color%2C%20if%20visable%2C%20get%20data%2C%20adjust%20with%20lut%2C%20then%20apply%20to%20color%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%28%28toNormalized%28getDataValue%280%29%29%20+%20lut_0%28%29%29%29%3B%5Cn%5Cnif%20%28channel1_visable%20==%20true%29%5Cnchannel1%20=%20channel1_color%20%2A%20%28%28toNormalized%28getDataValue%281%29%29%20+%20lut_1%28%29%29%29%3B%5Cn%5Cnif%20%28channel2_visable%20==%20true%29%5Cnchannel2%20=%20channel2_color%20%2A%20%28%28toNormalized%28getDataValue%282%29%29%20+%20lut_2%28%29%29%29%3B%5Cn%5Cnif%20%28channel3_visable%20==%20true%29%5Cnchannel3%20=%20channel3_color%20%2A%20%28%28toNormalized%28getDataValue%283%29%29%20+%20lut_3%28%29%29%29%3B%5Cn%5Cn//%20Add%20RGB%20values%20of%20all%20channels%5Cnvec3%20rgb%20=%20%28channel0%20+%20channel1%20+%20channel2%20+%20channel3%29%3B%5Cn%5Cn//Retain%20RGB%20value%20with%20max%20of%201%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5Cn//%20Render%20the%20resulting%20pixel%20map%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22channel3_visable%22:false%2C%22lut_0%22:%7B%22range%22:%5B151%2C1033%5D%2C%22window%22:%5B0%2C5945%5D%7D%2C%22lut_1%22:%7B%22range%22:%5B109%2C957%5D%2C%22window%22:%5B0%2C6451%5D%7D%2C%22lut_2%22:%7B%22range%22:%5B79%2C384%5D%2C%22window%22:%5B0%2C2061%5D%7D%2C%22lut_3%22:%7B%22range%22:%5B96%2C141%5D%2C%22window%22:%5B54%2C676%5D%7D%7D%2C%22channelDimensions%22:%7B%22c%5E%22:%5B1%2C%22%22%5D%7D%2C%22name%22:%22out_trim_lighting8.omezans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%22out_trim_lighting8.omezans%22%7D%2C%22layout%22:%224panel%22%7D) <br>

Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 594 - Ctip2 <br>
   Alexa Fluor 647 - Viral tracing & weak NeuN <br>
   Alexa Fluor 790 - vanished NeuN <br>

Date of imaging: 2023-12-09

   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/whole_mouse_brain.png?raw=true)


-------------


## (Combinatorial Slide) Mouse Brain Section: Nuclei + Colors

neuroglancer ID: [Combinatorial Slide Mouse brain (first scan)](https://neuroglancer-demo.appspot.com/#!%7B%22dimensions%22:%7B%22x%22:%5B0.000002%2C%22m%22%5D%2C%22y%22:%5B7e-7%2C%22m%22%5D%2C%22z%22:%5B6.18e-7%2C%22m%22%5D%7D%2C%22position%22:%5B3522.23974609375%2C3913.805908203125%2C228.5%5D%2C%22crossSectionScale%22:17.057924622859353%2C%22projectionScale%22:33980.58252427185%2C%22layers%22:%5B%7B%22type%22:%22image%22%2C%22source%22:%22precomputed://https://brain-api.cbi.pitt.edu//ng/public_h20/holis/brainpi_links/hillman2023_01_22_combinatorialSlide_mouseBrain_tiff_Alan_multicolor_tiff_stack_2.omezans%22%2C%22tab%22:%22rendering%22%2C%22shader%22:%22#uicontrol%20bool%20channel0_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel1_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel2_visable%20checkbox%28default=true%29%3B%5Cn#uicontrol%20bool%20channel3_visable%20checkbox%28default=true%29%3B%5Cn%5Cn#uicontrol%20invlerp%20channel0_lut%20%28range=%5B0%2C1571%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B0%5D%29%3B%5Cn#uicontrol%20invlerp%20channel1_lut%20%28range=%5B0%2C4648%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B1%5D%29%3B%5Cn#uicontrol%20invlerp%20channel2_lut%20%28range=%5B0%2C65535%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B2%5D%29%3B%5Cn#uicontrol%20invlerp%20channel3_lut%20%28range=%5B0%2C65535%5D%2Cwindow=%5B0%2C65535%5D%2Cchannel=%5B3%5D%29%3B%5Cn%5Cn#uicontrol%20vec3%20channel0_color%20color%28default=%5C%22#FF0000%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel1_color%20color%28default=%5C%22#00FF00%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel2_color%20color%28default=%5C%22#FF00FF%5C%22%29%3B%5Cn#uicontrol%20vec3%20channel3_color%20color%28default=%5C%22#FF00FF%5C%22%29%3B%5Cn%5Cnvec3%20channel0%20=%20vec3%280%29%3B%5Cnvec3%20channel1%20=%20vec3%280%29%3B%5Cnvec3%20channel2%20=%20vec3%280%29%3B%5Cnvec3%20channel3%20=%20vec3%280%29%3B%5Cn%5Cn%5Cnvoid%20main%28%29%20%7B%5Cn%5Cnif%20%28channel0_visable%20==%20true%29%5Cnchannel0%20=%20channel0_color%20%2A%20%20channel0_lut%28%29%3B%5Cn%5Cnif%20%28channel1_visable%20==%20true%29%5Cnchannel1%20=%20channel1_color%20%2A%20%20channel1_lut%28%29%3B%5Cn%5Cnif%20%28channel2_visable%20==%20true%29%5Cnchannel2%20=%20channel2_color%20%2A%20%20channel2_lut%28%29%3B%5Cn%5Cnif%20%28channel3_visable%20==%20true%29%5Cnchannel3%20=%20channel3_color%20%2A%20%20channel3_lut%28%29%3B%5Cn%5Cnvec3%20rgb%20=%20%28channel0%20+%20channel1%20+%20channel2%20+%20channel3%29%3B%5Cn%5Cnvec3%20render%20=%20min%28rgb%2Cvec3%281%29%29%3B%5Cn%5CnemitRGB%28render%29%3B%5Cn%7D%22%2C%22shaderControls%22:%7B%22channel2_lut%22:%7B%22range%22:%5B0%2C34751%5D%7D%2C%22channel3_lut%22:%7B%22range%22:%5B0%2C13946%5D%7D%7D%2C%22crossSectionRenderScale%22:0.0625%2C%22channelDimensions%22:%7B%22c%5E%22:%5B1%2C%22%22%5D%7D%2C%22name%22:%22hillman2023_01_22_combinatorialSlide_mouseBrain_tiff_Alan_multicolor_tiff_stack_2.omezans%22%7D%5D%2C%22selectedLayer%22:%7B%22visible%22:true%2C%22layer%22:%22hillman2023_01_22_combinatorialSlide_mouseBrain_tiff_Alan_multicolor_tiff_stack_2.omezans%22%7D%2C%22layout%22:%22xy%22%7D) <br>

Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 546 - NeuN <br>
   Alexa Fluor 594 - GAD1 & ACTA2 <br>
   Alexa Fluor 647 - PV & ALDH1L1 <br>
   iFluo Styramide 790 - nNOS & Iba-1 <br>

Date of imaging: 2023-01-14

   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/large_mouse_brain_slab_combinatorial_1.png?raw=true)


-------------


## (Combinatorial Slide) Mouse Brain Section: Nuclei + Colors - reimaged

Neuroglancer ID: [Combinatorial Slide Mouse brain (re-scan)](https://brain-api.cbi.pitt.edu/ng/globus/bil/hillman/2023_04_04_combinatorialSlide_mouse_tiff_nuclei_and_colors.omehans) <br>

Label: <br>
   SytoG24 - nuclei <br>
   Alexa Fluor 546 - NeuN <br>
   Alexa Fluor 594 - GAD1 & ACTA2 <br>
   Alexa Fluor 647 - PV & ALDH1L1 <br>
   iFluo Styramide 790 - nNOS & Iba-1 <br>

Date of imaging: 2023-04-04

   ![thumbnail](https://github.com/CBI-PITT/holis_images/blob/master/thumbnails/large_mouse_brain_slab_combinatorial_2_corr.png?raw=true)

   
