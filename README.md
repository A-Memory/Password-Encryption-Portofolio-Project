Description:

This program provides a unique method for encrypting and decrypting passwords. Instead of traditional cryptographic methods, this program uses a vast multi-dimensional array (referred to as the "data_realm") to scatter the characters of a user's password randomly, ensuring complexity in the encryption process.
Features:

    Cross-Platform Compatibility: The program offers a clear_screen() function that works on both Windows and POSIX systems.

    Complex Data Realm Generation: The create_data_realm() method creates a large multi-dimensional array filled with random characters to serve as the realm in which password characters are placed.

    Password Encryption: The insert_secret_key() method encrypts the user's password by placing its characters at random locations within the data realm.

    Password Decryption: The decrypter() method allows for the decryption of the encrypted password by searching for the characters within the data realm.
