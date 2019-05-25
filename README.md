# Outdoor_AP_Geomaps

Solution to capture outdoor APs location, regularly update it and display it in Prime Infrastructure or other platforms like Google Earth or Next UI for monitoring and operations.

## Business/Technical Challenge

Companies in certain verticals like mining and service providers deploy outdoor Access Points with GPS receivers. These companies specially the mining companies want to have a way to monitor where these APs are deployed since they are mobile and move daily to new locations supporting mining equipment used for exploration.

The need is to have these APs location updated when they move to be used in monitoring and operation activities.

Prime Infrastructure is used by some customers and others are looking for other ways to visualize their APs and information about these APs like number of customers, channel, mesh network rf quality and so others.

Until Prime Infrastructure 3.5 Outdoor APs GPS location is not updated automatically. Prime and Aironet have limited API capabilities.


## Proposed Solution

The proposed solution encompass the following:

1) For customers with Prime Infrastructure until 3.5 and Aironet controllers a software that uses Prime APIs and WLC SNMP capabilities collect the APs information and generate a CVS file that can be loaded at Prime when a refresh of the APs location is desired, instead of having to do it manually.

2) For customers migrating to Catalyst Wireless LAN Controllers the Catalyst WLC Yang modeling is used to collect the information in a more scalable way and generate a CSV file that can be loaded at Prime Infrastructure.

3) For customers looking for other ways to visualize their outdoor APs, a software will provide and export file that can be open at Google Earth or Next UI.


### Cisco Products Technologies/ Services

Our solution will leverage the following Cisco technologies

* Cisco Unified Wireless Networking (CUWN)
* Cisco Catalyst 9800 Controller
* Prime Infrastructure (PI)

## Team Members

* Wendel Nery <wnery@cisco.com> - Brazil CML Eng
* Flavio Correa <flcorrea@cisco.com> - Brazil EN Architecture
* Julio Gouy <jgouy@cisco.com> - Brazil Enterprise

## Solution Components


<!-- This does not need to be completed during the initial submission phase  

Provide a brief overview of the components involved with this project. e.g Python /  -->


## Usage

<!-- This does not need to be completed during the initial submission phase  

Provide a brief overview of how to use the solution  -->



## Installation

How to install or setup the project for use.


## Documentation

Pointer to reference documentation for this project.


## License

Provided under Cisco Sample Code License, for details see [LICENSE](./LICENSE.md)

## Code of Conduct

Our code of conduct is available [here](./CODE_OF_CONDUCT.md)

## Contributing

See our contributing guidelines [here](./CONTRIBUTING.md)
