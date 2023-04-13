Weingart, Scott. 2019. 'The Route of a Text Message, a Love Story' _Motherboard_https://www.vice.com/en/article/kzdn8n/the-route-of-a-text-message-a-love-story

Summary

- In 1984, German telephone engineer Friedhelm Hillebrand set the character limit of text messages in stone at 160 characters. Androids and iPhones weave long messages together behind the scenes so we can't tell they were split apart for delivery.
- Hillebrand and his team wanted to relay messages over a secondary channel that phones were already using to exchange basic information with their local stations, but the Signalling System no. 7 (SS7) protocol had a hard limit of 279 bytes of information.
- Getting messages across the SS7 protocol isn't as simple as sending 2,232 bytes at 8 bits each. Part of the signal needs to conatin the sender and recievers phone number.
- Hillebrand and his team crammed all the contextual bits into a 279-byte signal, but were left with only enough space for 140 characters at 1 byte (8 bits) a piece.
- To get an alphabet down to 7 bits, you need to remove some possible characters, but assuming people will never use those symbols in text messages, you can get 160 characters into a 140-byte space.
- The message appears on her phone as 10 bytes of 8-bit hex codes, which are converted to 7-bit hex codes by borrowing the remaining bit at the end of every byte.
- When the phone senses voltage fluctuations over the 'send' button, it sends the encoded message to the SIM card, and in the process wraps it in all sorts of useful contextual data.
- The first ten bytes of a text message are reserved for the telephone number of the SMS service center, which routes the text to the mobile station nearest to the recipient's phone.
- The message reference (MR) is a number between 1 and 255 that lets the phone and the carrier know which text message it's dealing with.
- The next twelve bytes are reserved for the recipient's phone number, called the destination address (DA). This number is encoded using reverse nibble notation.
- The Data Coding Scheme byte tells the carrier and the receiving phone which character encoding scheme was used. 
- The validity period space can take up to seven bytes, and sends us into another aspect of how text messages actually work. If the SMSC can't find my phone, it will bounce around in its system until the moment my phone reconnects.
- Because there's often a lot of empty space in an SMS, a few bits are dedicated to letting the phone and carrier know exactly which bytes are unused. The user data length (UDL) byte solves this problem.
- Because each character is 7 bits rather than 8 bits, we can shave an extra byte off in the translation. The message itself, or the UD (User Data), can take up to 140 bytes, though "I love you" will pack into a measly 9 bytes.
- The SMS must now travel from the SIM card to the nearest base station, where it is converted to an analog radio signal and sent out into the thor at a frequency of 800 to 2000 megahertz.
- Antennas should be no smaller than half the size of the radio waves they're dealing with, but mobile phones never seem to get much smaller.
- Due to competing signals, each base transceiver station can't handle more than 200 active users at a time.
- The SMS has to go from the SMSC to a global switchboard and then bounce around the world before reaching my phone.
- There are about 330,000 pixels crammed inside each of my phone's 13 square inches, or 4 million in all. Each pixel is actually three points of light, with a different organic molecule for blue, red, and green light. These shine different colors when electrified.
- 