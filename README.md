# supply_chain_management_project

## SPS Problem Statement

Suppose you are working as a business analyst at Smart Consultants Pvt. Ltd. You work in the Data Science department, and there are other operations departments as well, such as Product Management, Supply Chain Management, Marketing, in the organisation. Your team receives a report from one of your clients seeking the team’s help with the problem that it is facing. The client runs an open-pit mine in the state and looks after the production of the desired composition of the ores extracted from the mine.

As a business analyst, your first task would be to understand the problem faced by the client. And to do that, you would want to understand the operational entities that are involved in the open-pit mine.

You realise that the following operational entities are associated with your client’s open-pit mine.

Digger: A digger is an operational tool that extracts the right proportion of the desired raw ore from holes that are blasted over a particular part of an open-pit mine.

Digger-to-Crusher Trucks: These are the empty trucks that are present at every digger. They get loaded with the raw ore that is extracted by the digger and make their way to the crusher as soon as they are loaded to their full capacity.

Crusher: The loaded trucks that have arrived all the way from the digger dump all the raw ore into the crusher, which is another operational tool present at multiple locations on an open-pit mine. The crusher crushes/processes the desired quality of ore composition required by the customers/clients of the open-pit mine.

Crusher-to-Digger Trucks: After dumping the raw ore into their allocated crushers, the digger-to-crusher trucks, which are now empty again, head back to the diggers to get loaded with raw ore.

Logistics Manager: The logistics manager acts as a medium between the customer and the open-pit mine. Customers reach out to the logistics manager before placing an order of a desired quantity and composition of a required ore. The final processed ore is also delivered to the customer via the logistics manager.

Customer: This is the end-user who had submitted the requirements with the logistics manager for the desired composition of ore to be processed.


## Truck Assignment Problem

Suppose you are still working at Smart Consultants Pvt Ltd. and one of your clients that handles an open-pit mine comes to you saying that they are facing a problem of low production at the mine. This is an indication of the low efficiency of the mine operations and is also causing higher management to increase the cost of production.

Although the mine is in continuous operation, it is taking longer to serve the requirements of the customers. This is, in turn, causing distress among the customers, which is, in a way, reducing your market value and is also forcing your customers to send requirements to other open-pit mines. But this time, your client does not ask you to conduct a root cause analysis of the problem that they are facing. They explicitly tell you that there is a problem with the queues at each digger and crusher, to the extent they are not optimised. The client currently functions without an artificial intelligence solution.

Instead, available trucks are assigned to diggers and crushers randomly on the field. Ideally, the truck assignment should have been considered using the distance between each digger and crusher, and the truck travel time. And the assignment should also have been considered, i.e. which trucks at diggers and crushers go empty in the next few cycles. Your client asks you to build an optimisation model. If you manage to achieve a matching factor of 900+ for a truck and a digger, and a matching factor of 300+ for a truck and a crusher, then the operational cost would reduce by almost 50% and it will save a large amount of money for the higher management.
