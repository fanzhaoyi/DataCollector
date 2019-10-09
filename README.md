# Data Collector

## Introduction
The main purpose of this brief note is to provide information on the operation of the experimental Chrome browser extension which I 
have developed to assist my research. This research is aimed at understanding the degree to which a user can be identiﬁed by a visited 
website purely from keyboard/mouse interactions with a browser; future research may also look at ways in which this potential privacy 
threat can be mitigated. An additional purpose of this note is to enable me to obtain informed consent for use of the extension and to 
store and process the data it generates. The experimental platform contains two parts: a Chrome extension which needs to be installed 
on the participant’s computer, and a remote server which is used for data storage.

## Operation
The extension works only when the user is signed in and when the user is interacting with a web page via Chrome. If the user is signed out,
the browser is minimized, or the user is not currently interacting with the browser (i.e. the browser is in the background and the user is
interacting with another program on the computer), the extension does not gather any data.

## Data gathering
When the extension is working, it records every keystroke and mouse movement when using Chrome. For example, when a user types in a 
sentence, every character in this sentence and the corresponding timing information are captured. The coordinates of a user’s mouse 
pointer and mouse button clicks are also captured. These data are sent to a remote server for further analysis.

## Data storage
All collected data is stored in a secured cloud server database. The data will only be used to conduct the research outlined in this 
document. The captured data will not be released to any other party without the explicit additional consent of the party whose computer 
generated it. The author will not look at the data in detail, which means the author cannot learn any sensitive content from the data 
that has been gathered. The data will only be processed automatically using biometric identiﬁcation algorithms.

## Additional remarks
The following additional points should be noted. 

• After installation of the extension, the user is required to register a user name and password. It is recommended to avoid re-use of a name/password combination that has been employed elsewhere. 

• As the extension can record every keystroke and mouse movement, some personal data might be gathered, including passwords for other websites and other sensitive data. 

Thus if a user has any concerns that the data they are typing is possibly sensitive, the user is recommended to log out of the extension 
and log in again when the sensitive interactions have been completed.
