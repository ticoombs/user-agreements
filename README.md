# user-agreements
A repository to highlight and provide transparency for user agreement changes, for all software and licenses

## How-to Contribute
When updating any software to a new version which comes with an updated user agreement or license change, before you immediatly hit accept. 
 - Copy and save it to a file. 
 - Check if that program already exists in the repo (And for the version you are updating to)
  - Have a look at the differences between your previously accepted licence and the latest version.
 - Create a pull-request with the latest agreement if you happen to be the first to update. 
 - Have a warm fuzzy feeling.

 
## Current Repo Structure
While the repo is in its alpha stages the current structure will be as follows. If you dissagree or would like to propose we change our arrangement of licenses please open an Issue.

 - \<repo\>/\<program\>\-\<type\>.txt
 - Commit Message: <Program> <Version> 

Example:
  user-agreements/firefox-user.txt
  user-agreements/firefox-privacy.txt (Optional: if a program has a privacy policy)
  user-agreements/chromebrowser-user.txt
  user-agreements/chromebrowser-privacy.txt
  user-agreements/license-gpl.txt
  user-agreements/license-mit.txt
  user-agreements/license-apache.txt


## (Possible) Future Repo Structure?
 - \<program\>
  - user-agreement
  - privacy
