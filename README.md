# SLIDE: Single Image 3D Photography with Soft Layering and Depth-aware Inpainting
[ICCV 2021 Oral Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Jampani_SLIDE_Single_Image_3D_Photography_With_Soft_Layering_and_Depth-Aware_ICCV_2021_paper.pdf)

Single image 3D photography enables viewers to view a still image from novel viewpoints. Recent approaches combine monocular depth networks with inpainting networks to achieve compelling results. A drawback of these techniques is the use of hard depth layering, making them unable to model intricate appearance details such as thin hair-like structures. We present SLIDE, a modular and unified system for single image 3D photography that uses a simple yet effective soft layering strategy to better preserve appearance details in novel views. In addition, we propose a novel depth-aware training strategy for our inpainting module, better suited for the 3D photography task. The resulting SLIDE approach is modular, enabling the use of other components such as segmentation and matting for improved layering. At the same time, SLIDE uses an efficient layered depth formulation that only requires a single forward pass through the component networks to produce high quality 3D photos. Extensive experimental analysis on three view-synthesis datasets, in combination with user studies on in-the-wild image collections, demonstrate superior performance of our technique in comparison to existing strong baselines while being conceptually much simpler.

<img src="https://user-images.githubusercontent.com/29260006/137384500-b9439558-d5b4-4525-bcbd-f3e4a8f364f9.png" width="100%"/> 

Single image view synthesis with SLIDE (Ours) show better preservation of hair structures compared to that of 3D-Photo. We also show the novel view (Ours-No-BG) where the background (BG) layer is greyed-out to showcase our soft layering.

## Comparisons

## Run

## License


## Citing
```
@inproceedings{slide2021iccv,
	title = {SLIDE: Single Image 3D Photography with Soft Layering and Depth-aware Inpainting},
	author = {Jampani, Varun and Chang, Huiwen and Sargent, Kyle and Kar, Abhishek and Rucker, Richard and Krainin, Michael and Kaeser, Dominik and Freeman, William T and Salesin, David and Curless, Brian and Liu, Ce},
	booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  year={2021}
}
```
