# art-generation-with-neural-style-transfer
Given a content image (ex: a landscape) and a style image (ex: a Monet painting), this project uses neural style transfer to "merge" to style into the content image (hopefully generating some art!).

## Getting started
After downloading the notebook, you can click on `run all cells` (or run each cell manually) to set up the project and generate your first results. If you want yo try with your own images, do the following:
1. in Section 4.1, change the path of `content_image ` to the desired content (loaded in the images directory, for instance).  
```py
content_image = Image.open("[PATH_TO_YOUR_IMAGE]")
```
2. In Section 5.2, you can do a similar process to defined what your style image will be.
3. Finally, in Section 5.6 (where the model is trained), feel free to change the `learning rate` and number of `epochs` to achieve better results. The default values are purposely low to allows quick demonstration. By changing those values you can get much better results (similar to those presented in the images embedded in the notebook).
