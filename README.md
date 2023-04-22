# PYNQ_Mathematically_Generated_Images

The project was to create mathematically generated images using the PYNQ-Z2 board.

The works in this project were based on the work by Hamid Naderi Yeganeh.
This can be found at https://blogs.scientificamerican.com/guest-blog/making-mathematical-art/


This project is targeted for the PYNQ-Z2 board - information on how to set this up can be found at https://pynq.readthedocs.io/en/latest/getting_started.html

The System_Generator_Files folder contains the .slx files to generate the IP for each design - if you wish to do this

The output folder contains the intended output of each design.

The remaining folders each contain a Jupyter notebook and the corresponding .hws and .bit files for each design.
The contents of these folders are required to be upload to the board.

This can be done by running the following in a terminal window on the baord

sudo pip3 install git+https://github.com/AndrewFerg05/PYNQ_Mathematically_Generated_Images.git

or alternatively drag the folder of choice manually onto the board.

Simply choose which design you wish to run, upload that folder to the board, and run the Jupyter notebook

 
