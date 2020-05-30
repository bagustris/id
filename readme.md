## id

### iban-recipe based Indonesian speech recognition
Structured by Bagus Tris Atmaja (btatmaja@gmail.com), presentend on ASJ Spring Meeting 2019, UEC Tokyo.


Notes : 
- steps and utils folder are needed, please copy (or softlink) from either iban or wsj directory.  
- dataset is not included due to copyright, but its structure is given in text file
- Used Kaldi commit = 0e5d755fdbe8a746223f05bcf7243107618ecaf7
- For single GPU, set exclusive mode via `sudo nvidia-smi -c 3`
- Latex template for beamer slide: https://github.com/bagustris/beamer-nomi

Citation
If you use part of this method or used for benchmarking, please cite the included pdf paper.
```
Atmaja, B.T., Arifianto, D., Akhmad, F., Akagi, M., 2019. “Speech recognition on Indonesian 
language by using time delay neural network.” ASJ Spring Meeting, Tokyo, pp 1291–1294.
```
