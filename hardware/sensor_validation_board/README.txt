This file documents the macro decisions related to the MEMS sensor validation for the Williamson rocket v1 flight computer.

On a previous flight computer project at university we ran into major issues with the reliability of both the barometer (BMP585) and IMU (LSM6DSOX). We believe this was an issue with our soldering/assembly. This sensor validation board is designed to test the flight computer chips before we commit to sensor selection. 

Requirements:

- The chips must be able to run off 3V3 logic to simplify power requirements

- The chip which is finally selected must withstand soldering in a predictable and consistent way. 

- The chip must be able to be soldered at home/university. 

Datasheets for trial chips:

IMU:

(slightly older version of one used for uni project)
https://www.digikey.co.nz/en/products/detail/stmicroelectronics/LSM6DSLTR/6192804

- I would also like to try using an MPU6050, since they have been so widely used. Even though they are quite old. No stock at digikey however.

Barometer:

(BPS space used this)
https://www.digikey.co.nz/en/products/detail/te-connectivity-measurement-specialties/MS561101BA03-50/5277445

(same as university selection, BMP585)
https://www.digikey.co.nz/en/products/detail/bosch-sensortec/BMP585/19522589

(popular in industry, BMP581)
https://www.digikey.co.nz/en/products/detail/bosch-sensortec/BMP581/16036134

