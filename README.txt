NAME:
	cmdplus
FUNCTION:
	add some extra functions to the cmd(Windows)
VERAION:
	0.01
AUTHOR:
	code_tin 2005
MODIFY:
	jiangxin 2014

Copyright (c) 2005, code_tin


All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
Neither the name of the code_tin nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

FILES:
	README.txt It's the file itself.
	backup.cpp The source code created by the author code_tin in 2005.
	main.cpp The source created by jiangxin according to the previous files edited by code_tin.
	History.txt The log file when you run the program, in which you can get the all commands that you used ever.
	main The binary program.
	
How TO USE:
	Run the binary file named main, you can get the History.txt file which records the commands that you have ever used in the cmd windows.
	However you can also use "Win-R" and input "PATH_OF_THE_MAIN_FILE/main -p PAHT_OF_THE_LOGFILE -n LOGFILE" to custom yourself need.
		PATH_OF_THE_MAIN_FILE: the path of the binary program main. (NO DEFAULT CHOICE)
		PAHT_OF_THE_LOGFILE: the path where you want to put your logfile. (DEFAULT CHOICE IS THE DIRECTORY WHERE YOU ARE)
		LOGFILE: the filename of your logfile. (DEFAULT CHOICE IS "History.txt")
	By default the logfile can pick up the time at which you use each command in the cmd windows. However if you don't want keep the in the logfile, just input the choice "--ntime".
	By default the logfile can pick up the time with the accuracy of second. However if you want to pick up the time with the accuracy of millisecond, just input the choice "--mtime".
	
