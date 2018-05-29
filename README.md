# Automated-Flow-Monitoring-System
Welcome!

If you are reading this then you have the outstanding opportunity of using Bronkhorst Flow Microcontrollers, but you unfortunately put your trust in an Undergraduate programmer to do your flow automation (not the best choice!); however, this program is robust and correct enough that you can rest assured that your reactions will proceed as planned. 

The software detailed throughout the rest of this manual is a python-based program that automatically monitors the current flows of multiple Bronkhorst controllers and changes the flows based on times specified by the user. The software takes the responsibility of monitoring the timing of flow changes away from the user and also offers protection to the experimenter in terms of ensuring the slows switch to the correct values. One of the biggest differences between this project and similar programs on github, is that this software allows for multiple microcontrollers to be used in parallel along with multiple computer ports to be used. Additionally, automated email updates to the user can be added  to indicate the completion of the reaction or if there was an error. The interface is through the command line, and can be run on virtually any computer that can support python. 

Throughout this manual general installation/configuration guidelines, usage procedures, and troubleshooting advice will be explained. This is meant to be thorough, although I am sure that I will miss parts. Please update this manual on my github page if you find anything that could be explained better or if you think the addition of an explanation/procedure is needed. This is meant to be an open source project that anyone can and should contribute to if they would like to use Bronkhorst Flow controllers in their own research efforts.

The Autonomous Flow Monitoring System (AKA. AFMS) is originally a project for the Sustainable Chemistry and Catalysis Engineering (Ive Herman’s lab) at the University of Wisconsin-Madison. My main research mentor was Sarah Specht, who has been a great asset throughout the creation of this program as a willing experimenter for my software and as a patient “client”. My hope is that this software can be expanded on and used in other research labs throughout the country. This software was based on a Bronkhorst driver developed in the PyExpLabSys project on GitHub.

With that, I wish you the best in your endeavor to use my software, and please do not hesitate to reach out to me on github, linkedin, or wherever you can find me. I hope this software helps!

Sincerely,
Ethan Young
