# message_app_hibernate_and_message_integrity
A basic messaging application that uses Hibernate to manage a MySQL database and implements public-private key pairs to verify user signatures on messages and ensure their integrity.
Also, it counts with a slightly improved interface than the previous version in the repository "basic_message_app_hibernate_and_encrypted_messages".

To run the aplication, an empty database must be created for hibernate to build and manage it. The name of the database is visible on the persitence.xml file, found in the resources folder.
In that same file, a user and password with enought permits must be set, so hibernate is able to act throught it. 

Then, class Main must be executed.
