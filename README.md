# AED Pulse Simulator

# Build and Test

1. Execute Program with the setup script 'setup.sh'. This should already be an executable but incase of an issue please convert the file to an executable using 'sudo chmod +x ./setup.sh'. This file will install the required packages to play audio & run the program.
2. If you encounter any errors, you may install the package seperatly using [sudo apt update] & [sudo apt install alsa-utils], and then run the program in QT.
3. Please note this alsa-utils package is required for the audio. More information regarding the package can be found below.
4. If you run into any other issues, attempt to run the unixConversion Script. If this does not resolve your issue, please contact us and we will provide an immediate fix.

### Description:
    The AED Pulse Simulator is a software application designed to simulate the core functionality of an Automated External Defibrillator
    (AED) Pulse device. This simulation allows users to practice and enhance their skills in responding to life-threatening cardiac arrhythmias,
    such as ventricular fibrillation, ventricular tachycardia and PEA in a virtual environment

### List of sources:
    AED_Simulator.pro (Qt Creator project file)
    aed.cpp, aed.h
    aedcontroller.cpp, aedcontroller.h
    aedstate.cpp, aedstate.h
    aedwindow.cpp, aedwindow.h
    AudioTypes.h
    battery.cpp, battery.h
    defs.h
    electrodepads.cpp, electrodepads.h
    heartrategenerator.cpp, heartrategenerator.h
    logger.cpp, logger.h
    main.cpp
    mediaplayer.cpp, mediaplayer.h
    patient.cpp, patient.h
    PatientType.h
    ProcessSteps.h
    processtracker.cpp, processtracker.h
    SignalType.h
    testcontroller.cpp, testcontroller.h
    testwindow.cpp, testwindow.h


### Issues/Limitations:
    No known issues or limitations.
