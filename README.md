# Constellation_contact_analysis-orekit
The code mentioned in this repository focuses on how does a target satellite propagating in orbit establish contact window with satellites which are part of a constellation. It requires the user to install the latest orekit version, along with access to NORAD TLEs. The code retrives TLEs directly from the Celestrak website and then  propagates the satellites.

It should be taken into account that the user can change the following parameters and notice change in their output:
Axis of nadir pointing
Half-aperture angle of the constellation antenna
Maximum allowable range
It has been assumed that the target/dummy spacecraft has an antenna on-board which is omnidirectional. Hence, there are no stringent pointing requirements except what is mentioned above.  

## How to run
Open the notebook in Jupyter and run all cells in order.

## Output 
Upon successful completion of the code, the user should expect a complete contact analysis along with the window of duration. 

## Notes
This is a personal project shared for discussion and learning.
