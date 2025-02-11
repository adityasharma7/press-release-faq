# SHIP-T Integration

## Merchants using shipping carriers like ShipT for last mile delivery want to ensure that their OMS supports required systemic integrations and real-time sync of fulfillment updates.

HotWax Commerce integrates with shipping carriers like ShipT to help in computing the estimated ship date on a ship group. HotWax Commerce communicates order details and the requested delivery date with ShipT and stores the delivery date confirmed by ShipT. Due to the real-time nature of Shipt deliveries HotWax Commerce also reads fulfillment updates from Shipt webhooks and updates customers instantly.

Traditional integrations with standard shipping companies like Fedex don’t require criteria-set like store operating hours, lead time and pickup deadlines when determining fulfillment SLA eligibility. Not storing granular fulfillment timeline details and communicating exact delivery deadlines to providers like ShipT leads to increased order cancellations from the carrier or delays in fulfillment to the customer. Fulfillment details are also broadcasted by ShipT using webhooks, due to the condensed nature of the fulfillment, which traditional fulfillment integrations don't support.

A specialized integration between HotWax Commerce OMS and ShipT fills in the gaps left by otherwise traditional shipping gateway integrations. When a customer selects same day or next day delivery, HotWax will automatically apply an expected delivery date to the order based on the selected method. After the order is pushed to ShipT, HotWax Commerce saves the delivery date confirmed by ShipT allowing retailers to notify customers of the actual expected ship date if it differs from what they requested. To keep customers posted with their order status from when the order is picked up from store, through delivery, HotWax Commerce will read fulfillment updates using webhooks and email customers with the tracking details. 

Merchants using ShipT as their shipping carrier for last mile deliveries will be able to implement additional criterias supported by HotWax Commerce, along with incoming webhook communication for order fulfillment updates.

*Internal quote* 

*Customer quote*
