We are given an image avocado.jpg.

Using binwalk on the file shows a zip file named justsomezip.zip.

we then carve it out using 

dd if=avocado.jpg of=justsomezip.zip bs=1 skip=100599

The zip is password protected. To crack the password a dictionary attack can be done using fcrackzip with rockyou.txt wordlist.
The password is found as impassive3428.

Unzipping using this password we get another zip named justsomezip.zip and staticnoise.wav.

The spectrogram of the wav file reads out d41v3ron which is the password of the zip file, which gives us flag.txt


flag: scriptCTF{1_l0ve_d41_v3r0n}
