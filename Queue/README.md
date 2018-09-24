# Azure Service Bus Queue

Azure Service Bus consists of 3 parts, which are sender, reciever and queue. The key benefit of Azure Service Bus is using queue to decoupling sender and reciever, which means sender and reciever doesn't need to work simultaneous in order for service bus queue to work. Sender and reciever can work independently. Also Azure Service Bus doesn't neccessary guarantee FIFO. FIFO can be achieved but again not guaranteed.

There are some adavanced features that we can cover in the late demos. Let First create a simple project which consists of sender and reciever. 