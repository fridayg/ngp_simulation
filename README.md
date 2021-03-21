# ngp_simulation
New Georgia Project Data and Targeting Director Simulation

This code joins together two datasets provided by NGP and uploaded to google cloud (people and attempts).
It pulls all of the relevant information for analysis. It also includes some aggregations, grouping, and renaming for analysis.
It creates a new table with this information in order to push it to Google Data Studio. Google data studio allows creation of graphs and additional aggregations.
Custom fields created in Google Data Studio include: contact rate (total attempts/total contacts), % Attempted (total people attempted/total people in universe), % Contacted (total people contacted/total people in universe).

To start using this code, you'll need access to the two datasets (people and attempts). You'd want to appropriately replace the table/dataset names to match your own uploads - including the name of the table being updated or created at the beginning.
