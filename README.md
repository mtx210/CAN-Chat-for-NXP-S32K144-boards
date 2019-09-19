# CAN-Chat-for-NXP-S32K144-boards
A simple transmit/receive chat application for NXP S32K144 boards using C and CAN bus

Following example projects for NXP boards in Design Studio, it is crucial to modify the FLEXCAN.h file line defying which node is the
program used for. Comment the definition of NODE A to create NODE B. That is pretty much it.

The program can transmit 32 bits of information at a time due to hardware's limitations so 8 characters can be sent at once. No problem
with longer messages, just keep typing and remember to indicate message end with '#' before pressing enter. It will indicate to the
receiver to create new line.

to be continued :)))
