# Ultrasonic Sensor
the ultrasonic sensor works by sending out a 10µs pulse that sends out an 8-cycle burst of ultrasound frequency at 40kHz. The sensor then records the time interval between sending the trigger signal and receiving echo signal when it bounces from an object.

# Testing Plans and Overall Results
The first test was Accuracy. for this test i placed a flat, wide object in 3 different spots of varying ranges to see how close they were to the measurement given by my ground truth (ruler).

At the 20cm mark, my readings averaged out to 20.35cm, at 21cm, it was an average of 20.73cm, and at 19cm, it was an average of 18.93cm, as seen in the US_ACCURACY_Data picture in this folder.
Comparing these innaccuracies to the specification table, as seen in the USSPECIFICATIONS picture in this folder, we see that at 21cm and 19cm, it is within the tolerance limit, but at 20cm, it is .5mm away from the +-3mm.

The second test was Range. for this test i measured out multiple spots on the floor from 410cm to 1cm. finding that from 200cm and up, the sensor was freaking out, giving an almost constant 450cm reading.
then once i broke 150cm, the reading stabilized, then at around 5cm, it began giving awkward readings, and at around 2cm, the sensor stopped giving accurate readings entirely.

i found that the range of the sensor was somewhere around 150cm-5cm. the specification table says that the range is 400cm-2cm. my range is significantly less.

The third test was Repeatability. for this test i picked 5 different distances within the known range. then i moved the object to each distance, then went back to the first distance and repeated the test 3 times.

at 10cm, the 3 tests gave me 10.91cm, 10.22cm, and 9.64cm. 

at 20cm, the 3 tests gave me 21.26cm, 19.97cm, and 20.29cm. 

at 30cm, the 3 tests gave me 29.97cm, 29.81cm, and 29.81cm. 

at 40cm, the 3 tests gave me 38.81cm, 39.88cm, and 39.52cm.

at 50cm, the 3 tests gave me 49.93cm, 49.76cm, and 48.78cm.

These results show that it isnt exactly precise nor reapeatable, as the numbers fluxuate greatly.

# Possible Errors
Eyeballing the distance reading from the tape measure and the distance between the actual sensor and the casing of the sensor.
