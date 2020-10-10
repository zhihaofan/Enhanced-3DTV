# Enhanced-3DTV

The motivation map of Enhanced-3DTV is as follows. 

![motivation of Enhanced 3DTV](https://github.com/andrew-pengjj/Enhanced-3DTV/blob/master/Img/3DTVandOurs.png)

The matlab code of paper ''Enhanced 3DTV Regularization and Its Applications on Hyper-spectral Image Denoising and Compressed Sensing''

## There are Two tasks: Compress sensing & Denoising 
### structure 
  #### Compress sensing
  The structure of Compress sensing is:
  * compared method 
    * JtenRe3DTV   
    * KSC
    * LR&TV
    * SLNTCS
    * SpaRCS
  * Enhanced3DTV in the paper
    * demo_EnhancedTV_CS.m
    * EnhancedTV_CS.m
    * quality assess
  * quality assess
  * demo.m

```bash
# run "demo.m" in command line window of matlab to test all codes
$ demo.m
# run the code inside "Enhanced3DTV in the paper" to see the performances of Enhanced 3DTV in compress sensing tasks.
$ demo_EnhancedTV_CS.m
```
  #### denoising
  The structure of Denoising is:
  * compete code
    * ALM_RPCA
    * BM4D
    * LLRT
    * LRTDTV
    * LRTV
    * TDL
    * WNNM
    * WSNM_RPCA
  * Enhanced3DTV in the paper
    * EnhancedTV.m
    * TV_operator
    * quality assess
    * simulation_case1_demo.m
    * simulation_case2_demo.m
    * simulation_case3_demo.m
    * simulation_case4_demo.m
    * simulation_case5_demo.m
    * simulation_case6_demo.m
  * quality assess
  * Demo_simulation_case1.m
  * Demo_simulation_case3.m
  * RunAllMethod.m

API of all methods are list in "RunAllMethod.m"  
```bash
# run "Demo_simulation_case1.m" and "Demo_simulation_case3.m"to test all the code. For example,
$ Demo_simulation_case3.m
# run the code inside "Enhanced3DTV in the paper" to see the performances of Enhanced 3DTV in Denoise tasks. For example,
$ simulation_case3_demo.m
```

### supplemental.pdf
Here, we show some visual restoration of all methods
The denoising performance of all methods on IndianPines simulation data.
![IndianPines](https://github.com/andrew-pengjj/Enhanced-3DTV/blob/master/Img/indian_pines_denosing.png)
The compress sensing restore  performance of all methods on dcmall data.
![cs_dc_160](https://github.com/andrew-pengjj/Enhanced-3DTV/blob/master/Img/cs_dc_160.png)
The compress sensing restore  performance of all methods on lowal altitude data.
![cs_lowal_80](https://github.com/andrew-pengjj/Enhanced-3DTV/blob/master/Img/cs_lowal_80.png)

More experiment results and the proof of the equivalence are list in supplemental.pdf

