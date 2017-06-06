# Minds and Machines Berlin Hackathon 2017
# Electrification Challenge - Grid GIS Dataset

## Who is ESB?
Electricity Supply Board (ESB) was established in 1927 as a statutory corporation in the Republic of Ireland under the Electricity (Supply) Act 1927. With a holding of 95%, ESB is majority owned by the Irish Government with the remaining 5% held by the trustees of an Employee Share Ownership Plan.  

As a strong, diversified, vertically integrated utility, ESB operates right across the electricity market: from generation, through transmission and distribution to supply. In addition, ESB extracts further value at certain points along this chain: supplying gas, using our networks to carry fibre for telecommunications, developing electric vehicle public charging infrastructure and more.


## What is the challenge?
Driving toward a low-carbon future will require the insertion of more and more renewable energy production or electric vehicle charging stations. Grid management relies heavily on geographical models to forecast and locate congestions or assess the impact of connection of a new production or load node.

In practice, grid models can turn out to be quickly outdated especially when it comes to the complex branching of electricity distribution networks. As the physical grid configuration will tend to change more frequently and as the grid model will become more detailed, keeping this model up to date will require advanced tools. To that end, GE Energy Connections develops a new set of software service on Predix dedicated to geographical data management: the Intelligent Mapping service and Dynamic Mapping service.

You can find our more here:
https://sw-intelligent-mapping.github.io/smallworld-mapping-services/

Your mission is to build the prototype for a new tool to visualize and edit a grid model. You can use the grid model sample from ESB and the Intelligent Mapping API to test your solution. You can also combine this data with external data sources.
For instance you could use
- a StreetView API to build and update an advanced electrical pillar inventory
- a satellite view API to build and update a solar panel inventory


## What's in the dataset?
The provided dataset is a grid model from ESB for a portion of the Irish grid with geographical data for the following kind of elements:
- bundled conductors
- pillars
- low voltage (LV) overhead open wires


## How to access the dataset?
The ESB grid model sample data has been loaded in an Intelligent Mapping service instance pre-provisionned in your team space on Predix. This service is bound to a User Account and Authentication server (UAA) instance also created in your team space. In this UAA instance we created a UAA Client dedicated to manage the access to your Intelligent Mapping instance.
Here are the credentials for this UAA Client:
- ClientID: XXXX
- Client secret: XXXX

Your team space has also been pre-provisionned with a seed app that is already bound to your Intelligent Mapping service instance for a basic visualization.
You can test this Intelligent Mapping seed app using the dedicated UAA User credentials below:
- UserID: XXXX
- User secret: XXXX

**NB:** If you corrupted the ESB data in your Intelligent Mapping service instance you can reach out to the Hackathon tech staff to reset your instance.

You can also find the original DWG files in this GitHub repo.