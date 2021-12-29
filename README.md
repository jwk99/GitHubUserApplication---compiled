# GitHubUserApplication
Program to browse user repos.
## Description
This program is made in accordance with Allegro's internship requirements. It's purpose is to: list repositories and stars of chosen user, sum stars of all repositories owned by given user and to list languages used by user and count bytes of code in these languages.
## Getting started
### Dependencies
- Java 14
- Windows 10(probably)
### Installing
- Simply download this repository and unzip it to the folder of your choice.
### Executing program
- Run cmd.exe as admin.
- Use cd command with path to the folder with file allegro.project-0.0.1-SNAPSHOT.jar. For example:
`cd C:\Users\your_username\Desktop\githubuserrepos`
- After moving to this folder, type: `java -jar allegro.project-0.0.1-SNAPSHOT.jar`
### Using program
This program has 3 simple functions that were mentioned in the description. All of following commands have to be typed in the address bar:
- to list repositories and stars for chosen user, type `127.0.0.1:8080/githubtest/*user_name*/repos`
- to obtain sum of stars of all repositories owned by given user type `127.0.0.1:8080/githubtest/*user_name*/totalstars`
- to list languages used by user and count all of bytes of code in these languages type `127.0.0.1:8080/githubtest/*user_name*/languages`
## Notes
GitHub may block the connection for about an hour if the query is too frequent or too big. If this happens, page won't load and soon after it the browser will display error code 500.
## Authors
Jan Wojciech Kruk
[@jwk99](https://github.com/jwk99)
## Version history
* 0.0.1 - initial release
## Future ideas
* simple UI
* work on authentication (if possible) to eliminate problems with GitHub's rate limit
