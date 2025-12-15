# Free-Water_Elimination_and_Mapping_from_Diffusion_MRI_review
In this paper a way of restoring and separating meaningful signal from noisy and distorted data in Diffusion MRI via the Beltrami framework is proposed. A significant drawback of DTI (Diffusion Tensor Imaging) of the brain is that in each voxel, the mean water displacement is being represented. Hence, in voxels that represent partial brain tissue areas such as areas on the contour of the brain that are in direct contact with free water or areas around an edema in the brain, the isotropic diffusion of the free water volume dominates the signal, and hence the water diffusion of the brain tissue in that area is mixed with a high signal contributed by the free water compartment.
In this review, I will mainly focus on the mathematical framework proposed in the paper. I will present the [mathematical approach to this problem and derive in detail the calculations omitted from the paper](./Free_Water_Elimination_and_Mapping_from_Diffusion_MRI-4.pdf).

Along the theoretical methematical derivations, you can find an implementation of the optimization algorithm proposed in the paper in the notebook below.



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/GabrielSamberg/Free-Water_Elimination_and_Mapping_from_Diffusion_MRI_review/blob/main/dMRI_project.ipynb
)
