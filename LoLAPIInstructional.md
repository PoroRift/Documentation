## Playing with LoL API before System Design
These instructions are technically optional to test LoL API but better experience, you could just paste the requests into your address bar.

---

**1. Install Postman if you don't have it already:** Instructions to install and how to get started and stuff is [here](https://www.getpostman.com/docs/v6/postman/launching_postman/installation_and_updates) or if you're more of a TLDR person just click [here.](https://www.getpostman.com/apps)

**2. Download Postman Collection from our beautiful repository, it is in [ProroRift/docs-about](https://github.com/PoroRift/docs-about).** 

**3. Open up Postman, exit out of that introductory popup, and click on `File` > `Import...`.**

**4. You drag and drop or or hit `Choose Files` to upload the Postman Collection file you downloaded from O.B.R. (Our Beatiful Repository).**

**5. Click `Collections` tab on the left next to the `History` tab.**

~~**6. Put down the API key in Environment Variable:** Open up the Collection by clicking the small left arrow. There should be a few requests (or just one) click on one you're interested in and it should open up into the main boxes. Click on `No Environment` dropdown above the blue `Send` button and select `PORORIFT`, click the eye icon next to that dropdown and click on the `Edit` button adjacent to `PORORIFT`. You should see a checked row labeled `API_KEY`. Under `CURRENT VALUE` grab the API key from our chat (or generate your own [here (requires LoL account)](https://developer.riotgames.com/)) and paste it into that column. Hit `Update`. You might also need to add other variables to this place depending on the variables the request will use.~~
**6. WE CAN SHARE ENVIRONMENTS!** Create an account with Postman, sign in and let me know your email. I will share the key/environment with you and you will not need to worry about this step. You may still need to go to the dropdown to change to this environment however.

> **NOTE:** API key expires every 24-hours so if it's expired request for me to generate a new one for you or make an account to test your own and place it into the same place mentioned above.

**7. PLAY AROUND WITH THE COLLECTIONS OR MAKE YOUR OWN!** Hit the blue `Send` button! You can also play with the parameters (as you did in step 6), i.e. click on `No Environment` dropdown above the blue `Send` button and select `PORORIFT`, click the eye icon next to that dropdown and click on the `Edit` button adjacent to `PORORIFT`. Use your common sense to change the values and hit `Update`!

Below are a list of resources to help you! If you need help please don't heasitate to ask in **Messenger group chat** [BFS] or ask **anyone** [DFS] _(ask recursively until someone who knows is asked. Please avoid cycles by keeping track of visited team members. ;) one of the algorithms is better than the other)_
- [LoL API Methods/Documentation](https://developer.riotgames.com/api-methods/)
- [Postman Docs!](https://learning.getpostman.com/docs/postman/launching_postman/installation_and_updates/)

_Please keep in mind that each generated key is limited to: `20 requests every 1 seconds` and `100 requests every 2 minutes`. This won't be an issue for us most likely..._

## To Contribute to "Recipies"
---
**1. Make sure you have the repository checked-out.**

**2. You should see `PORORIFT LoL API Playground` in your Collections, hover over it and click on the ellipsis (`•••`) > `Export` > _(default selections are fine)_ `Export`.**

**3. Find the folder where the original recipies file is and overwrite it.**

> **NOTE:** before making any git commits please make sure you are not exporting the API_KEY variable as well. This can be done by cutting it out of the Environment Variables before exporting Collection. (There could be an easier way... let me know)

**4. Push the changes to a branch and make a pull request! _(Request assistance if needed.)_**
