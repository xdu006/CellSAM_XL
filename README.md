# CellSAM_XL
CellSAM_XL is a tool for quantitative analysis of large-scale flourescent microscopy images. 

### Web Demo URL
Live demo for testing can be found at [https://huggingface.co/spaces/XDU006/CellSAM_XL](https://huggingface.co/spaces/XDU006/CellSAM_XL). 

### Repo Directory

#### CellSAM_XL_Gradio.ipynb
Code to create your own instance of the web interface. Simply run the file from beginning to end and your own instance of the web interface will be created with a sharable link. 

#### CellSAM_Pipeline_Western4.ipynb
Full code with ICR and enhancement trials, preliminary tests, and functions. Not recommending for running from beginning to end and only serves as a reference until proper curation and conversion to a proper github repo with best practices is completed.

#### Demo Images
A set of demo images for use in web interface. Western 4 Left is recommended for best visualization effects. 

### Abstract
Microscopy imaging, renowned for its ability to convey vast amounts of information, has become indispensable in both research and clinical settings. It provides a unique window into cellular life, offering both qualitative and quantitative insights. While fluorescence microscopy delivers valuable data across various fields related to human health, the extraction of this data is often time-consuming and complex due to the large size and volume of images, as well as the expertise required for accurate analysis. CellSAM, a foundational model for cell segmentation, offers automation but is not optimized for quantification and performs poorly on large images. Thus, this study aims to address these limitations by designing a pipeline that enhances CellSAM’s utility for accurate, large-scale quantification tasks. We demonstrate that the image-to-cell size ratio (ICR) significantly influences CellSAM's performance, and by optimizing the ICR, we tile large images to fit appropriately within CellSAM’s input space. Additionally, we show and incorporate image enhancement techniques to boost detection accuracy. The pipeline is completed with channel-specific analysis to differentiate different cell types, and the extracted data is output as a versatile CSV file suitable for downstream applications. Ultimately, we present a fully functional, open-source pipeline with an interactive web interface, tailored for large-scale fluorescence microscopy quantification.
