Modular HiFi
============

A collection of Eurorack modules for home HiFi.

Typically, the PCB serves as a front panel while also carrying the circuit components on the back.

*Status: working prototypes. More documentation will follow!*


Modules
-------

Stereo mixer
~~~~~~~~~~~~

``stereo_3ch_mixer``

Three vertical slider potentiometers. Secondary (monitor) output. Quasi-differential inputs.


Phonograph preamplifier
~~~~~~~~~~~~~~~~~~~~~~~

``phono_preamp``

RIAA preamplifier and subsonic high-pass filter. 

Based on Rod Elliot <http://sound-au.com/> "Project 06" (RIAA pre-amp) and "Project 99" (subsonic filter)


Surround decoder
~~~~~~~~~~~~~~~~

``surround_decoder``

Stereo to 5.1 decoder. Separate volume controls for front, center, rear and subwoofer. Switchable subwoofer low-pass filter, adjustable between 50 and 500 Hz. Rear center channel "mix-in" control.


License
-------

`Open source hardware <https://www.oshwa.org/>`_ is hardware for which the design is made publicly available, so that anyone can study, modify, distribute, make, and sell the design or hardware based on that design, subject to the following license conditions.

Hardware licensed under the *CERN Open Hardware Licence Version 2 - Weakly Reciprocal,* a copy of which is included in this repository at `cern_ohl_w_v2.txt <https://github.com/turingbirds/modular-hifi/blob/master/cern_ohl_w_v2.txt>`_.
