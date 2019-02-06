# picfixR

#### DSCI-524 Collaborative Software Development Project  
  
#### Team Members

| Name                | Github.com Username |
| ------------------- | ------------------- |
| Miliban Keyim       | mkeyim              |
| George J. J. Wu     | GeorgeJJW           |
| Mani Kohli          | ksm45               |

#### Project Overview

Image enhancement is typically done with a full-scale editing software such as Adobe Photoshop or GIMP, but what if we just want to quickly touch up an image during prototyping in a programming environment? 

`picfixR` allows users to quickly enhance images in an integrated development environment (IDE) (e.g. Jupyter notebook, RStudio) without powering up an image editing software. Users can quickly adjust the sharpness, contrast, and vibrance of .png images, by simply calling the corresponding functions. This package currently offers three essential image enhancement functions, and we hope to implement additional features in the near future. 

#### Functions

###### sharpen
Given a .png image, darken the edges to get a sharpened effect, returns a .png image.

###### contrast
Given a .png image, make dark pixels much darker, and bright pixels slightly darker, returns a .png image.

###### vibrance
Given a .png image, increase the overall intensity and saturation by increasing more for colours that were less saturated to begin with, returns a .png image.

#### R ecosystem

[magick](https://cran.r-project.org/web/packages/magick/vignettes/intro.html) provides R with a comprehensive package with an overwhelming amount of functionality for complex image processing. However, even for basic image enhancements, users typically still have to dig into a substantial amount of documentation and implementation details. This project offers a simple alternative, allowing users to have the ability to enhance images quickly during prototyping without the overhead of heavy library resources.


