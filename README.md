# OcrevalUAtion: evaluation of a batch on file level
This notebook provides a simple script to run the ocrevalUAtion tool (see: https://github.com/impactcentre/ocrevalUAtion) automatically through a batch of files. Whereas the outcome provided by the tool is the total number per category for the complete batch, this code provides an outcome on file level. The output is a .csv file, with for every file the 'CER', 'WER' and 'WER (order independent)' scores after comparison with the Ground Truth file. 

This code is written for files with a filename in this format: **"idenitifier_pagenr_type.extension"**

**Identifier:** a unique code which is used in both the Ground Truth file and the OCR file <br> 
**Pagenr:** the pagenumber of the source that is captured in the file <br>
**Type:** GT for Ground Truth, OCR for the OCR file to be evaluated <br>
**Extension:** This can be any extensions that is allowed by the ocrevalUAtion tool. In this example .xml is used.
