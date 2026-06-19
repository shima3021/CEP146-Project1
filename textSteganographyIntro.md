# What is Steganography?

Steganography refers to the practice of hiding information (e.g., a message) inside another information object (e.g., a text document, an image, or an audio/video file) which also called a carrier.

# What is Text Steganography?

Text Steganography is one of the ancient and common use of steganography where the carrier is a text document/object. Although, it seems simple at the beginning, it can be quite challenging for a person or an auditor to find if a text document or object has been a carrier. Imagine one would choose to hide a message "This book is ancient" inside a book of 25 pages with each page containing 100 words. Obviously, in 2500 words, there are many opportunities to hide the message.

Text Steganography also does not require that the secret message to be always a text. For instance, the secret message can be an audio file. However, since the carrier is a text document/object, one would first convert the audio file into text to be able to use a text carrier. 
In this report, we only focus on hiding text in text carrier methods.

# Discovering the secret message?

Once a carrier becomes a stegano (contain the secret message), the receiver of the message must know where to look for the embedded message inside the stegano to quickly discover the message. Common methods for communicating the stegano map/key are:

 - Prearrangement between the sender and the receiver of the stegano on how to look up the secret message 
 - The sender will tell the receiver how to discover the message (e.g., telling them in a separate letter).
 - Using a a common software and identical configurations by the sender and the receiver of the stegano.

More information on the Text Steganoraphy techniques can be found in textSteganographyMethods file at: https://github.com/shima3021/CEP146-Project1/blob/textSteganography/textSteganographyMethods.md
