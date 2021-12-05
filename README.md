# JSON Resume Theme: To The Point (black and white)

## Theme Goal
The theme was designed to focus on the role experience items, leaving the additional data on the side (right column).
The contacts were placed in a non-intrusive way. Nevertheless, the contacts are easily perceived.

## Install
1. Node.js
**To install** use the available installer in [node.js](https://nodejs.org/en/).
Note: The used and tested *node.js* version was 14.17.0 and the *npm* version was 6.14.13.
Note: To check the *node.js* installed version run:
	```shell
	$node -v
	v14.17.0
	```
	Note: To check the *npm* installed version run:
	```shell
	$npm -v
	6.14.23
	```
1. JSON Resume CLI
**To install**:
	```shell
	$npm install -g resume-cli
	```
	Note: To check the *npm* *resume-cli* package installed version run:
	```shell
	$npm view resume-cli version
	3.0.4
	```
1. Download or clone the repo to local:
   ```shell
	git clone https://github.com/PauloBrazFigueiredo/jsonresume-theme-to-the-point-bw
   ```



4. Create a `resume.json` file:
   ```sh
   cd jsonresume-theme-apage
   resume init
   ```
5. Serve your file with the theme:
   ```sh
   resume serve
   ```