 **Marvel API Character Retrieval**
 
This Python script retrieves random Marvel characters using the Marvel API and saves their information to a CSV file. The script generates a list of random letters and uses them to query the Marvel API for characters whose names start with those letters. For each character, the script retrieves their name, ID, the total number of events, series, and comics they have been featured in.

To use the script, you will need to provide your own Marvel API credentials, which consist of a public key and a private key. Once you have obtained your credentials, you can modify the script to include them and run the code to retrieve the characters.

The CSV file generated by the script will contain columns for each of the character's attributes, making it easy to view and analyze the data. The file can be opened in any spreadsheet software, such as Microsoft Excel or Google Sheets.

**Dependencies**

The script requires the following dependencies:

* time
* hashlib
* requests
* random
* csv
