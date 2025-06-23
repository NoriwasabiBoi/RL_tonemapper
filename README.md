# rl_tonemapper

## About

Custom MATLAB tonemapper for a university project.  
Includes a simple GUI with a saturation slider that controls the strength of desaturation and resaturation.  
Visualizes the 4 main steps of the pipeline in a 2x2 layout:  
1. Normalize  
2. Desaturate  
3. Tonemap (Reinhard + Log)  
4. Resaturate  

Meant for exploring basic color manipulation techniques in an HDR workflow.

---

## Credits

- The `remap` function is adapted from:
  **Vlad Atanasiu (2025).** *Remap numerical values*. [MATLAB Central File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/54404-remap-numerical-values). Accessed June 23, 2025.
