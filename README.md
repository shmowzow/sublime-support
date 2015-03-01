# The Shmowzow Esoteric Language

![Shmowzow](https://raw.githubusercontent.com/shmowzow/shmowzow-lang/master/shmowzow.gif)

Shmowzow's syntax highlighting support for some text editors. 

##Using

### Sublime Text

1. Download the markup. 
2. Unzip the files and rename the folder to `Smowzow Lang`.
3. Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`.
4. Copy the folder into your Sublime Text `Packages` directory.
5. Have fun!

## Scopes/Commands

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