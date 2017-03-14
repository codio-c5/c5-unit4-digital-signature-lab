{Check It!|assessment}(multiple-choice-117556987)
|||guidance
# Solution
**her private key**
|||
{Check It!|assessment}(multiple-choice-2471947862)
|||guidance
# Solution
**Validity period of the certificate**
**Algorithm to verify the signature**
**Signature of the issuer**
**Public key of the owner**
|||

Pending Questions:
1: Describe how asymmetric (public) key cryptography is used for providing authenticity through digital signatures.
*Answer: A signature on a message will verify only if the signature was signed using the private key that goes with the public key used for verification.*
2:The certification path for the digital certificate for amazon.com can be seen in the picture below. Explain how the certificate for www.amazon.com is verified by appealing to the chain of trust among certificate authorities.
![](.guides/img/amazon.png)
*Answer: To verify that the digital certificate of Amazon is valid, the signature on it is verified by using Symantec Class 3 Secure Server CA – G4’s public key (which is on CA’s certificate).  The certificate of Symantec Class 3 Secure Server CA – G4 is verified using Verisign’s public key.*
