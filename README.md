# The Shmowzow Esoteric Language

![Shmowzow](https://raw.githubusercontent.com/shmowzow/shmowzow-lang/master/shmowzow.gif)

Shmowzow's syntax highlighting support for some text editors. 

##Using

### Sublime Text

#### Install using Git

You can install the markup and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime
Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

```sh
$ git clone https://github.com/shmowzow/syntax-highlighting.git "Shmowzow Lang"
```

#### Download Manually

1. Download the files using the [GitHub .zip download](https://github.com/shmowzow/syntax-highlighting/archive/master.zip) option
2. Unzip the files and rename the folder to `Shmowzow Lang`
3. Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
4. Copy the folder into your Sublime Text `Packages` directory
5. Have fun!

## Commands/Scopes

Command     		      | Scope																																														
---						  | ---  																																															
`Shmowzow` / `shmowzoW`   | `keyword.control`  																														   
`SHMOWZOW` / `shmowzow`   | `constant.numeric`																															
`ShMoWzOw` / `sHmOwZoW`	  | `support.constant`																																			 
`ShmoWzow` / `sHMOwZOW`   | `entity.name.function`																																		
`c:` 					  | `string.quoted.double`																																							

> *Remember*: Shmowzow ignores all characters except the eight commands; so no special syntax for comments is needed 
(as long as the comments don't contain the commands). The `c:` is not actually necessary for comments - it just makes
the things more beautiful.  

##License

Shmowzow's syntax highlighting support is distributed under the MIT License, available in this repository. All 
contributions are assumed to be also licensed under the MIT License.

> Adventure Time is an American animated television series created by Pendleton Ward for Cartoon Network. Shmowzow Language
*does not* have any rights over anything related to the series; images, logos, and everything related to the show have All
Rights Reserved to Cartoon Network, A Time Warner Company.