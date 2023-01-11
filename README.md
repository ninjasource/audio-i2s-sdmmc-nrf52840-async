# audio-i2s-sdmmc-nrf52840-async
Asynchronously reads LC3 Encoded audio off an SD card and plays it through the I2S audio peripheral using Embassy on an nrf52840 DK

# To run

Copy the mono LC3 Encoded audio file `classmon.lc3` to the root folder of a fat formatted SD card

`cargo run --release`
