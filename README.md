Process of performing the task - 

For Question 1 - 
For flag = 0 -
Bring the file to the end of the file.
Then read one chunk of the file, but in the reverse order
Then, write the character from the chunk into the new file

I know, this is not the most optimal approach, but this was my first programming assignment, so nothing better was expected from me.

For flag = 1 - 
Divide the work into 3 parts- start, mid and end.
For start of the file, read the file from the left index of the argument to the start of the file, writing the characters of the chunk in reverse
For mid part, keep reading the chunks from left index to right index and write the characters in the same order.
For end part, read the file from end of file to the right index, printing the characters in that order.


For Question 2 - 
For checking whether the contents of the file are reversed or not, use the same logic as Question1 flag = 0.
Rest print all the permissions using stat() system call.

Assumptions - 
The chunk size is 5 B(can be changed later) for flag = 1 and 5MB for flag = 0.
The output file and directory are created in the same directory as the input file.

Error Handling - 
Following errors are handled in this assignment-
Inability to read/write from/to the files
Left index > right index (in case of flag = 1)
Inability to access a particular file position.# AOS_Assignment1
