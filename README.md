# Draft UI schematic

![ui_scheme](https://github.com/MoonSHRD/Interface_story/blob/master/assets/draft_ui_scheme.jpg "ui_scheme")

yellow - first release

green - second release

purple - third release

## Windows description

-  topic / chat list - window with list of available dialogs

- dialog window - window which contains dialog itself (read message frame, input frame)

- personal info window - window, which contain personal information of a user.

Personal info contain user name, image, uid,  topic list. Topic list is a list of user "interests"

- input topic window - is a window for input and edit user topic list

- dialog info & search - window, where user can observe dialog info and search (filter) messages

- contacts - window, where user can observe his contact list

- matched - window, where user can observe contacts, which has been auto-match with his profile 

Matching mechanism working like this:

1.user input his topics in 'input topics' window

2.each time he discover a new peer in any local network with similar topics - he request his id, which will be added to a 'matched' window. You may think about it like e-id card, which collect every useful contacts from enviroment, basing on your interests

- places  - window, where user can observe places (nearby network in first releases)

In first releases it could be just list of available wi-fi network. If our app know the password from any of it - it will mark green color.

- place info - window where user can observe info about specifiec location

If user know the password from this network - he could add this password to place card and add some info about it. It is also allow him to 'pin' some main local chat and being administrator for it.


