# FRPC

## What version should i use on Mac?

-   frp_x.xx.x_darwin_amd64.tar.gz

## How should I run frpc on Mac?

-   Open a terminal
-   Navigate to frpc directory
-   Type `./frpc -c frpc.ini`

## Why does Mac say that `frpc` is from an Unidentified Developer?

This is because `frpc` is not signed for Mac. To allow it to run follow these steps:

-   Navigate to `frpc` folder in Finder
-   Right click on the `frpc` executable while holding **Ctrl**
-   Select **Open**

Mac will give you information about the risks of skipping the system security. Please read it carefully and click **Open** in the popup if you agree.

## What are the risks of giving permissions to `frpc` even if it is from an Unidentified Developer?

`frpc` executable is not signed by Apple. It means that the OS cannot know what kind of code it is going to execute. By accepting to skip the system security you are telling the OS that you trust the app. Please do so at your own responsibility. To avoid any issues make sure you have downloaded `frpc` from the official repository at [https://github.com/fatedier/frp/releases](https://github.com/fatedier/frp/releases).
