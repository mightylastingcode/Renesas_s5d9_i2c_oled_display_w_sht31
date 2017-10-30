# Renesas_s5d9_i2c_oled_display_w_sht31
Add an external I2C SHT31 temperature and humidity sensor

Develop the C code from scratch for the S5D9 board
Read the current temperature (F) from an external SHT31 sensor (I2C interface).
Display the current temperature (F) on OLED display (I2C interface).
Display the temperature graphically over time on OLED display.

File Description:
1.  hal_entry.c/h  (Main Program Loop)
2.  i2c.c/h (i2c SSP API calls)
3   sht31.c/h (subroutines for interfacing with the sht31 sensor)
4.  ssd1306_oled.c/h (subroutines for the OLED module operations)
5.  en210.c/h (subroutines for AMS EN210 operations - not used in this tutorial but kept here.)
