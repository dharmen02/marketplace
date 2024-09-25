Simple Marketplace Sample Application for Azure Blockchain Workbench
====================================================================

Overview 
---------

The Simple Marketplace application expresses a workflow for a simple transaction
between an owner and a buyer in a marketplace.  The state transition diagram
below shows the interactions among the states in this workflow. 

<br />

Application Roles 
------------------
| Name                   | Description                                       |
|------------------------|---------------------------------------------------|
|Owner |A person who wants to sell on the marketplace. |
|Buyer |A person who wants to buy from the marketplace. |

<br />

States 
-------

| Name                   | Description                                       |
|------------------------|---------------------------------------------------|
|ItemAvailable |Indicates that an owner has made the item they want to sell available in the marketplace.
|OfferPlaced |Indicates that a seller has made an offer to buy the item listed by an owner.
|Accepted |Indicates that the owner has accepted the buyer's offer for the item.

<br />

Workflow Details
----------------



