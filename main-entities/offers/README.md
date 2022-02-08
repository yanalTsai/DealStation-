# OFFERS

## What is An OFFER

Offer Term is used to describe a discount(modeled as a percentage) for a specific Merchant at a specific branch where members coupons can be redeemed

Offers are issued via Merchant and require admin approval to be published and discoverable, each offer contains a maximum number of coupons distributed with predefined percentages for each Merchant branch.&#x20;

{% hint style="warning" %}
Each Branch has its own version of the offer regarding the maximum coupons and the due date
{% endhint %}

Each offer has a lifetime specified by the Merchant or the admin, the lifetime is what differentiate normal offers from flash offers&#x20;

{% hint style="danger" %}
Each Offer must be approved by the admin before its published&#x20;
{% endhint %}

#### Normal Offers

Normal Offers is used  to describe an offer with a due date longer than 3 month

#### Flash Offers

Flash offers term is used to describe an offer with a due date shorter than 1 month, the differentiating factor is that once a flash offer is issued a notification will be sent to the members within the city&#x20;

## OFFER Attributes

| Attribute                 | Description                                                                                                                                                                                                            |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                    |                                                                                                                                                                                                                        |
| **offer title\_en\*\***   | **This attribute is used to indicate offer title**                                                                                                                                                                     |
| **offer title \_ar**      | **This attribute is used to indicate offer title**                                                                                                                                                                     |
| **Offer\_Description**    | **This attribute is used to indicate the Offer description**                                                                                                                                                           |
| **Offer\_image**          | **This attribute is used to indicate Image URL**                                                                                                                                                                       |
| **Offer\_Amount**         |                                                                                                                                                                                                                        |
| **Merchant\_ID**          | **FK - This attribute is used to indicate Associated Merchant**                                                                                                                                                        |
| **Cities**                | **This attribute is used to indicate the ids of cities where this offer will be available**                                                                                                                            |
| **Branchs IDs**           | **This attribute is used to indicate the ids of branches where this offer will be available**                                                                                                                          |
| **Branch-Coupon**         | **This attribute (Table) is used to indicate the coupons available to be redeemed per branch**                                                                                                                         |
| **Total Coupons**         | **This attribute is used to indicate the number of coupons for this offer that can be redeemed**                                                                                                                       |
| **Offer\_Type**           | **This attribute is used to indicate the type of the offer specified in the** [**Offer Types table**](https://docs.google.com/document/d/1uOTUHhntiAFayZK8SKlLJ\_Sm4k6wjIo1kmdQufDwbGU/edit#heading=h.7uk6yt7kfq1r)    |
| **Coupon\_Type**          | **This attribute is used to indicate the type of coupon for this offer**                                                                                                                                               |
| **Status**                | **This attribute is used to indicate the status of the offer specified in the** [**offer status table**](https://docs.google.com/document/d/1uOTUHhntiAFayZK8SKlLJ\_Sm4k6wjIo1kmdQufDwbGU/edit#heading=h.m2n4iiq823d6) |
| **Targeted\_Memberships** | **This attribute is used to indicate what memberships will be able to redeem this offer**                                                                                                                              |
| **Categories\_id**        | **This attribute is used to indicate the set of categories that this offer belongs to**                                                                                                                                |
| **Campaigns \_id**        | **This attribute is used to indicate the set of campaigns that this offer belongs to**                                                                                                                                 |
| **Creation\_Date**        | **This attribute is used to indicate the creation date of this offer**                                                                                                                                                 |
| **End\_date**             | **This attribute is used to indicate the end date of this offer**                                                                                                                                                      |
|                           |                                                                                                                                                                                                                        |

|                                    | Description                                                                                                   |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Normal Offer**                   | **This attribute is used to indicate the most basic form of an offer in the deal station platform**           |
| **Flash Offer \*can be deleted\*** | **This attribute is used to indicate  a normal offer with a lifetime less than 1 month**                      |
| **Paper\_Based\_Offer**            | **This attribute is used to indicate a type of offer that is printed on paper and scanned by members' app**   |

## &#x20;
