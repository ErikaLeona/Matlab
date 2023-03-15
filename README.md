# Class B power amplifier

# Description

It is a graphical interface made in Matlab where you can see the waveforms of the transistor currents in the class b power amplifier circuit.

# How it works

The application opens with an interface, which contains the circuit diagram and a menu, called "Documentatie".      
![image](https://user-images.githubusercontent.com/107769103/220174603-0b37cdf7-dade-40ce-ac2a-e151d4cfee9e.png)

Accessing the menu will open three other submenus. One for our circuit, which in turn splits into two, one for the bibliography and one for closing the application.    
![image](https://user-images.githubusercontent.com/107769103/220172680-64af1d73-97f9-4a41-bec9-2872bf7cd834.png)

Accessing the "Cronograme" sub-menu will open another interface, on which it is located: 
>A plot showing the output voltage   
>3 radio buttons     
>A plot showing the current       
>A radiogroup with 3 edit buttons, respectively 3 text buttons       
>A pushbutton   ![image](https://user-images.githubusercontent.com/107769103/220172599-6cd682b9-a9eb-47d4-ac32-1fdc4601f9c2.png)

By pressing the first radio button, next to the output voltage, the input voltage will be displayed.
![image](https://user-images.githubusercontent.com/107769103/220171503-70901b80-ef69-4861-bb1a-93667fee2246.png)


Accessing the second RadioButton, called "Afiseaza CSTV", the CSTV will appear on the right side of the figure.
![image](https://user-images.githubusercontent.com/107769103/220172545-4983f1c6-2608-4ca2-9090-57eab53491ec.png)

By checking the third RadioButton, another subplot will appear in place of the CSTV showing the output power across the RL resistor.     
![image](https://user-images.githubusercontent.com/107769103/220172563-d2f5cd05-0e0f-4731-9f5d-143f1d411027.png)

Depending on the option chosen from the popup menu, either the output current (io) or the current from the first transistor (ic1) or the current from the second transistor (ic2) will be displayed.   
![image](https://user-images.githubusercontent.com/107769103/220173065-c52966d0-b476-49fd-9ec3-680aa9399655.png)
![image](https://user-images.githubusercontent.com/107769103/220173081-9c0202f3-9bf8-4122-83de-5e090d50f40e.png)

By changing the values in the radiogroup, all waveforms will change according to the changed value.    

Accessing the "Ecuatii" submenu will open another interface, on which it is located:
>A ChechBox   
>A radiogroup with 3 edit buttons, respectively 3 text buttons   
>A radiogroup with 6 text buttons     
>A pushbutton   

By checking the CheckBox, the output power, supply and efficiency will be calculated, at the maximum amplitude of the output voltage (vo=Vcc-0.2), obtaining a maximum efficiency.

