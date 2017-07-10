# Thematicity To SSML

This repository contains code and sample sentences annotated with thematicity to reproduce our demonstration in [1]. Further information on the methodology to derive SSML tags from thematicity spans can be found in the references below.

######################
## Code
######################

The script them2ssml.py converts a txt file annotated with thematicity to SSML prosody tags.
To run the script simply execute it using the command: python them2ssml.py "yourpath"/sentences.txt > "yourpath"/"yourResultFilename".txt

######################
## Sample sentences
######################

The file sentences.txt contains some sample sentences in order to reproduce the demonstration presented in [1]

######################
## References and Citation
######################


If you use this software, data or modify the code please cite the following publication:

     - [1] Domínguez, M., M. Farrús, and L. Wanner (2017). A Thematicity-based Prosody Enrichment Tool for CTS. Accepted in show and tell demonstrations at Interspeech 2017, Stockholm, Sweden.

Further references:

     - Domínguez, M., M. Farrús, J. Codina and L. Wanner (2017a). A Data-driven Approach to Thematicity-based Prosody Enrichment. Submitted to the 5th International Conference on Statistical Language and Speech Processing (SLSP 2017), Le Mans, France.
     - Domínguez, M., M. Farrús, A. Burga, and L. Wanner (2016). Using hierarchical information structure for prosody prediction in content-to-speech applications. In Proceedings of the 8th International Conference on Speech Prosody, Boston, USA, 2016, pp. 1019–1023.
