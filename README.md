# translate-assembly-to-hexa
A c++ program used to translate assembly language to hexacode using and input text file. the program uses an algorithm to extract and divide assembly code parts and add each line to a node in a linked list. After that, the code will be translated using a 2d array as a dictionary. the program contains error handling 
Input example from a text file:
      ORG  100
      LDA  107  
      CMA
      INC
      ADD  MIN 
      STA  DIF
      HLT
MIN,  DEC  83
SUB,  DEC  -23
DIF,  HEX  0
      END
