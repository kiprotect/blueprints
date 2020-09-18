# Pseudonymization Demo

This demo shows how to pseudonymize structured data with Kodex.
To pseudonymize the example data in `input.json`, simply run

    kodex run pseudonymize

To depseudonymize it again, simply run

    kodex run depseudonymize

# Pseudonymization with custom key

The two examples above will use the parameter management of Kodex to
store pseudonymization keys. If you want to specify the keys yourself you
can do so as well:

    kodex run pseudonymize-with-key

and

    kodex run depseudonymize-with-key

Kodex will ask you to enter a key and use that key to pseudonymize
and depseudonymize the items, without reyling on the parameter management.
