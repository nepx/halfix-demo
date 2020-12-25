# Halfix Demo

This repository contains a minimalistic build of the Halfix x86 emulator, configured to emulate an Intel Core Duo, and a set of disk images in chunked, compressed (`.gz`) form that are known to work on it:  

 - OS/2 Warp 4.5  (100.3 MB compressed, 209 MB uncompressed)
 - Basic Linux (2.9 MB compressed, 104.9 MB uncompressed)
 - Windows NT 4.0 (43.7 MB compressed, 314.3 MB uncompressed)

In the future, I will consider adding [Red Star OS](https://en.wikipedia.org/wiki/Red_Star_OS), which would be of interest for researchers and casual users. However, this will require the implementation of save states (not yet functional within the browser, unfortunately), and the disk size (800+ MB compressed) may be too large for this repository. 

These disk images can also be used to test the native build of the emulator. 

## System Requirements

WebAssembly support is required. Make sure you have enough bandwidth to download the disk images; even with compression, the emulator downloads 10-20 MB per boot, more if you run apps like Internet Explorer. 

## License

Except for Linux, all the other operating systems are copyrighted and are provided for non-commercial and educational purposes ONLY. This project is not affiliated with and has not been approved by the entities that produced these operating systems. Please don't abuse this. 

The emulator itself is open source and is available [here](https://www.github.com/nepx/halfix). 
