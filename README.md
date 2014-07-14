Sign Message
===========

A single purpose small Python script to sign and verify messages with bitcoin private keys.


#### How to use:

Requires ecdsa library. Do `pip install ecdsa` before using script.

###### To sign a message:
    $./signmessage.py -s
    Verify message

    Enter address:
    1HUBHMij46Hae75JPdWjeZ5Q7KaL7EFRSD
    Enter message:
    test message
    Enter private key:
    5KMWWy2d3Mjc8LojNoj8Lcz9B1aWu8bRofUgGwQk959Dw5h2iyw

    Signature:
    
    G0k+Nt1u5boTTUfLyj6x1T5flg1v9rUKGlhs/jPApaTWLHf3GVdAIOIHip6sVwXEuzQGPWIlS0VT+yryXiDaavw=


###### To sign a message:
    $./signmessage.py -s
    Verify message

    Enter address:
    14dD6ygPi5WXdwwBTt1FBZK3aD8uDem1FY
    Enter message:
    test message
    Enter private key:
    L41XHGJA5QX43QRG3FEwPbqD5BYvy6WxUxqAMM9oQdHJ5FcRHcGk

    Signature:
    
    IPn9bbEdNUp6+bneZqE2YJbq9Hv5aNILq9E5eZoMSF3/fBX4zjeIN6fpXfGSGPrZyKfHQ/c/kTSP+NIwmyTzMfk=


###### To verify a message:
    $./signmessage.py
    Verify message

    Enter address:
    14dD6ygPi5WXdwwBTt1FBZK3aD8uDem1FY
    Enter message:
    test message
    Enter signature:
    IPn9bbEdNUp6+bneZqE2YJbq9Hv5aNILq9E5eZoMSF3/fBX4zjeIN6fpXfGSGPrZyKfHQ/c/kTSP+NIwmyTzMfk=

    Message verified: True
