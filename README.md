# Virtual_Memory

# Usage

**$make**

**$./Proj3**


# Design Idea:

1.Check the TLB(translation lookaside buffer), if TLB miss then goto PAGE TABLE, if PAGE HIT then update TLB(using LRU) and return physical addresss.
  
2.If PAGE FAULT, goto BACK_STORE to find the frame number, and update PAGE TABLE and TLB. Return physical address.
  
3.To start, because we don't load frame number from BACK_STORE. There will be at least 16 TLB MISS,16 PAGE FAULT, until finishing update.

# Example outputs:



# Project Details:


