# Buffer overflow attacks

Buffer overflow attacks, the internet’s most notorious 5,800-day exploit, was first outlined in a US Air Force study on computer security published in October 1972. Buffer overflow attacks exploit a fundamental vulnerability in how computers handle data in memory. They target the stack or heap, critical areas where data is stored temporarily for processor access. Within the stack, buffers are designated areas for dynamic data input. However, many operating systems and programming languages lack the security measures to validate the size of incoming data, allowing oversized inputs to overflow and overwrite adjacent memory areas. This flaw can be manipulated by attackers to execute malicious code, tricking the system into running unauthorized instructions by overflowing the buffer with carefully crafted inputs.

This report explores the process of owning target machines with various OS using buffer overflow exploits. 

All scripts are in the Appendix and the logic is appropriately referenced.

___

| Author | Task |
| ------------- | ------------- |
  | Sana Sajesh  | Windows XP |
 | Dhruti Davey  | Linux |
 | Fatima Patel | Windows 10 with Defender |
