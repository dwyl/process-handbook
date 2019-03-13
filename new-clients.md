# New client setup

So you've won some work from a new client - good for you!

This is how we set new clients up on all of our various systems.

* [ ] Create and sign contracts
  * Template contract is saved in the `Clients` folder. Unless there are non-standard terms, only pages 1, 9, and 10 should change
* [ ] Book initial workshop
  * This will be the responsibility of the client contact
  * Bear in mind that our standard terms are for the first invoice to be paid at once, so that can be raised and sent out immediately
* [ ] Set client details up on Xero for invoicing
  * `Xero > Contacts > Customers > Add customer`
  * You'll need their accounts contact email address at least
  * Other contacts can be copied in or not as they prefer
  * (You should also ask what information they need for their system, if they haven't already requested it.)
* [ ] Set up Google Drive
  * (This is still a WIP as it's not currently possible to duplicate entire folders on Drive)
  * Set up a folder to match the `.template` structure (hopefully we'll find a way to just dupe it)
    * Be careful to keep the `permissions` the same
  * Save all documents with financial/sensitive information in the `.private` folder
    * Proposal
    * Contract
    * Budget planner
* [ ] Set up github
  * Create a client organisation
  * Create project repo
    * Initialise with `readme`
    * Call it something _sensible_
    * Copy across our labels using [labelsync](https://label-sync.herokuapp.com/) as per https://github.com/dwyl/labels
  * Give permission to all team members who'll be working on the project
    * Either at the `org` level, if we have access to that, or at the repo level if that's all we have access to
* [ ] Set up gitter
  * Decide whether this will be a `dwyl` channel or coming from the client repo
