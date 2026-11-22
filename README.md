# This is a preservation effort for Ron Gage's ABPLC5 library
  
  It also aims to be a soft fork that modernizes the code and fixes any lingering bugs that might be there. The goal is to make sure that it compiles and runs correctly, and to eliminate any edge cases that cause crashes or logic errors.
  
  One of the branches will preserve the 1999 version of Ron's code.
  
  The 1999 version predates the addition of a GPL license, and is the only version that I had previously used successfully. I may add something like a GPL license, but the 1999 branch will be available forever under his original license, which merely states that you must share any fixes or improvements back with him, assuming that you can reach him.
  
  The C standard has evolved since 1999, and so have industry best practices. I'm having AI scan the code for issues. I'm also reformatting the code for more modern and consistent formatting standards. I will accept pull requests that were made with AI assistance, provided that they are accompanied by the submitter's understanding of each line of patched or updated code, with their ability to make changes if I see fit. I may ask for formatting changes before I accept a pull request.
  
  The primary function of this code is to read and write data to an Allen Bradley PLC5 over Ethernet. This includes PLC5 compatible PLC's like SoftPLC. It is not intended to support newer versions of Allen Bradley PLC's, although I might consider patches for that from someone that has access to said newer hardware and is willing to maintain those patches for it.
  
  Ron gave this to the world, for free, and I want to keep that going. Allen Bradley would charge you an arm and a leg and your first born child for it, and split it up into multiple hyper expensive packages while making it confusing to discern which parts you actually need for your project. I want to see people create things with it.