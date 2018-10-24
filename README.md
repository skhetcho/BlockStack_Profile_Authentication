# BlockStack_Profile_Authentication
[![Linkedin](https://img.shields.io/badge/Connect-LinkedIn-0E76A8.svg)](https://www.linkedin.com/in/sourenkhetcho/)

This BlockStack User/Profile Authentication program is a simple demonstration of using "BlockStack Auth". Find out more about BlockStack on [BlockStack Git Repository](https://github.com/blockstack).

When you run this program you can access a login page from your localhost. However, you will need a blockstack id in order to login. After you login, you will be presented with a box to update your status on the account. When submitting the status, you have created you first putFile request to the BlockStack GAIA storage which is a decentralized encrypted storage. If you want to see how the data fetches when other users try to visit your profile just visit 

```
localhost:YOUR_PORT/YOUR_USERNAME.id.blockstack
```
You will notice that you can't post or delete the status anymore. Because it is simply isn't allowed.

Enjoy !!!



# Installation
```
git clone
cd BlockStack_Profile_Authentication
npm install
npm start
```
