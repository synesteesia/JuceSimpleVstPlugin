In this project, I undertook the creation of a simple yet foundational VST (Virtual Studio Technology) plugin using the JUCE framework, 
with C++ as the coding language within the Visual Studio IDE. 
This endeavor aimed to provide a thorough understanding of VST plugin development while crafting a basic volume fader plugin as a springboard for future, more intricate projects.

JUCE provides several essential project files, each serving a distinct purpose in VST plugin development:

PluginProcessor.h/cpp: These files define the core processing functionality of the plugin. 
The PluginProcessor class handles audio processing, parameter management, and communication with the host DAW

PluginEditor.h/cpp: Responsible for the graphical user interface (GUI) of the plugin, 
the PluginEditor class manages the visual representation of the plugin within the DAW, including parameter controls and display elements.

These template files serve as the foundation for building VST plugins using JUCE, 
providing a structured framework for efficient development and customization. 
Files with ending .h primarily contain declarations. 
They outline the structure and interface but do not contain the actual implementation code.  
Files that end with .cpp, on the other hand, contain the implementation code. 
They include the necessary headers, implement the member functions declared in .h, 
and define the behavior of the class. This file is where the actual functionality is coded, 
including audio processing algorithms, parameter handling, and interactions with the host DAW.
