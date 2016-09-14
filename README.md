# ppmrw-Project-1-CS430-Palmer
Repository for all the code for my Computer Graphics Project for NAU's CS430 class

The Plan:

The structure I plan on implementing at this point in time is to create two functions that will read or write in ppm files in the format described in the instructions for this project.

I will want to create some if statements that will read in the second character of the file since it should either be 3 or 6, in regards to the magic number, to do the write into the other magic number format. 

I will throw an error code if the second character is not  a 3 or a 6 (if I was a grad student I would incorporate 7 into this as well).

Once i have the code up, I will create the image I plan on using in paint to test the program to see if the read and write is successful.

Updated Plan:

Upon further research, the original plan has changed a little to now read the input files into and array that I can then use to convert the images to the alternate formats if necessary and having it all one local array. This will help with the error code throw since the second element of the array should be either a 3 or 6 making it a little easier to manage.
