Hobdrive config for Chevrolet Aveo 1.2 MT T255 (2010 year)

Petrol engine [B12D1](https://en.wikipedia.org/wiki/Daewoo_S-TEC_engine#S-TEC_II) controlled by ECU "Sirius D42R".

    for %i in (user.*) do adb push %i /storage/sdcard0/hobdrive/%i      rem Windows
    for f in user.*; do adb push $f /storage/sdcard0/hobdrive/$f; done  # Linux
