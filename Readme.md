# 1. How to start

There is a software operation video in the HOW-TO-START directory. Through this video, you will know how to run the XXSim model directly, and how to convert the Eclipse model into XXSim model and run it ( the conversion of CMG model is similar to the operation of Eclipse model ).

# 2. Update history

## 2018/05/31  New Features for v1.5

### GUI
The most important update is the release of a bata version of CMG to XXSim converter with following basic features:
  
1) the standard black oil model (IMEX);

2) the standard compositional model(GEM);
 
3) the standard thermal model(STARS);

4) improved 3DView module;
 
5) more adjustments and optimizations of Eclipse to XXSIM converter;
 
6) fixed the bug of the model directory that can not take the space character.
 
### XXSIM core:
 
1) added multiple pvt tables for black oil;
 
2) added multiple equilibration regions;
 
3) added multiple viscosity tables for thermal;

4) added historical rates and wbhp of each well for history match purpose;

5) added Restart option.


## 2018/01/02  New for v1.1.1
1) Added the conversion of Eclipse keyword SWATINIT;
2) Fixed some bugs;

## 2017/12/12  New for v1.1

New features of XXSim and Eclipse to XXSim converter:

1) Added DUALPORO module in XXSim and conversions of keywords for dual poro model: DUALPORO, GRAVDR, DUPNUM, DZMATRIX, MULTMF.

2) Added conversions of Well Group constraints.

3) Added conversion of keywords related to faults;

4) Improved the conversion of BOX, MULTIPLY, ADD, EQUALS, MINVALUE, MAXVALUE, so that all the legal arrays could be converted properly now.

5) Added conversions of keywords:  MULTIREG, MULTREGT, MULTREGH;

6) Added conversion of keyword WPIMULT.
7) Thermal model conversion.
8) Add _xx to the converted eclipse data file.
9) Output region and group rates and cumulative in smspec and unsmry files.
10) And fixed some bugs.
