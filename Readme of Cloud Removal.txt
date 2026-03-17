cd ./CloudRemoval\JointCloudRemoval

(1) CMD command for the thin cloud removal workflow on the Windows platform:

JointCloudRemoval.exe ThinRemoval ..\Data\GF1_PMS1_E112.9_N30.8_20200625_L1A0004889881-MSS1_TOA.tif ..\Data\GF1_PMS1_E112.9_N30.8_20201026_L1A0005235887-MSS1_Mask.tif ..\Data\GF1_PMS1_E112.9_N30.8_20201026_L1A0005235887-MSS1_Mask.tif_Clear.tif ..\Data\GF1_PMS1_E112.9_N30.8_20200625_L1A0004889881-MSS1_Thin.tif 3 0


(2) CMD command for the thick cloud removal workflow on the Windows platform:

JointCloudRemoval.exe ThickRemoval ..\Data\GF1_PMS1_E112.9_N30.8_20200625_L1A0004889881-MSS1_Thin.tif ..\Data\GF1_PMS1_E112.9_N30.8_20201026_L1A0005235887-MSS1_Mask.tif ..\Data\GF1_PMS1_E112.9_N30.8_20201026_L1A0005235887-MSS1_TOA.tif ..\Data\GF1_PMS1_E112.9_N30.8_20200625_L1A0004889881-MSS1_JTTR.tif