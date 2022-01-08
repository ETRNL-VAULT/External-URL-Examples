
# Setup

## Host these files
Make sure the **index.html**, **main.css**, and **script.js** are all hosted within the same folder on your webserver. For this example, we will host them on the **/verify** page.

## Create a secure page that uses the external URL
Create a secure page in the ETRNL VAULT. Then click on the "**advanced**" dropdown on the right and click the "**enable custom URL**" option.

If you host these files at the /verify page as mentioned above, then the external URL format should look like this:

**`https://yoursitehere.com/?tagId=%tagId%&eCode=%eCode%&enc=%enc%&cmac=%cmac%`**

*"yoursitehere.com" would be replaced with your website.*

## Program tags to use this page
Now all you need to do is program a tag to use this page that your created and you're all done!
