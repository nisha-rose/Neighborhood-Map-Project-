#frontend-nanodegree-neighourhood-project
=========================================

##How to Run
=============

    1.Download the *frontend-nanodegree-neighourhood-project* folder.
    2.Open the file named *index.html*

##Functionalities
=================

    1.Can search for a loction in list using search box
    2.Clicking a location on the list displays unique information about the location, and animates its associated map marker
    3.Google street view is provided in the infowindow.

    *google map API is used to provied  google map for the users.
    *wikipidea API is used to provide related link about the place.

##Adding new Locations to list.
===============================

steps:
    1.Open the file named *app.js*
    2.Add the loction name and latlong data in the locations array in the following format
            {
            title: "new location name" ,
            location: {lat: value, lng: value}
        }
    3.Save it.

##Attribution
=============
    * Modified code from the Udacity courses.
    * Modified code from 'http://opensoul.org/2011/06/23/live-search-with-knockoutjs/' for search implementation.