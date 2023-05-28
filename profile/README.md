# SimpliFunds
## Title
A fully fledged native IOS application designed to showcase a Personal Finance Manager.
The app is called "SimpliFunds" and is a simple app for managing finances accross different bank accounts.

## Description
### What is it
`SimpliFunds` is a finance manager which has been made to simplify users accounts and to create rich insights based off their past transactions. This is a content rich app which I have built to demonstrate my take on a Personal Finance Manager

It is a fully fledged native Swift app complete with an MVVM architecture, database connections, faas[^1] calls, and external API calls.
Also, this org contains GCP Functions created with typescript to handle bankend services.

### What technologies does it use
`SimpliFunds` predominantly relies on GCP[^2] and Basiq to handle API calls and backend services.

The app & corresponding functions are connected to a number of GCP services:
- Identity
- Firestore
- Functions v2

It mostly connects to these API's through GCP Firebase which provides an easy method to tie it all together with the application.

This app has been developed to utilise the CDR's Open Banking standard through Basiq and their Open Banking platform. This means that the collected data from all participating banks is standardised which enables users to add all of their different banks/bank accounts.

### Dependencies
#### Swift
- firebase-ios-sdk
- SDWebImageSVGCoder
- SDWebImageSwiftUI
#### Typescript
In Progress

## How to install
In Progress

## How to use
In Progress

## License
Each repo is licensed under the GNU General Public License V3, the license conditions can be found in the LICENSE md file in each respective repo.

[^1]: Functions As A Service
[^2]: Google Cloud Platform
