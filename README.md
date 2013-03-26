Concatenate-Blocklist
=====================

OSX only.

This program can be used, in conjuction with Transmission,
  to automatically merge sereveral iBlocklist files into a
	single blocklist. 
	When supplied with the file location of a 
	'blocklist menu', it will download every individual blocklist 
	(in the p2p format), unpack any gzip files, and concatenate them 
	all into a single blocklist (in the p2p format), placed into 
	Transmission's /blocklist/ folder. The 'blocklist menu' must 
	list 1+ URLS, separated by a newline character.
	All downloaded blocklist files are assumed to be in gzip format,
	as per standards on iblocklist.com. However, any file with the
	'.txt' suffix will be treated as a plain-text list in the p2p
	format.
	The suggested use for this program is for it to be run at user
	login, and the 'blocklist menu' file be stored in 
	/Application Support/Transmission/.
	
	Copyright 2013, Adam David Cox 
	adam.david.cox@gmail.com
	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

    See <http://www.gnu.org/licenses/> for a copy of the GNU General Public License
