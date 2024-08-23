# QKD-EncryptoR-DecryptoR
This project focuses on using Quantum Key Distribution to encrypt or decrypt a message between two quantum channels.

Abstract.
In this project we have used the Quantum Key Distribution(QKD) to encrypt and decrypt
the message between the communication channel. We have utilized the Cirq library
developed by Google to create the Quantum Key for the secure communication and
cryptography of our message\information. We have developed mainly four function
which will carry out the deed in securing the message through the channel namely:
(i)Quantum_Key() 
(ii)Measure_Quantum_Key 
(iii)EncryptoR() 
(iv)DecryptoR()
Introduction
What is QKD?
In very simple and concise manner Quantum Key Distribution shortly QKD is the
protocol used for securing the communication channel with the help of a Key which is
unique for that channel, and that Key can be used for the encryption and decryption of
the message.
As QKD contains the “Quantum”(the mighty), one can assume that we are using
QuantumPhysics\Quantum Mechanics principles somewhere. Yes! Indeed we use the
pillars of Quantum Mechanics that are Superposition and Entanglement.
Now we get the crux about the QKD and its application in securing the communication
channel by utilizing the Superposition and Entanglement, which helps in making the Key
super secure against the external attacks and threats.
The implementation of encryption and decryption can be achieved as follows:
1.1 Quantum Key Generation.
The first step for our encryption will be to generate a secure Quantum Key. For
this we have developed the Quantum_Key() function which will generate a key
for the given number of bits.
1.2 The Encryption of the Message(EncryptoR).
After generating our Quantum Key and Measuring it we will feed our Message
along with the Key to the EncryptoR() function will which take the formers as
its assignment and will make sure the original message get disfigured before
sending to Bob(receiver).
1.3 The Decryption of the Encrypted Message(DecryptoR).
Now after the Alice(sender) sent the encrypted message through the quantum
channel to the Bob(receiver) our Quantum Key will make sure that it will be only
decrypted by the Bob only and If any intruder tries to tamper this message in
Between then it can easily be recognised by the Bob at the time when it is
Measurement period of the message.

What if there is the presence of Eavesdropping.
Now one can easily encrypt and decrypt the message across a quantum channel with
the help of the Quantum Key Distribution and will make sure that their messages\-
information are highly secured. But one can think: What will happen if there is breach in
Quantum Channel by the Eavesdropper?What will happen to our original message? Will
it be accessed by the Eavesdropper?How will the receiver make sure they are getting
the right message\information.
If any eavesdropper is present during the development phase of the quantum state then
this will pose a threat for both the sender and receiver, there are chances of theft of part
of the information by measuring the quantum state.
And that part of measurement is a threat as well as the protection(kind of) for the
quantum channel if there is presence of the eavesdropper are it measure the quantum
state then this measurement will break the continuity and will introduce the error in the
quantum channel and at the time when the message is decrypted the receiver(Bob) will
try to match the part of the Key of both ends, for that quantum channel. There will be an
error in the message that is decrypted and this will give the hint about the eavesdropper
and will make the receiver(Bob) and sender(Alice) aware about it.

Quantum Key Distribution is very crucial when the classical cryptography protocol fails
in the times when we are dealing with and developing the Quantum Computer for
communication and Scientific collaboration.
There are several points which can be highlighted which gives more impact on
developing new quantum encryption and cryptographic algorithms.
(1) In recognising the future threats.
(2) In developing a more secured global network channel.
(3) In detection of Eavesdropping.
(4) In making Quantum-Cryptography more safe and secure.
(5) In new Scientific and Technological innovations.
