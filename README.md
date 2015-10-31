# Excise Digit Recogniser

Quite fast and simple prototype for recognise digit on Kazakh excise labels

See notebooks:
1. Number segmentation -- [Number segmentation](01-NumberSegmentation.ipynb)
2. Contour Number Heuristic analysis and number sorting -- [Number Heuristic Analysis](02-NumberHeuristicAnalysis.ipynb)
3. Number recognition -- [Number recognition](03-NumberRecognition.ipynb)
4. Speedify Tesseract number recognition -- [Speedify Tesseract Number recognition](04-SpeedifyTesseractNumberRecognition.ipynb)
5. Number recognition tests -- [Number recognition tests](05-NumberRecognitionTests.ipynb)
6. Increase robustness of segmentation -- [Threshold robustness](06-ThresholdRobustness.ipynb)
7. Selective search for object detection -- [Selective search](07-SelectiveSearch(ObjectSegmentation).ipynb)
8. Barcode detector -- [Barcode detector](08-BarcodeDetector.ipynb)
9. Barcode detector tests -- [Barcode detector tests](09-BarcodeDetectorTests.ipynb)
10. Crop masked image  -- [Masked crop](10-MaskedCropTests.ipynb)
11. Anti glare system. Step 1. CLAHE  -- [Clahe](11-CLAHE.ipynb)
12. Anti glare system. Step 2. Specularity highlight detection, Image Inpainting and noise reduction -- [Full Reflection Rediction](12-FullReflectionRediction.ipynb)
13. Barcode Detection on masked image  -- [Masked barcode segmentation](13-MaskedBarcodeSegmentation.ipynb)
14. Kuwahara and Skeleton filter for Segmentation Number and Serial on masked image  -- [Masked serial number segmentation](14-MaskedSerialNumberKuwaharaSegmentation.ipynb)
15. Watershed Segmentation Number and Serial on masked image  -- [Masked serial number segmentation](15-MaskedSerialNumberWatershedSegmentation.ipynb)
16. Gaussian Mixture Model segmentation -- [GMM serial number segmentation](16-MaskedSerialNumberGMMSegmentation.ipynb)
17. K-Nearest segmentation -- [KNN serial number segmentation](17-KNNSegmentation.ipynb)
18. SciKit segmentation(Thresholds, Denoising and Сlarity) -- [SciKit segmentation](18-SciKitSegmentationThreshold.ipynb)
19. SciKit segmentation(Chain Vesa, Active Contour Model and Geodesic) -- [SciKit segmentation](19-SciKitSegmentation.ipynb)
20. Heuristic morphology segmentation Number and Serial on masked image  -- [Morphology masked serial number segmentation](20-MaskedSerialNumberMorphologySegmentation.ipynb)
21. Segmentation speedify -- [Segmentation Speedify Dataset Tests](21-SegmentationSpeedifyDatasetTests.ipynb)
22. Image segmentation with real mobile data -- [Morphology masked serial number segmentation](22-MobileSerialNumberSegmentation.ipynb)
23. Heuristic Mobile Serial Number Text Extracting -- [Heuristic text extracting](23-MobileSerialNumberTextExtracting.ipynb)
24. Clearness (preciseness) detection -- [Clearness detection](24-BlurDetection.ipynb)
25. Detecting thik lines on barcdes -- [Detecting thik lines](25-ThikLinesDetection.ipynb)
26. Heuristic analysis thik lines on barcdes -- [Detecting thik lines](26-ThikLinesHeuristicDetection.ipynb)
27. Crop number -- [Crop number tests](27-MobileCropNumber.ipynb)
28. Heuristic analysis of number -- [Mobile Heuristic Number Segmentation](28-MobileHeuristicNumberSegmentation.ipynb)
29. Stroke Width Transform by Boris Epshtein -- [SWT Number Segmentation](29-SWTNumberSegmentation.ipynb)
30. Region Filter Number Segmentation -- [RF Number Segmentation](30-RegionFilterNumberSegmentation.ipynb)
31. Histohram analysis of number -- [Mobile Histohram Number Segmentation](31-MobileHistohramNumberSegmentation.ipynb)
32. Heuristic number recognition-- [Mobile Heuristic Number Recognition](32-MobileHeuristicNumberRecognition.ipynb)

### Улучшения 

https://habrahabr.ru/post/278435/
https://habrahabr.ru/post/128768/

#### Play Vision Scanner Notes (если не работает фокусировка)
https://gist.github.com/Gericop/7de0b9fdd7a444e53b5a !!!!!!!!

### OpenCV iOS
https://medium.com/ios-os-x-development/the-fd4fcb249358

#### K-nearest recognition
http://pythonopencv.com/simple-digit-recognition-aka-optical-character-recognitionocr-in-opencv-python/
https://github.com/openpaperwork/pyocr

34. Text recognition over NN and backend
https://cloud.google.com/vision/docs/detecting-text
https://cloud.google.com/vision/pricing
https://cloud.google.com/vision/docs/detecting-text
https://cloud.google.com/vision/

43. 3D марка и маркеры
https://docs.opencv.org/3.1.0/d9/d6d/tutorial_table_of_content_aruco.html 
ArUco marker detection opencv


http://libdmtx.sourceforge.net/ !!!!!!!!!!!!


### Barcode Zxing, Zbar recognition (Failed)
https://github.com/pethoalpar/ZxingExample !!!! <----
https://stackoverflow.com/questions/13576161/convert-opencv-image-into-pil-image-in-python-for-use-with-zbar-library

### Recognition Barcode on masked image with Zebra (Failed)
https://github.com/v2e4lisp/pdf417-text-mode-decoder 
https://jdbates.blogspot.com/?view=sidebar
https://medium.com/@yushulx/raspberry-pi-barcode-scanner-in-python-927839100c6b
https://demo.dynamsoft.com/DBR/BarcodeReaderDemo.aspx
https://www.inliteresearch.com/barcode-recognition-sdk.php
https://partnerportal.zebra.com/PartnerPortal/product_services/downloads_z/software/Scanner_SDK_Linux_Fact_Sheet.pdf !!!!

https://www.dynamsoft.com/CustomerPortal/LoginOrRegister.aspx?op=4DD608F3803493E4&product=8BC841D35BACD076 !!!!!!!!!!!!!!!!!
--> https://www.zebra.com/ru/ru/products/software/scanning-systems/scanner-drivers-and-utilities/scanner-sdk-for-linux.html !!!!!

### OpenMV Barcode reader (Failed)
https://www.pyimagesearch.com/2018/03/19/reading-barcodes-with-python-and-openmv/?__s=z8qigk95cahgicgoz8zo

### Google Barcode reader (Failed)
https://developers.google.com/vision/android/barcodes-overview