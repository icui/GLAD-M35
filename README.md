# GLAD-M35
GLAD-M35 model at a resolution for visualization purposes

---
### Coordinate data
```latitude.npy``` array of latitude values (deg)
```longitude.npy``` array of longitude values (deg)
```depth.npy``` array of depth values (deg)

### Model data
3D array with dimension: (depth x latitude x longtidue)
```vpv.npy``` Vertially polarized P-wave velcoity (km/s)
```vph.npy``` Horizontally polarized P-wave velcoity (km/s)
```vsv.npy``` Vertially polarized S-wave velcoity (km/s)
```vsh.npy``` Horizontally polarized S-wave velcoity (km/s)
```eta.npy``` Dimensionless parameter

```std(vp).npy```  Standard deviation of P-wave velcoity (km/s)
```std(vs).npy``` Standard deviation of S-wave velcoity (km/s)

### Uncertainty values

---
## netCDF file download link
Same format as the numpy arrays, but bundled in netCDF-v3 classic format. Can be used by Specfem3D-Globe for low-resolution simulation
https://1drv.ms/u/c/6aa54e88b62ecf65/ER2lG67lZF9PsvEQM_Wy8aMByeldmERhWzcBg7uiYiY61Q?e=LSYgIE

---
IRIS EMC repository (available soon)
