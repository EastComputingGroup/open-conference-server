# Open Conference Server

The Open Conference server creates a place for friends, communities, or companies to communicate via text, audio, or video.

_This page mentions features that aren't yet part of the Open Conference Software Suite. For a full list of available features, please see the "Current Features" section below._

A single Open Conference server usually contains members of a singe friend group, community, or organization. Companies will likely want to stand up multiple Open Conference servers and utilize enterprise features from the Open Conference Management Server (OCMS) to delegate user connectivity and pre-authorized connections to managed Open Conference servers.

An Open Conference server is a collection of chat rooms, where clients can communicate via text, audio, or video depending on the rooms configuration. All data is stored on your hardware - meaning no data is shared publicly unless you want it to.

### User Accounts

Open Conference has three main ways for user authentication, each offering different levels of security. They are outlined below.

1. Anonymous Access (Least Secure, Trust Validation) - Users do not require any form of validation for who they are to connect to your server. While they will need to know the password, access code, obtain and access code, or have a one-time access link to connect initially, there is no guarantee that they are who they say they are on subsequent connections. This form of validation is best for groups who don't care about server permissions.
2. Public Open Conference Management Server (Default, Full Validation) - The Open Conference team hosts a public OCMS for anyone to create an account on. Open Conference Servers can use (and do by default) this public OCMS as a validation service to verify the client is who they say they are. Clients send an encrypted passphrase to the Open Conference server they are attempting to connect to along with their username, which the Open Conference server then forwards along to any listed OCMS. If the credentials match, the associated OCMS responds back with a successful validation request informating the Open Conference server that the user is who they say they are. More information on the public OCMS can be found below.
3. Private Open Conference Management Server (Self-Hosted, Full Validation) - For those who want total control over who can access their server and the associated accounts, you can stand up and host your own OCMS. This is the best options for enterprise solutions.

The Open Conference Management Server can use a variety of databases for user credentials as well as directory services such as Active Directory or LDAP.

## Current Features
None! The Open Conference project is brand-spanking new and has nothing to show for yet - please check back later!
