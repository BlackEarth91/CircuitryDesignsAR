# Introducing CircuitryDesignsAR
CircuitryDesignsAR application is developed with the use of open-source tracking library available, ARToolKit, the purpose of the application was set to examine the learning paradigms provided by augmented reality. Through the use of representations of spatial information, real-time calculations of the circuit are displayed on screen and the augmented 3-D models of components are projected on the NFT markers created

#Feature recognized

# Samples


# Tools and Usage
* The project utilizes the ARToolKit open source library provided from [ARToolKit](https://github.com/artoolkit) 
*  Import the Unity Package with [Unity](https://unity3d.com)
* Alternatively you can install the apk provided in the app folder on your Android device.

# Scripts
The scripts used for the logic calculations of the circuit is called on the successful recognition of the marker
CalculateVoltage.java


    public float calculateCurrent()
    {
        bool Result;
        float num;
        Result = float.TryParse(InputField.text, out num);
        if (Result)
        {
            _current = ((float.Parse(InputField.text)) / (resistance));
        }
        return _current;
    }

# Limitations

