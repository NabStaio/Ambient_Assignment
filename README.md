
# AMBIENT INTELLIGENCE ASSIGNMENT

## THE IDEA

The name of my project is **AI-Read Outlet**.
The idea is to create a smart environment where people can buy books in a fast and pleasure way.
The problems are that in libraries we waste time in searching our favourite books, long queries for buying them and low surveillance. 
This project can solve this problems:
* Introducing a preference-based connection between rooms can reduce the books' hunt and browse directly your desired ones. This is done by a stereo camera that gathers person's image, elaborates data and send them to a computer that through an algorithm displays which room is in line with the costumer. The choice is done by selecting the icon on a screen near the door. Once selected the room, you are brung directly to the wished one. Obviously near the door there is a switch for open it.  
* To avoid long queries it is possible to buy a book simply reading the barcode on the cover, indeed in the barcode is implemented a RFID antenna which can be read by the client's phone.
* To prevent robberies, vandalisms and book's exchange on incorrect shelves, the stereo camera works also as a supervisor in combination with a PIR sensor that reacts to people who stole books. Cases are mounted on shelves that can be opened only by switching an interrupt near them.

## POSSIBLE STRUCTURE

In Fig. 1 it is illustrated a possible structure of the shop (the one described in the ontology).

<img src="OutletStructure.jpeg" width="500" height="500" /> _Fig.1 Plant of the shop_



As it's shown, all the rooms are connected at the entrance and are initially close.
Books are divided in specific shelves associated with a specific color that indicates their category.
Rooms have names related to the categories, e.g. NinthArt room has origin from the classification of arts, comics are the ninth art in the world.
Thus, the client will start his journey in the shop entering in the entrance passing through a PIR sensor and catched by a stereo camera.
In this case the outlet owner can see if a person is entered or not, and the camera can process the data of the customer checked, send them to a
computer, compute the algorithm and suggest the preferred room to visit on the display near the door. Once near it, the person selects the place
and will open the door by switching the button on the side; in this way also the selected room's door is opened, drawing a path to the desired chamber.
In the room the customer can browse every book and buy how many he wants just by reading the barcode with his phone.
Hovewer, to take a book a built-in case needs to be open, and it's done by switching the interrupt on the side.
Fig.2 and Fig.3 are a zoom of how shelves and books are designed.


<img src="ShelfwithCaseandSwitch.jpeg" width="500" height="500" />  _Fig.2 A Shelf with case and a switch sensor_

<img src="BookwithRFID.jpeg" width="500" height="500" />  _Fg.3 A Book with the barcode (RFID Antenna)_






