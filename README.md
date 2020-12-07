# World_Pitch
## Author
[PHILIPIA]https://github.com/philipiaeveline/-WORLD_PITCHES)
# Description
A Pitchess motion is a request made by the defense in a California criminal case, such as a DUI case or a resisting arrest case, to access a law enforcement officer's personnel information when the defendant alleges in an affidavit that the officer used excessive force or lied about the events surrounding the ...
## Live Link
[View Site](https://worldpitch.herokuapp.com)

## User Story

* Comment on the different pitches posted py other uses.
* See the pitches posted by other uses.
* Vote on s pitch they have viwed by giving it a upvote or a downvote.
* Register to be allowed to log in to the application
* View pitches from the different categories.
* Submit a pitch to a specific category of their choice.
## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all posts, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with app pitches based on categories and commenting section|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|
## Development Installation
To get the code..
1. Cloning the repository:
  ```bash
  https://github.com/Owiti-Charles/pitch-world.git
  ```
2. Move to the folder and install requirements
  ```bash
  cd pitch-world
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.6 manage.py server
  ```
5. Testing the application
  ```bash
  python3.6 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.
## Technology used
* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)
## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug
## Contact Information 
If you have any question or contributions, please email me at [mikeycharlesm7@gmail.com]
## License
* *MIT License:*
* Copyright (c) 2019 **Owiti Charles**