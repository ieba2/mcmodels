# C/S Inocean Cat I Drillship (CSAD) - WAMIT

---

## 1. Input Data

### 1.1 Mesh name and dimensions
- **Mesh name**: `CSAD.gdf`
- **Length**: $2.578 \, \text{m}$
- **Width**: $0.440 \, \text{m}$
- **Draft**: $0.142 \, \text{m}$

### 1.2 Input parameters and problem scope
- Radiation and diffraction, equations of motion, and mean drift forces.
- $6$ degrees of freedom.
- Infinite water depth.
- Water density: $1000 \, \text{kg/m}^3$.

### 1.3 Environmental Conditions
- **Range of period**: from $0.3 \, \text{s}$ to $3 \, \text{s}$ with a $0.05 \, \text{s}$ increment.
- **Direction of incident waves**: from $0^\circ$ to $180^\circ$ with a $10^\circ$ increment.

### 1.4 Mass matrix
- $x_G = 0 \, \text{m}$, $y_G = 0 \, \text{m}$, $z_G = -0.033 \, \text{m}$
- $I_{xx} = 2.53 \, \text{kg} \, \text{m}^2$, $I_{yy} = 60.69 \, \text{kg} \, \text{m}^2$, $I_{zz} = 61.85 \, \text{kg} \, \text{m}^2$
- $I_{xy} = I_{xz} = 0 \, \text{kg} \, \text{m}^2$, $I_{yz} = -0.56 \, \text{kg} \, \text{m}^2$
- $M = 127.92 \, \text{kg}$
