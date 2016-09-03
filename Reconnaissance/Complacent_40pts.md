These silly bankers have gotten pretty complacent with their self signed SSL certificate. I wonder if there's anything in there. [complacent.vuln.icec.tf](https://complacent.vuln.icec.tf/)
===
---
When you enter the website, you will encounter a Privacy error.

1. Go to url bar and click the lock icon "View site information" in chrome.
    > "Your connection to this site is not private. Details"

2. SHA-1 Certificate
3. View certificate
4. Details

    >Issuer:
    CN = complacent.icec.tf
    OU = Flag: IceCTF{this_1nformation_wasnt_h1dd3n_at_a11}
    O = Secret IceCTF Buisness Corp
    L = IceCTF city
    S = Kingdom of IceCTF
    C = IS

![sslCert_info.png](https://github.com/HLOverflow/icectf-Writeups/blob/master/Reconnaissance/sslCert_info.png "sslCertInfoLeak")

---
IceCTF{this_1nformation_wasnt_h1dd3n_at_a11}
