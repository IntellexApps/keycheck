# keycheck


Introduction
--------------------

Simplifies checking any APK againsy keystore file, protected with its
passphrase, alias and alias password.

This is very usefull to validate that your APK is properly signed and valid
before uploading it to the Google Play Store.


Requirements
--------------------

* Any linux distribution.
* Installed and available keytool (commes with android SDK)
* You must also know
	* Passphrase of the key
	* Alias and its password


Usage
--------------------

#### With root access
1. Download the script to your /usr/bin folder
2. Type `chmod +x /usr/bin/keycheck`
3. Type `keycheck <path_to_the_apk> <path_to_the_keystore>`
4. When promprted, supply with passphrase, alias and its password


#### Without root access
1. Download the script to your system
2. Type `chmod +x /path/to/keycheck`
3. Type `/path/to/keycheck <path_to_the_apk> <path_to_the_keystore>`
4. When promprted, supply with passphrase, alias and its password



Credits
--------------------
Script has been written by the [Intellex](http://intellex.rs/en) team.
