# CertificateGenerator
Certificate Automatic Generator

This simple script helps organizations that need to manually create thousands of certificates for their employees or students. The project aims to reduce the time spent on making the certificates. The most importent part of this secript it is sport Arabic text.

- inpot:
  - Certificate Template (without student's name)
  - Excel sheets contain the Names
- output:
  - PDF certificates

## How it's work?
- load the font and Excel sheet
``` 
font = ImageFont.truetype("Tajawal-Regular.ttf", 100)
dataset = pd.read_excel('Book1.xlsx')
```
- set the coordinate of the text 
ex. (1500 , 970 )
```
draw.text((1500 , 970 ), rev_text, fill=(255,0,0,255), font=font)
```

#### NOW YOU ARE READE TO GENERATE THOUSANDS OF CERTIFICATES ON THE SAME TIME :)

 
