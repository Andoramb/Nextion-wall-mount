Here's the current HMI resource file for Nextion Editor (or in case of TJC-> USART HMI editor)

I don't expect it to load correctly if any image is modified and here's why:
Pictures are loaded into the elements based on their number (in the order they have been added...)
For ex. the weather element loads the picture based on a preconfigured number.

If a picture gets deleted, the whole array needs to be shifted by 1... tricky, it is what it is. Handle with care!
