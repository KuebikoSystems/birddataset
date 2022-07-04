# Kuebiko's entry for the Hackaday Competition.

OrnithoNet - a audio detection model based on the tensorflow framework and deployed on the NRF52840 on the Nano33 BLE Sense.
This repo a database and codenotebooks.

Following execution protocols for the repo : 

1. Fetch data from xeno canto
2. Convert it into a dataset
3. Run that dataset through a tensorflow model
4. Run that model , convert it to tensorflow lite.
5. Run inference on NanoBLE 33 Sense.

Following would be the order to use : 

1. Fetch the data from Xeno_Canto
2. Call the dataset inot MP3toWav_Conversion notebook.
3. Import the converted dataset into the Modeltest_Spain.
4. TFLM-notebook - for converting .tf model to .tflite
5. Arduino Testing routines.
