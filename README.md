# Modeling Irregular Boundaries Using Isoparametric Elements in Material Point Method
> Ezra Y. S. Tjung, Shyamini Kularathna, Krishna Kumar, and Kenichi Soga

## Abstract
The Material Point Method (MPM) is a hybrid Eulerian-Lagrangian approach capable of
simulating large deformation problems of history-dependent materials. While the MPM can
represent complex and evolving material domains by using Lagrangian points, boundary
conditions are often applied to the Eulerian nodes of the background mesh nodes. Hence, the use
of a structured mesh may become prohibitively restrictive for modeling complex boundaries such
as a landslide topography. We study the suitability of unstructured background mesh with
isoparametric elements to model irregular boundaries in the MPM. An inverse mapping
algorithm is used to transform the material points from the global coordinates to the local natural
coordinates. Dirichlet velocity and frictional boundary conditions are applied in the local
coordinate system at each boundary node. This approach of modeling complex boundary
conditions is validated by modeling the dynamics of a gravity-driven rigid block sliding on an
inclined plane. This method is later applied to a flume test of controlled debris flow on an
inclined plane conducted by the United States Geological Survey (USGS).
