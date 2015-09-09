#movie-history

Movie History was written as a team project from Nashville Software School to make an application that allows the user to search the OMDBA API for movies and organize them as watched or unwatched.  The user can search the database and choose the movie to add. The movies are stored on a firebase database and can be marked us watched or unwatched and be deleted from the database.  The page is searchable via a text box.

##Running the Application

Clone the repo

    mkdir ~/projects && cd ~/projects
    git clone https://github.com/lynnsamuelson/movie-history.git

##Serve the application

Go to the application root folder and start the server.

    cd ~/projects/movie-history
    http-server ./ 
    
##Making your own Firebase Database

To have a database that you can access, go to:

    https://www.firebaseio.com/
    
and make an account.  Then use the JSON file (movie-history-531-export.json) in this repository to initially populate the database.  
    
Now you can open your browser and go to http://localhost:8081 (or whichever port it reports it is using) and you should see the basic mock-up. The application will be displayed along with the movie poster and general information from the OMDBA database.  
