Documentation for LMS6002D single chip transceiver
==================================================

Info
----

This documentation is released by Lime Microsystems for the benefit of open-source community. You're free to use it without signing an NDA with Lime Microsystems as long as you develop and open-source project.

Official web-site of Lime Microsystems: http://www.limemicro.com

Official support mailing list for open-source projects: https://groups.google.com/forum/?fromgroups=#!forum/limemicro-opensource


Why LMS6002D?
-------------

Because up to my knowledge it's the only highly-integrated wide-band transceiver chip which is friendly to open-source software and open-source hardware. Lime Microsystems support for open-source is not ideal, but they're making great effort to do better. This documentation repository is a part of this effort.


Contents
--------

 * [LMS6002Dr2-DataSheet-1.2r0.pdf][1] (5 June 2012) - LMS6002D datasheet.
 * [LMS6002Dr2-Programming and Calibration Guide-1.1r1.pdf][2] (19 July 2011) - LMS6002D Programming and Calibration Guide. Also contains description of calibration procedures.
 * [LMS6002Dr2-Quick Starter Manual-EVB_5_r2.3.pdf][3] (11 May 2012) - Quick Starter Manual for the [LMS6002D evaluation board][EVB]. Contains useful instructions for manual LO leakage and I/Q imbalance calibration.
 * [LMS6002D-FAQ-1.0r7.pdf][4] (16 July 2012) - Answers to Frequency Asked Questions. Don't miss this.
 * [LMS6002Dr2-Improving transceiver performance using digital techniques-1.0r1.pdf][5] - Shows how to cancel TX LO leakage and compensate RX IP2 and TX I/Q imbalance in baseband.
 * [LMS6002D-Temperature testing July 2011.pdf][6] - Measurements of the chip performance vs. temperature and frequency.
 * [LMS6002Dr2-RF LoopBack Response.pdf][7] - The document shows the frequency response of different RF Loopback. Adjusting the Tx/Rx gain stages you can make the frequency response to be flat up to 2.9 GHz for LNA1/2.
 * [LMS6002D IF-RF LoopBack Options.pdf][8] - A diagram showing baseband loopback connection options.
 * [LPF IF BW vs RCCAL_LPF.pdf][9] - Shows dependency between the LPF bandwidth and RCCAL_LPF (0x36[6-4]) values for the 750kHz filter.

[1]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002Dr2-DataSheet-1.2r0.pdf
[2]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002Dr2-Programming%20and%20Calibration%20Guide-1.1r1.pdf
[3]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002Dr2-Quick%20Starter%20Manual-EVB_5_r2.3.pdf
[4]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002D-FAQ-1.0r7.pdf
[5]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002Dr2-Improving%20transceiver%20performance%20using%20digital%20techniques-1.0r1.pdf
[6]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002D-Temperature%20testing%20July%202011.pdf
[7]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002Dr2-RF%20LoopBack%20Response.pdf
[8]: https://github.com/chemeris/lms6002-documentation/raw/master/LMS6002D%20IF-RF%20LoopBack%20Options.pdf
[9]: https://github.com/chemeris/lms6002-documentation/raw/master/LPF%20IF%20BW%20vs%20RCCAL_LPF.pdf
[EVB]: http://www.limemicro.com/lms6002d_eval.php


Projects
--------

Below is a list of open-source projects built with the LMS6002D chip:
 * [UmTRX][] - a dual-channel transceiver with 1GbE interface from Fairwaves.
 * [BladeRF][] - a USB 3.0 Superspeed Software Defined Radio from Nuand.
 * [MyriadRF][] - a reference/prototype RF frontend from Lime Microsystems.

Let me know if you develop something awesome with LMS6002D and get a credit line here!

[UmTRX]: http://code.google.com/p/umtrx/
[BladeRF]: http://nuand.com/
[MyriadRF]: http://myriadrf.org/


Contacts
--------

If you need more information to develop your open-source project - write to [the LimeMicro open-source support mailing list][lime-ml].

[lime-ml]: https://groups.google.com/forum/?fromgroups=#!forum/limemicro-opensource

-- Alexander Chemeris &lt;Alexander.Chemeris@gmail.com&gt;

