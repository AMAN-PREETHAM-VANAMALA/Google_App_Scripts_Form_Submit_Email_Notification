# Google_App_Scripts_Form_Submit_Email_Notification

[Here](https://docs.google.com/forms/d/e/1FAIpQLSd7YhkGXaDeCeE2IPLAeknvpwm5bd0NF6YNlO_Xl3ke3) is the link for sample form. An 'On Submit' trigger has been set which on submitting will send an email notification containing the responses in a formatted manner. The AppScript has a function which on form submission stores the response, formats it and sends an email containing the response received. 

### Notes:
- Having a name and email address queries in the form is mandatory.
- The AppScript is generalised for most of the form cases except that the name should be first response and email address should be third response.
- AppScript can be modified to have the name and email address indices appropriately if the form needs to be modified.
- While copying the AppScript code to some other form, the form ID should be edited accordingly.
