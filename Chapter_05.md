
# Chapter 5

## Digital Signals and Digital Encoding
- Digital encoding is the conversion of data into a digital pattern acceptable to the network media.
- A unipolar digital signal fluctuates between a positive voltage level and zero-volt level.
- A bipolar digital signal fluctuates between a positive voltage level and a negative voltage level.
- Manchester encoding, used on LANs, is characterized by the digital pulse transitioning during the midpoint of the timing period.
- A synchronous signal is synchronized with a reference signal for proper timing.
- An asynchronous signal is not synchronized with a reference signal and uses a binary pattern to determine the stop and start of the signal.

## Data Packaging and Transmission
- A parity check is used to check the integrity of data.
- A cyclic redundancy check (CRC) identifies and corrects errors.
- Data encapsulation surrounds raw data with information needed for delivery.
- Terms like segment, frame, datagram, and protocol data unit (PDU) describe blocks of data.
- A protocol data unit (PDU) is the most technically correct term for data packaging.
- Connection-oriented protocols establish a connection, transfer data, and then release the connection after communication ends.
- Connectionless protocols send data to the destination without establishing a connection.
- Circuit-switching networks establish a physical connection between two points.
- Packet-switching networks establish a logical connection and may use different physical paths for data transmission.

## Data Codes
- ASCII, Unicode, and HTML are coding standards that represent the written word.

## Protocol Frame Structures
- Various protocols package data in particular ways.
- The User Datagram Protocol (UDP) frame structure contains data, destination and source information, packet length, and error checking.
- Ethernet II and 802.3 frame structures are generally compatible but not fully.
- A broadcast frame is intended for every computer on the network, while a multicast frame is for a specific group.

## Data Encoding, Transmission, and the OSI Model
- The OSI model has seven layers explaining the process of encapsulating data for network communication.
- The OSI model is sometimes referred to as the protocol stack.
- The application layer is the communication point for applications installed on a device.
- Data is packaged into a universally agreed-upon form at the presentation layer, where encryption also occurs.
- The session layer establishes a dialog between source and destination.
- The transport layer manages the flow of data to and from the destination.
- The network layer routes data packets across WAN, MAN, or GAN.
- The data link layer organizes data into frames or packets for transmission.
- The physical layer deals with the media hardware and network topology.
