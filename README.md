# PHP_Eventive

The login page (verify_login) verifies the Password Hash (not the password itself).
In case one wishes to add a new user password or update a password -> make sure to create the hash of the password via https://www.md5hashgenerator.com/

For example: You wish to update password, choose the password string example: abc123 and create its hash via https://www.md5hashgenerator.com/

Your Hash: e99a18c428cb38d5f260853678922e03 (save this in database).
Your String: abc123 
