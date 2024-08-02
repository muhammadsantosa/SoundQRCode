# SoundQRCode
Individual Research Project looking at the feasibility of storing sound on paper

Encoding & Decoding:
- Encoding involves:
  - Encoding Sound QR Codes with AAC audio file with 256 colours, which includes regular QR Code features and a custom coloured reference box
  - Getting the size of the Sound QR Codes based on different settings such as printer dpi, pixels per module, and Sound QR Code verson
  - Producing a pdf with the Sound QR Code of specified sizes printed on it in their actual sizes which are then printed using a printer
 
- Decoding involves:
  - Taking a picture of the Sound QR Code using an iPhone and pre-processing the image
  - Performing object detection, geometry fixing, and lighting fixes
  - Using delta E 2000 as a metric to perform regression for data modules, comparing colours detected against colours in the coloured reference box
 
Results:
- Utilised different metrics such as RRMSE to determine best colour space and size to use for the Sound QR Code, as well as the detection accuracy

References:
- 

For more information on how it works visit ___
