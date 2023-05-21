# Practical Case 3: RAM Memory Analysis
By Luis Daniel Casais Mezquida  
Mobile devices security 22/23  
Bachelor's Degree in Computer Science and Engineering  
Universidad Carlos III de Madrid


## Project statement
This time your friend asks for your help in obtaining the user's unlock password of an Android mobile phone.  
To do so, we have a RAM image (`i900-CM.bin`). As clues for the case, we know that the password has the format `INS{xxxxx}`. We also have a zip file (`i9100-CM_3.0.64.zip`) with two files, `System.map` and a `module.dwarf`, which will allow you to analyse the RAM image with the [Volatility](https://github.com/volatilityfoundation/volatility) tool.

The zip file with all the data can be found [here](http://lightweightcryptography.com/SDM2022/SDM_RAM.zip).

With all this information, what is the user's unlock password?


## Useful links
- [Volatility foundation](https://www.volatilityfoundation.org)
- [Volatility's source repository](https://github.com/volatilityfoundation/volatility)
- [Hashcat](https://hashcat.net/hashcat/)
- [Password cracking in Android](https://www.pentestpartners.com/security-blog/cracking-android-passwords-a-how-to/)
- [More cracking in Android](https://www.web3us.com/cyber-security/breaking-samsung-android-passwordspin)