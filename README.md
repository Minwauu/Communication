# Communication

## Serial and parallel data transmission
Computers can transmit data between their different components in two ways: serially or in
parallel. 

### Serial 
Serial data transmission 
In serial data transmission, data is sent one bit at a time over one communication line (this 
is usually a metal wire, but could also be an optical fibre or a wireless channel). 

Serial data transmission is frequently used for transmitting data over medium to long 
distances (computationally speaking), such as from wired peripherals like mice and 
keyboards to your computer

### Parallel 
Parallel data transmission uses numerous parallel communication lines in order to send 
multiple bits between components in a computer simultaneously. 

The more lines that a parallel communication medium uses, the more data can be
transferred simultaneously. 

Each of the communication lines that forms part of a 
parallel communication medium will have slightly 
different electrical properties, meaning that the time 
taken for one bit to be transferred will differ slightly from 
line to line. This means that bits sent together may not 
be received together, a problem referred to as skew. 

## Adv of serial over parallel
Serial data transmission doesn’t suffer from skew or crosstalk making it a more reliable 
communication method, especially over long distances. Serial communication mediums, 
which use just one line, are cheaper to install than parallel mediums which use more than 
one line. 

## Skew
Skew is when bits sent together may not be received together.
Skew is worst over long distances and, in extreme cases, can lead to bits from different
pulses overlapping, causing corruption of data. Furthermore, parallel communication 
mediums are more expensive than their serial counterparts because of their use of 
multiple lines. For these reasons, parallel data transmission is most often used over short 
distances, such as between parts of the processor and within RAM. 
Another issue, referred to as crosstalk, can occur with parallel data transmission. When 
communication lines are tightly packed, signals from one line can “leak” into another, 
another cause of data corruption. 

## Symbol
A symbol is a particular pattern of bits represented by a signal. For example, a symbol of 
four bits might be 1101​.

## Baud rate
A communication system’s Baud rate is the number of signal changes in the medium per 
second. 1 Baud (or 1Bd) is equal to 1 symbol change per second.

## Bit rate
A communication medium’s bit rate refers to the number of bits that are transmitted over 
the medium per second. This is often measured in bits per second (bps). 

Therefore, a communication system’s bit rate is equal to its Baud rate multiplied by the 
number of bits per signal in the communication medium. 

Bit rate = Baud rate × Number of bits per signal 

A communication medium’s bit rate will be higher than its Baud rate if there is more than 
one bit sent per signal.

## Bandwidth
Bandwidth, expressed in Hertz, relates to the range of frequencies that a communication 
medium is capable of transmitting. There is a direct relationship between bandwidth and 
bit rate. Higher bandwidth results in a higher bit rate. 

## Latency
Latency in a communication medium, often measured in milliseconds, is the difference in 
time between an action being initiated and its effect being noticed. For example, if you 
press the “R​” key on your keyboard and the letter R appears on screen 26ms later, the
latency in the link between your keyboard and the application you are using is 26ms.
Latency usually increases with distance. 

## Protocol
A protocol is a set of rules relating to communication between devices. International 
organisations decide upon and publish protocols which allow devices made by different 
manufacturers in opposite ends of the world to communicate seamlessly. 

## Synchronous and asynchronous data transmission 

### Synchronous transmission
When data is transmitted using synchronous transmission, a 
clock signal (which is shared by both the sender and the 
receiver) is used to time when signals are sent. Synchronous 
data transmission is used within the busses of a computer’s 
processor in the fetch-execute cycle. 
The signals, which are sent at regular intervals, will be 
received in the same order that they were sent. This makes 
synchronous data transmission suitable for transmitting 
information in real-time systems. 

### Asynchronous transmission

In asynchronous data transmission, the 
requirement for a shared clock signal is done 
away with by using start and stop bits to 
indicate the duration of a transmission. 
The start bit can be either a 0​ or a 1​ and the 
stop bit is always the opposite of the start bit. 
The sender and receiver must use the same Baud rate and need only synchronise their 
clocks for the duration of data transmission. 

