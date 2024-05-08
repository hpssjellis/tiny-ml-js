## ictp-2024-presentation.md

### RAK2270 Sticker Tracker Acceleration tinyML example but using a cell phone or laptop mouse instead of the [LoRa/LoRaWan RAK2270 sticker tracker](https://store.rakwireless.com/products/rak2270-rak-sticker-tracker?variant=43194331791558)  
Demo at or use the QR code https://hpssjellis.github.io/tinyMLjs/public/acceleration/a00-best-acceleration-rak2270-sticker-tracker.html

![image](https://github.com/hpssjellis/tinyMLjs/assets/5605614/16314837-988e-4c82-8d3b-5dd75eb58c1c)


Start of TinyMlJs SPA (Single Page Application)
![image](https://github.com/hpssjellis/tinyMLjs/assets/5605614/9bd0c0dc-eb1e-4789-9deb-9f10033c2b46)

  <img src="https://github.com/hpssjellis/tinyMLjs/assets/5605614/9bd0c0dc-eb1e-4789-9deb-9f10033c2b46" width = 500/>  

Using your cell phone accelerometer (use QR code above) populate the data and clean it of messy input, change the label to "1sideways" and keep the data
![Screenshot_20240508_092204_Chrome](https://github.com/hpssjellis/tinyMLjs/assets/5605614/b791b0bb-0aa7-4afd-a00d-3c8d53ec9270)



repeat for 3 total moving sideways readings (you would collect much more if this was not a demo)

Then repeat for 3 more moving vertical readings. Change label to "2up"

![Screenshot_20240508_092004_Chrome](https://github.com/hpssjellis/tinyMLjs/assets/5605614/c1831554-f92b-421f-9b68-b4725e1a7b69)


Then click convert data to tensor and train all. If nothing happens youi can try the "Clean, Trim or Fill All" button to try to tidyup the data. (Sensor data is messy)

Once done, capture new data clean it and classify it.

![Screenshot_20240508_092128_Chrome](https://github.com/hpssjellis/tinyMLjs/assets/5605614/36a7cee5-d09a-4631-bc1a-05691997bc81)

  <img src="https://github.com/hpssjellis/tinyMLjs/assets/5605614/36a7cee5-d09a-4631-bc1a-05691997bc81" width = 500/>   

You can export the model (3 files a json, labels and binary file)

Now that tensorflowJS model needs to be converted to a tflite file and then a c-header file. the last step is easy the first step can be done in multiple ways.

You can also upload the 3 files onto your laptop. click show file uploading, find the three files load them and view your model structure

![image](https://github.com/hpssjellis/tinyMLjs/assets/5605614/5ad0c048-f622-4a6b-83e7-b5ccdce911bb)


 
  <img src="" width = 500/>   
  <img src="" width = 500/>   
  <img src="" width = 500/>   
  <img src="" width = 500/>   
  <img src="" width = 500/>   




