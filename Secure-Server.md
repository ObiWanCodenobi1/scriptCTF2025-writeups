We are given a capture.pcap file. We can inspect it using Wireshark to find the following 

flag XOR key1: 151e71ce4addf692d5bac83bb87911a20c39b71da3fa5e7ff05a2b2b0a83ba03

flag XOR key1 XOR key2: e1930164280e44386b389f7e3bc02b707188ea70d9617e3ced989f15d8a10d70

flag XOR key2: 87ee02c312a7f1fef8f92f75f1e60ba122df321925e8132068b0871ff303960e

XORing all three gives us the flag in hex

flag: scriptCTF{x0r_1s_not_s3cur3!!!!}
