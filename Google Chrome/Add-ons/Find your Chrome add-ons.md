<img width="943" height="503" alt="image" src="https://github.com/user-attachments/assets/bacbbc37-79b6-492a-8827-ed26990ccc65" /># Find your Chrome add-ons
## Part 1 -- Install Chrome add-ons
You have to install Chrome add-ons on Google Web Store.

## Part 2 -- Get ID of your add-ons
After installing,

Step 1:

Open Google Chrome.

Step 2:

type [`chrome://extensions/`](chrome://extensions/) on url bar.

<img width="1912" height="1007" alt="image" src="https://github.com/user-attachments/assets/78f0ff58-26ca-448a-ab12-86e55cef2e3b" />

It will redirect to the main page of Google Web Store.

Step 3:

Next, click `My extensions` to ONLY search installed add-ons.

<img width="1912" height="1007" alt="image" src="https://github.com/user-attachments/assets/5ee94b84-a36c-4815-9c7e-c7fa431a858a" />

Step 4:

Then find your add-ons.

<img width="1912" height="1007" alt="image" src="https://github.com/user-attachments/assets/ceb98564-b6e1-4023-8ffa-8ce0b68bd11e" />

Step 5:

In the card (contains your add-ons info), click `Details` button

<img width="1912" height="1007" alt="image" src="https://github.com/user-attachments/assets/3cbfd790-d699-4f29-a06d-1cc9631ff0cc" />

Step 6:

Then you will see the ID field in Detail Page. Don't close the Detail Page, you will need to use it later.

<img width="1898" height="1011" alt="image" src="https://github.com/user-attachments/assets/4ad4b682-218e-4453-a037-0e68d840f388" />

In this example, the ID of Chrome add-ons `Bulk Delete For Gemini` for me is `bdbdcppgiiidaolmadifdlceedoojpfh`

Step 7:

Copy the ID and paste into other place, you will use the ID later. 

## Part 3 -- Get root directory of your Chrome add-ons
Step 1:

Go to the Detail Page of your Chrome add-ons

<img width="949" height="506" alt="image" src="https://github.com/user-attachments/assets/40a1dc8e-b1a3-4696-826a-dcd0fedbcd23" />

Step 2:

On this Detail Page, type [`chrome://version/`](chrome://version/) and click `enter` to redirect the version page, and look at Chrome version.

<img width="1885" height="1005" alt="image" src="https://github.com/user-attachments/assets/443ff916-d3ac-4aeb-94c9-9fc2d6fc46b5" />

Step 3:

Find `Profile Path`, it's the root directory containing all installed Chrome add-ons with your current working Google Account. 

<img width="1875" height="1005" alt="image" src="https://github.com/user-attachments/assets/99b9e522-8746-4f58-84e6-ee7221f2fc34" />

## Part 4 -- Find specific add-ons
Step 1:

Open file explorer.

Step 2:

Navigate to your `<Profile-Path>`.

Replace `<Profile-Path>` to the profile path you find in Part 3. 

Step 3:

Then find a child named `<Chrome-Addons-ID>`.

Replace `<Chrome-Addons-ID>` to the ID of your installed Chrome add-ons you find in Step 2.

That's it. That's the root directory of your installed Chrome add-ons.
