# ConferenceAsync
Async version of LAC 5.2 Conf-Offer / Conf-Mgmt

This is an upgraded version of the LAC 5.2 Conf-Offer / Conf-Mgmt samples:
* simpler - Conf Mgmt has 1 resource (not 3), and 25% less code
* async - Conf Mgmt uses an async approach for processing messages

To install:
1. Stop LAC
1. In the <LAC-install>/CALiveAPICreator folder:
    1. Rename ConfManagement folder (e.g., add a Z)
    1. Copy the ConfManagement from the zip
1. Restart LAC
1. Rename the existing Conference Offers / Conference Management APIs
    * use the API Properties > Details URL Fragment screen
    * again, just add a Z
1. Import the 2 json projects
    * as for the initial LAC install, you must activate and restart the Connections
  
  
The Learning Center doc, of course, will be out of date.  The zip contains an updated image.
