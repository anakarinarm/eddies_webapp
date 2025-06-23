## Exploración interactiva de remolinos ciclónicos y anticlónicos

Repositorio webapp:

Este notebook nos permite explorar interactivamente los remolinos durante el año 2018 del producto de AVISO [Global mesoscale eddy trajectory product]([https://www.aviso.altimetry.fr/en/data/products/value-added-products/global-mesoscale-eddy-trajectory-product.html) y los perfiles de [Argo](https://argo.ucsd.edu/) más cercanos a estos remolinos en tiempo (dentro de una ventana de 15 días) y espacio (dentro de hasta 0.25 grados de distancia al contorno inicial del remolino). Usamos [Argopy](https://argopy.readthedocs.io/en/latest/index.html) para obtener estos perfiles.
1. Selecciona si deseas explorar los remolinos ciclónicos o anticlónicos.
2. Elige un remolino específico (número entre 1-223241 para ciclónicos y 1-25471 para anticiclónicos)
3. Carga los datos para ver sus características (toma un poco de tiempo, ya que la base de datos es grande).  
4. Visualiza la ubicación y forma del remolino en un mapa y/o los perfiles de Argo más cercanos al remolino. 