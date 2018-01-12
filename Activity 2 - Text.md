Yaroslav Leontenko (V00802386)

## Activity #2

### Design:
See the "Activity 2 - Design" file.

### What:

A visualisation proposal for the SeaSpan vessel schedule.
DataSet type given: Table
Attribute types:
	- Categorical: Vessel names, destination names;
	- Ordered Quantitative Cyclic: Time.
### Why:

Provides a better visual overview of what vessels are going to what destination, with what load and at what given times.
This draft was designed with the SeaSpan employees in mind and probably the additional data it provides wouldn’t be very practical for the passengers themselves.
Actions:
	- Present: present the original data in a more visual way;
	- Derive: derive results from the original tables;
	- Lookup: should be easier to just look up the needed data, since the location and the targets are known.

### How:

Utilize the table concept with additional data represented by colours and symbols.
	- Order: order data by days of the week and time;
	- Colour: use colour to represent the different vessels;
	- Motion: show motion of the vessels to determine the direction of the trip.
  
### Pitfalls:

PF4: The data for the load is not available in the initial tables; <br/>
PF6: For users, it’s easier to just type in their destination rather than looking at the tables, so only might be useful for the stakeholders; <br/>
PF7: No previous experience in visualizing data; <br/>
PF9: The tables might be inconvenient to look at, but they still work and if data gets too big, the visualization might get a bit cluttered (e.g.: colours will blend); <br/>
PF20: Doesn’t give any information about the berths, putting them inside the vessel bars might pollute the visuals. <br/>
