# IMPORTS-FOR-BARCODE
%pip install pdf417gen 
!apt-get install -y libzbar0 
%pip install pyzbar  
%pip install pdf417gen pdf417decoder 
import os 
from PIL import Image 
from pdf417decoder import PDF417Decoder 
from pdf417gen 
import encode, render_image
