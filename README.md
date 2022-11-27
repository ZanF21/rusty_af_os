# rusty-afOS
A rust OS

- Creating a rust binary that runs on bare metal without any underlying OS.(well bare bones already means that)
- 2022_10_28 :
  - Built the OS!!, When booted it just prints TEXT on the screen .... is that even an OS?? I mean ... i am using a program to run directly on the the cpu and make it output stuff ... so that is technically an "Operating System" ig
- 2022_11_20 : 
  - Built the tester which returns the results from a serial port (using a crate) and prints it on the console so qemu doesnt need to display anything :)
  - P.S. Im excited to be doin this :))))))
- 2022_11_27 :
  - Finally figured out why it wasnt compiling :')
  - Needed LLVM tools .... added cmoponent from rustup, can finally get back to testing
  - Finished writing the tests part ... am writing this after commiting it all :')