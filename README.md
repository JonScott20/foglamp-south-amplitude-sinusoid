# foglamp-south-amplitude-sinusoid
South plugin for the sinusoid with a configurable amplitude cycle.

## Debian Package
https://github.com/JonScott20/foglamp-south-amplitude-sinusoid/raw/master/foglamp-south-amplitude-sinusoid-0.0.1.deb

## Package Hashes
MD5: 49795F1F4B7B707DA978D33F8F603C33

SHA-256: 9E5FC53EC6C9FEBCF548ED44043949BC5C807B1EEA6BA6769633DD6E439C1878

## Installation
1. Download the Debian package to a machine installed with FogLAMP.
2. Navigate to the directory of the Debian package
3. Ensure that FogLAMP is running.
4. Run the following command:
> sudo apt install ./foglamp-south-amplitude-sinusoid-0.0.1.deb

NOTE: the "./" in front of the package name is important here!

5. Restart FogLAMP

## Configuration Options
![image](https://raw.githubusercontent.com/JonScott20/foglamp-south-amplitude-sinusoid/master/images/AmpSinConfig-FogLAMP.png)
- assetName (String): The name of the asset.
- dataPointsPerSec (Integer): The number of readings per second.
- maxAmplitude (Integer): The maximum amplitude before amplitude starts to decrease.
- step (Integer): The amount to increase/decrease the amplitude by each cycle. 

## Data Produced
![image](https://github.com/JonScott20/foglamp-south-amplitude-sinusoid/blob/master/images/AmpWave-FogLAMP.png)
