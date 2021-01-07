-------------------------------------------------------
       2HDMC - TWO-HIGGS-DOUBLET MODEL CALCULATOR
 -------------------------------------------------------

  2HDMC is a C++ code for performing calculations in 
  general, CP-conserving, two-Higgs-doublet models.        
	

  AUTHORS
 -------------------------------------------------------
  The original authors of the 2HDMC code are 
  David Eriksson, Johan Rathsman and Oscar Stal

  The code is currently developed and maintained by
  Johan Rathsman    <johan.rathsman@thep.lu.se>


  OBTAINING THE CODE
 -------------------------------------------------------
  The easiest way to obtain 2HDMC is from the 
  official webpage: 

  ->  http://2hdmc.hepforge.org

  From this page the class documentation can also be 
  downloaded. The full manual has been published and
  is available from
  
  ->  http://arxiv.org/abs/0902.0851
  
 
  SYSTEM REQUIREMENTS
 -------------------------------------------------------
  2HDMC has been tested to compile (with gcc 4) and run 
  under GNU/Linux on both 32- and 64-bit systems. It 
  also runs on OS X (10.6/7/8) without trouble.

  2HDMC requires a working installation of the GNU 
  Scientific Library (GSL). The latter is often included
  in standard Linux distributions, but can otherwise be 
  obtained from

  ->  http://www.gnu.org/software/gsl

  To calculate cross sections for Higgs production,
  2HDMC can now interface the public code SusHi

  -> http://sushi.hepforge.org

  For further information on how to use this interface,
  we refer the user to this webpage and the SusHi
  documentation.

  It can also be useful to download HiggsBounds/
  HiggsSignals (optional), since 2HDMC can interface the 
  LEP, Tevatron and LHC constraints implemented in these
  codes. HiggsBounds/HiggsSignals are available from

  -> https://gitlab.com/higgsbounds/higgsbounds
     https://gitlab.com/higgsbounds/higgssignals
	
  Starting from 2HDMC 1.8, HiggsBounds version 5.7.0 or
  higher AND HiggsSignals 2.4.0 are required to use this
  feature.

  To link 2HDMC with HB/HS support, uncomment the corresponding
  lines in the Makefile to define the orresponding build 
  directories. If you use 2HDMC with HB/HS, please cite the 
  relevant ublications.

  INSTALLING AND RUNNING
 -------------------------------------------------------
  To compile the library and example programs, run:
  $ make

  To compile the 2HDMC library, run:
  $ make lib

  To compile a single program, with source Prog.cpp, 
  located in src/, run
  $ make Prog

  To verify the 2HDMC installation (both with and without  
  HB/HS link), the sample program 'Demo' can be executed.
