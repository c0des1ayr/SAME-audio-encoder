# Emergency Alert System (EAS) Specific Area Message Encoding (SAME) Encoder

During this Era of Our Perpetual 2020 COVID-Themed Lockdown, I assumed there'd be a bunch of emergency broadcasts sent over the FM airwaves giving us further
directions, so I did what any responsible emergency-obsessed turbonerd would do and purchased a SAGE Alerting Systems EAS ENDEC (Encoder/Decoder).

[Here's a quick background on how EAS SAME headers work.](https://www.youtube.com/watch?v=Z5o1sfXXf9E)

During the late 90's / early 2000's, this is a device that would sit in the headend room of TV / FM / AM stations, listen for EAS SAME signals on neighboring
stations, and, if the specified information matched the predefined filters, rebroadcast the emergency message on its local station.

Anyway, since I'm trying to flex my coding skills right now, I wrote a Python script that generates these tones!  Tested and is correctly interpreted by my SAGE
EAS ENDEC.

[YouTube demo!](https://www.youtube.com/watch?v=OVxHkMDX2F8)

# Important Note

Please please please please PLEASE use this responsibly.  Did you just buy an old ENDEC on eBay and want to put it through its paces?  This is the script for you!

Don't use this to hack / exploit anything.  I made this for funsies in a few hours.  Please use it accordingly.

Also if you create a fork of this repo, please credit the original project :)
