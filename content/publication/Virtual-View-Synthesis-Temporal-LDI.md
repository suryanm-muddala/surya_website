+++
abstract = "Depth-image-based rendering (DIBR) is a commonly used method for synthesizing additional views using video-plus-depth (V+D) format. A critical issue with DIBR based view synthesis is the lack of information behind foreground objects. This lack is manifested as disocclusions, holes, next to the foreground objects in rendered virtual views as a consequence of the virtual camera “seeing” behind the foreground object. The disocclusions are larger in the extrapolation case, i.e. the single camera case. Texture synthesis methods (inpainting methods) aim to fill these disocclusions by producing plausible texture content. However, virtual views inevitably exhibit both spatial and temporal inconsistencies at the filled disocclusion areas, depending on the scene content. In this paper we propose a layered depth image (LDI) approach that improves the spatio-temporal consistency. In the process of LDI generation, depth information is used to classify the foreground and background in order to form a static scene sprite from a set of neighboring frames. Occlusions in the LDI are then identified and filled using inpainting, such that no disocclusions appear when the LDI data is rendered to a virtual view. In addition to the depth information, optical flow is computed to extract the stationary parts of the scene and to classify the occlusions in the inpainting process. Experimental results demonstrate that spatio-temporal inconsistencies are significantly reduced using the proposed method. Furthermore, subjective and objective qualities are improved compared to state-of-the-art reference methods."
abstract_short = ""
authors = ["**Suryanarayana M. Muddala**", "Roger Olsson", "Mårten Sjöström"]
date = "2016-01-22"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *Journal on Image and Video Processing*, EURASIP."
publication_short = "In *EURASIP*"
selected = false
title = "Spatio-Temporal Consistent Depth-Image Based Rendering Using Layered Depth Image and Inpainting"
url_code = ""
url_dataset = ""
url_pdf = "http://miun.diva-portal.org/smash/get/diva2:896962/FULLTEXT01.pdf"
url_project = "project/freeview-rendering-ldi/"
url_slides = ""
url_video = ""

+++
