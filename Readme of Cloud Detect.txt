cd ./CloudDetect
(1) CMD command for the cloud detect workflow on the Windows platform:

mainThinDetectPublic.exe --Year 2020 --inputName .\Data\GF1_PMS1_E112.9_N30.8_20200625_L1A0004889881-MSS1_TOA.tif --inputXMLName .\Data\GF1_PMS1_E112.9_N30.8_20200625_L1A0004889881-MSS1.xml --saveName .\Data\GF1_PMS1_E112.9_N30.8_20201026_L1A0005235887-MSS1_Mask.tif --modelName .\model\PixelCloud.tar --shadowModel .\model\PixelShadow.tar --model64Name .\model\Scene64Cloud.pth --model128Name .\model\Scene128Cloud.pth --model256Name .\model\Scene256Cloud.pth

--Year
Year of the input image acquisition (e.g., 2020).

--inputName
Path to the input TOA (Top of Atmosphere) image to be processed.

--inputXMLName
Path to the corresponding metadata XML file of the input image.

--saveName
Path where the output cloud mask will be saved.

--modelName
Path to the pixel-level cloud detection model.

--shadowModel
Path to the pixel-level shadow detection model.

--model64Name
Path to the scene-level cloud detection model with 64×64 input size.

--model128Name
Path to the scene-level cloud detection model with 128×128 input size.

--model256Name
Path to the scene-level cloud detection model with 256×256 input size.