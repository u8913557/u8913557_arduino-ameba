

This is personal verson to study Arduino Ameba from official 1.1.3


1. Arduino IDE 1.6.5 support third party hardware by providing hardware configuration.
You need add Ameba's configuration in "File" -> "Preferences".
And fill below URL in "Additional Boards Manager URLs:"

	https://github.com/u8913557/u8913557_arduino-ameba/raw/master/release/package_realtek.com_ameba_index.json

We also suggest to enable "Show verbose output" options on "compilation" and "upload" in Preference.

2. Open "Device Manager" in "Tolls" -> "Board" -> "Board Manager".
Wait for IDE update core configuration. Schroll down the menu, you will see Realtek Ameba in the list.
Press "Install" at the right side.

3. Select Ameba in "Tools" -> "Board" -> "Ameba Arduino".
Now you are able to develop Arduino code and upload image onto Ameba.

