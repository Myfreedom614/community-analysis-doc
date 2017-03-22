## Troubleshooting Community Analysis Extension (Easy Analysis Extension)
#### Greasy Fork: https://greasyfork.org/en/scripts/14666-easy-analysis-extension

- **How to upgrade the CA extension**

    - For IE, the BHO will always use the latest user script
    - For other browsers, Chrome as example, please *trigger update* in **Tampermonkey**
    ![alt text][tampermonkey-update]

- **CA iframe page always need to sign in (repeatedly login)**

    Basically this is caused by browser cache
    - **IE**
    
        Press **Ctrl+Alt+Delete**

        ![alt text][ie-cache-clear]

        Close all IE windows and restart IE

    - **Chrome**
    
        Press **Ctrl+Shirt+Delete**

        ![alt text][chrome-cache-clear]

        Close all Chrome windows and restart Chrome

- **I cannot use the CA extension in IE InPrivate mode**

    - Open IE.
    - Click on Tools > Internet Options > Privacy tab
    - In the "InPrivate" section, clear the " Disable toolbars and extensions when InPrivate Browsing starts" checkbox.
    ![alt text][inprivate-bho-setting]
    - Validate with the OK button.
    - Close all IE windows and start IE in InPrivate mode

[inprivate-bho-setting]: ../img/inprivate-bho-setting.jpg "InPrivate BHO Setting"
[tampermonkey-update]: ../img/tampermonkey-update.png "Update CA Add-in in Tampermonkey"
[ie-cache-clear]: ../img/ie-cache-clear.png "Clear IE cache"
[chrome-cache-clear]: ../img/chrome-cache-clear.jpg "Clear Chrome cache"
