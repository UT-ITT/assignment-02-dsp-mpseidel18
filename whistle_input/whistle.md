# Audio-Based whistle control

The script listes to the frequencie changes by analyzing the fourier transformed frequencies.

- Checking for signals only above a certain volume threhshold
- Apply a hanning window so we dont get ghost frequencies when cutting the chunks
- Only analyze the signal between relevant frequencies

The whistle-check is done by simply calculating the difference between the lowest and highest frequency.
Tested on PowerPoint.