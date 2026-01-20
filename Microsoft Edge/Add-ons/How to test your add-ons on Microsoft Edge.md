# How to test your add-ons on Microsoft Edge
## Prequisite
Your add-ons (written in JS) must contains

  + configuration file (inlcluding `manifest.json`)
  + JS script
  + API Key

## Part 1 -- Get add-ons on Chrome Web store
The fastest way to get JS script is to install Chrome addons you want on Google Web store and get its location. 

so that you don't have to develop it by yourself (Don't CRY principle)

See [my notes](https://github.com/40843245/Webbrowser/blob/main/Google%20Chrome/Add-ons/Find%20your%20Chrome%20add-ons.md) for the instructions

## Part 2 -- Specify the location of add-ons
> [!IMPORTANT]
> To keep the Chrome add-ons clean and uncorrepted so that can be used later,
>
> Please always copy the Chrome add-ons into other place then modify it.

Step 1:

Copy the add-ons (for example, `bdbdcppgiiidaolmadifdlceedoojpfh` folder -- Chrome add-ons named `Bulk Delete for Gemini`) where Chrome loading from  to other place (for example, `C:\Users\userJay30\AppData\Local\Microsoft\Edge\workspace\Extensions`). You can find it on [my notes](https://github.com/40843245/Webbrowser/blob/main/Google%20Chrome/Add-ons/Find%20your%20Chrome%20add-ons.md)

Step 2:

Open Microsoft Edge.

Step 3:

Type [edge://extensions](edge://extensions/) in url search bar, it will redirect to the main page of Installed Edge add-ons

<img width="1156" height="979" alt="image" src="https://github.com/user-attachments/assets/c1733998-6df4-4161-ba59-677f41007d32" />

Step 4:

Enable `Developer mode`

Also, enable `Allow extensions from other stores` to allow Edge to load add-ons from other source.

<img width="1156" height="979" alt="image" src="https://github.com/user-attachments/assets/b6ae8a0d-895a-43fe-bffe-599cd324b7f4" />

Step 5:

After that, click `Load unpacked` button.

<img width="1156" height="979" alt="image" src="https://github.com/user-attachments/assets/550ae078-1cf8-4b85-b72c-8ba5e5646a4e" />

Then open the folder containing directly children configuration files (here, open `C:\Users\userJay30\AppData\Local\Microsoft\Edge\workspace\Extensions\bdbdcppgiiidaolmadifdlceedoojpfh\1.0.5_0` folder)

And you will see a card with add-ons name you loaded it jsut now in `Extensions`->`My extensions`->`From other sources` section in this page immediately after Edge loads the add-ons successfully. 

<img width="1156" height="979" alt="image" src="https://github.com/user-attachments/assets/f0796133-da04-4c59-8536-89779ccd00a8" />

## Part 3 -- Test it
Congratulation, you can test it forever if you didn't move the configuration files (including `manifest.json)`. 

Once you open the Microsoft Edge webbrowser, you ONLY need to ensure Edge have reloaded the add-ons.

You can turn on the toggle on the card containing the info of the add-ons on [Installed extension page](edge://extensions/)

Then click `Reload` link on the card to force Edge try to reload the add-ons.

<img width="1156" height="979" alt="image" src="https://github.com/user-attachments/assets/2e09f289-527a-4e3d-b8e9-62b9da2856c1" />
