## Summary

Mybucks.online is a **password-only, self-custodial cryptocurrency wallet** built with Javascript. It generates a private key from your password and passcode using an industry-standard, verified **one-way hash function**. Your private key forms your account, allowing you to transfer, receive, and hold your crypto assets securely.

As a hash function, the **scrypt** Key Derivation Function (KDF) increases the computational effort required to crack passwords, effectively delaying brute-force attacks and making them impractical.

It fully runs on **your browser side** without using any storage or invoking any 3rd-party APIs for key management. It instantly generates your private key from your password input, and whenever you close or refresh, there is no footprint. This absolutely protects your privacy.

With mybucks.online, you can send cryptocurrency and even **wallet itself** via a URL. The recipient simply clicks the link to open the wallet and take full ownership.

Try this link to the demo wallet:  
https://app.mybucks.online/?wallet=VWnsSGRGVtb0FjY291bnQ1JgIxMTIzMjQCb3B0aW1pc20=_wNovT

## How to Use

1. Visit `app.mybucks.online`.
2. Input your password, confirmation, and passcode.  
  Test credentials:  
    password: **DemoAccount5&**  
    passcode: **112324**
3. Click `Open`.
