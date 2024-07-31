Key Concepts 

Encryption: Shifts each letter in the plaintext by the specified number of positions to produce ciphertext.

Decryption: Reverses the encryption process by shifting letters back by the specified number of positions.

1. User Interaction
Prompt the User:Ask if the user wants to encrypt or decrypt a message.If the input is invalid, prompt the user again.

2. Encrypting the MessageInput:Get the message and shift value from the user.
* Uppercase Letter:Convert character to its position in the alphabet (0-25).
Apply the shift and wrap around if needed using modulo 26.
Convert the shifted position back to a character.
* Lowercase Letter:Similar to uppercase but with ASCII values for lowercase letters.
* Non-alphabetic Character:Directly add to the result without any changes.
* Output:Display the encrypted message

3. Decrypting the MessageInput:Get the message and shift value from the user. * Process:To decrypt, shift in the opposite direction. This is achieved by calling the encryption function with a negative shift value.
* Output:Display the decrypted message.

4. Repeat or ExitAsk User:After displaying the result, ask if the user wants to perform another encryption or decryption.
* Exit Loop:If the user chooses not to continue, exit the program.
 
