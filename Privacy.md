# Privacy in Bot Framework

Bots are more and more prevalent in key business areas like financial services, retail, travel, and so on. A bot might collect very sensitive data such as credit cards, SSN, bank accounts, and other personal information. So, it is important that bots are secure and protect against common threats and vulnerabilities.

**Azure Bot Service automatically encrypts your data when persisting it to the cloud**. Encryption protects your data and to help you to meet your organizational security and compliance commitments. Data in Azure Bot Service is encrypted and decrypted transparently using 256-bit AES encryption, one of the strongest block ciphers available, and is FIPS 140-2 compliant. A checksum technique is also used to detect tampering of data that is not encrypted, such as GUIDs.

## **Recommended Steps**

**Each bot is its own service, and developers of these services are required to provide Terms of Service and Privacy Statements per their Developer Code of Conduct.**
If your app integration handles users' personal information (personal information includes all information or data that identifies or could be used to identify a person, or that is associated with such information or data. Examples of personal information include: name and address, phone number, biometric identifiers, location, contacts, photos, audio & video recordings, documents, SMS, email, or other text communication, screenshots, and in some cases, combined browsing history), **you must provide a prominent link from your app integration to an applicable privacy policy, and such privacy policy must comply with all applicable laws, regulations and policy requirements. This policy should cover what data you are collecting or transmitting, what you will be doing with that data, and (if applicable) who you'll be sharing it with.** 

Data can be tampered with during transmission. Protocols exist that provide encryption to address problems of misuse and tampering. In this regard, bots should communicate only over encrypted channels. This makes it hard for anyone other than the receiver and sender from seeing any part of the message or transaction.
## **Recommended Documents**

- [Bot Service Encryption](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-encryption?view=azure-bot-service-4.0)
- [Bot Framework security guidelines](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-security-guidelines?view=azure-bot-service-4.0#protocols-and-encryption.)
- [Bot review guidelines](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-review-guidelines?view=azure-bot-service-4.0)
- [Security and Privacy](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-resources-faq-security?view=azure-bot-service-4.0)

## Additional assistance:

- https://stackoverflow.com/questions/tagged/botframework
- https://blog.botframework.com/


