# keyword-gen
Crowd-sourced keyword generating tool (helped by thesaurus)

The idea for this system is as below:
User types a word, and a list of suggestions pop up below in another box. When user selects words from the pop-up list, the list gets enriched with more relevant words and drops less relevant words. User can control the amount of keywords generated, but upto a limit. If User types additional words the new words get associated with the rest of the words typed or selected by user, or existing association might get strengthened
When the user is done, he is able to copy the keyword list into the system buffer (clipboard) at the click of a button.
Incentive to log in:
- Facebook/twitter handles would work
- keyword history will be accessible
- twitter hashtag score will be provided (later feature, tbd if possible)
- - the score will be based on the collective popularity of the keywords on twitter, and divided by the number of keywords. This (hopefully) will make the user use keywords more relevant and less numerous

Business model
- ad-servers can latch on to send users ads based on the keywords they used
- non-disruptive ads would be displayed on the web-site itself based on keywords being typed. 

This will be powered by a REST api so web-sites like youtube can avail the service in their own environment. (Will be fee-based)
