This project contains notebooks to analyze 3D difference equations that explore parasitoid-host population dynamics.
These models are extensions of models analyzed by Kelsey Marcinko and Mark Kot, in which they analyzed 2D models (referenced below).
We extend two of these models, by adding a third parameter for the time-lagged host. 

Model 1 explores the dynamics induced by Beverton-Holt growth and fractional parasitism.
Model 2 explores the dynamics induced by Ricker growth and fractional parasitism.
The governing equations of each model are given at the top of each notebook.

For each model, we seek classifications of the bifurcations, detection of chaos, and numerical depictions of strange attractors.

We determine the fixed points of the map, and the eigenvalues of the community matrix to guide our experiments. When necessary, we use the jury conditions to complete our stability analysis.

The most interesting behavior is found in Model 2, where we use Ricker growth. We find local and global transcritical bifurcations, where we see the collision of fixed points, and the collision of invariant circles with a fixed point, respectively. We
also identify evidence of a cycle fold bifurcation, suggested by the difference in bifurcation diagrams when changing the direction over which we sample the bifurcation parameter. We also find chaotic behavior in this model.

The following figures depict chaos, and a cyclic fold bifurcation in Model 2.

![rf1](https://user-images.githubusercontent.com/55065632/197676365-273bdf71-1956-4140-8d25-6f8ed9cad291.png)
![rf2_fwd](https://user-images.githubusercontent.com/55065632/197676379-036f8d95-a129-4e27-86de-77fdc3c6b350.png)
![rf2_rev](https://user-images.githubusercontent.com/55065632/197676389-4e92058f-13bb-43ec-b19b-634721fb37d2.png)

## References
[A comparative analysis of host-parasitoid models with density dependence preceding parasitism](https://www.tandfonline.com/doi/full/10.1080/17513758.2020.1783005)
