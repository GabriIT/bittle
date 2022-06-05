# bittle
bittle 6 DOF robot

Bittle  is a open source programmable quadruped robot kit. This article shows new interesting learning capabilities stretching boundaries

Bittle  is a open source programmable quadruped robot kit suitable for STEM, new develoopments, and in general multi-DOF robot design and control applications development. Explanations, instruction are continually updated as well as new application details: a starting page to deep into understanding the versatility of this smart dog can be found at  www.petoi.com/
It is worth to remark that it is the 2. most successful project  in Arduino over the last 3  years, being Arduino Uno board the first one. https://create.arduino.cc/projecthub/petoi/opencat-845129?ref=platform&ref_id=424_popular___&offset=8 
After Arduino Uno board Bittle follows on Arduino platform  and it is not  by chance.
I bumped into it when searching for a sophisticated robot open source, with more than 6 degrees of freedom, ideally working on Arduino platform and ready to implement python scripts. I aim at controlling it through ROS2 and this will be my goal in the next months.
As for today I could successfully go through the bumpy road of having it under control in terms of software understanding and hardware design. Of course due to Prof.Li design continuous  improvements and exptensions is quite challenging to keep pace with all new feature emerging.

This article aims to show the implementation of ‘Bittle climbing’ in which Bittle climb a structure, while turning upside down. Additionally the smart dog carry out checks and change postures while staying in this odd posture.  Hereafter the video showing the result:
https://www.youtube.com/watch?v=cWgpqxFAHh8
A app allows to control Bittle also from a mobile phone with instruction available at: +
https://docs.petoi.com/app-guide

OpenCat.ino is the main control module and can be found at following link:
https://github.com/PetoiCamp/OpenCat/tree/main

