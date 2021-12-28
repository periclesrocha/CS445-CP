# Image Based Lighting

## Recovering HDR maps

Here are the results obtained for all LDR images. Note that all images are displayed using three methods for comparison: linear log operation, Reinhard’s operator (Ld(x,y) = L(x,y) / 1+ L(x,y)), and tone mapping using an OpenCV library. 

- Naive LDR merging: computes the average of irradiance estimates. Image 1 includes the original images (second row) and respective log irradiances (third row).
 
![Naive LDR merging with log radiances](_readmeimages/image1.png "Image 1")</p>
</p>

- Weighted LDR merging: weighted average of irradiance estimates from LDR images. 
 
![Weighted LDR merging.](_readmeimages/image2.png "Image 2")</p>
</p>

- LDR merging with camera response function estimation: calibrates the photometric responses to obtain more accurate irradiance estimates from each image. Image 3 includes the original images (second row) and respective log irradiances (third row).

![Image 3: LDR merging with camera response function estimation.](_readmeimages/image3.png "Image 3")</p>
</p>

Here are the obtained plots for g versus intensity: 
 
![Image 4: plots for the camera response function estimation.](_readmeimages/image4.png "Image 4")</p>
</p>
The following, is a composite image that puts together the three HDR methods together for comparison: 

![Image 5: comparison of the results obtained from all three HDR methods.](_readmeimages/image5.png "Image 5")</p>
</p>

## Panoramic transformations

Here are the results obtained for the panoramic transformations of the sphere photography. 
- Normal and reflectance vectors: 
 
![Image 6: normal and reflectance vectors](_readmeimages/image6.png "Image 6")</p>
</p>

- Equirectangular image:
 
![Image 7: equirectangular image](_readmeimages/image7.png "Image 7")</p>

## Rendering synthetic objects

Here are the results obtained when rendering my empty background scene with synthetic 3-D objects: 

- Background image:

![Image 8: background image (empty)](_readmeimages/image8.png "Image 8")</p>

- Rendered image with objects: 
 
![Image 9: image rendered in Blender with all objects.](_readmeimages/image9.png "Image 9")</p>

- Rendered image with local geometry: 
 
![Image 10: rendering plane.](_readmeimages/image10.png "Image 10")</p>
 
- Rendered mask image: 
 
![Image 11: mask image.](_readmeimages/image11.png "Image 11")</p>

- Final composited result:
 
![Image 12: Final result.](_readmeimages/image12.png "Image 12")</p>

## Additional results

Here’s an additional result which uses the same objects, on a different environment map: 

- Background image: 
 
![Image 13: background image (empty).](_readmeimages/image13.png "Image 13")</p>

- Rendered image with objects: 
 
![Image 14: image rendered in Blender with all objects.](_readmeimages/image14.png "Image 14")</p>

- Rendered image with local geometry: 
 
![Image 15: rendering plane.](_readmeimages/image15.png "Image 15")</p>
 
- Rendered mask image: 
 
![Image 16: mask image.](_readmeimages/image16.png "Image 16")</p>

- Final composited result:
 
![Image 17: Final result.](_readmeimages/image17.png "Image 17")</p>

## Acknowledgments / Attribution

- All images used in this report by Pericles Rocha. 
- Synthetic 3-D objects obtained from http://www.turbosquid.com.
