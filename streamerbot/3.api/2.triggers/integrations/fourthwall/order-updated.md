---
title: Order Placed
description: Trigger for a FourthWall Order being placed
version: 0.2.3
variables:
  - name: fw.createdAt
    type: DateTime
    description: The DateTime of the placed order in UTC
  - name: fw.UpdatedAt
    type: DateTime
    description: The DateTime of the updated status in UTC
  - name: fw.orderId
    type: string
    description: Id of the donation
  - name: fw.shopId
    type: string
    description: Id of the shop
    value: sh_7ad0c438-beda-4779-a885-0dc325a755c1
  - name: fw.friendly
    type: string
    description: Friendly Id
    value: F2LGPYCV
  - name: fw.checkoutId
    type: string
    description: Id of check out
  - name: fw.status
    type: string
    description: Status of the order
    value: SHIPPED
  - name: fw.email
    type: string
    description: E-mail adress of the supporter
    value: support@fourthwall.com
  - name: fw.emailMarketingOptIn
    type: boolean
    description: If user opted in to email marketing
  - name: fw.username
    type: string
    description: Username of the supporter
  - name: fw.statmessageus
    type: string
    description: Attached message
    value: message from supporter
  - name: fw.currency
    type: string
    description: Donation currency
    value: USD
  - name: fw.subtotal
    type: number
    description: Subtotal of order
    value: 10
  - name: fw.shipping
    type: number
    description: Shipping Cost
    value: 5
  - name: fw.tax
    type: number
    description: Tax Cost
    value: 1
  - name: fw.donation
    type: number
    description: Donation added to the order
    value: 3
  - name: fw.discount
    type: number
    description: Discount amount that was applied
    value: 2
  - name: fw.total
    type: number
    description: Order total amount
    value: 17
  - name: fw.variants[\#].id
    type: string
    description: Product Id
    value: b2c201d3-8104-4b2a-b2c9-1f6b335b650a
  - name: fw.variants[\#].name
    type: string
    description: Product name
    value: New T-shirt
  - name: fw.variants[\#].sku
    type: string
    description: SKU number of product
    value: Z3YD-8CTV00S
  - name: fw.variants[\#].image
    type: string
    description: Link of the first product image
    value: https://cdn.staging.fourthwall.com/customization/sh_7ad0c438-beda-4779-a885-0dc325a755c1/5a125858-0e0c-4099-996f-db61cbd62f8e.jpeg
  - name: fw.variants[\#].unitPrice
    type: number
    description: Price of product
    value: 5
  - name: fw.variants[\#].currencyCode
    type: string
    description: Currency code
    value: USD
  - name: fw.variants[\#].quantity
    type: string
    description: Quantity of product in order
    value: 2
  - name: fw.variants[\#].attributes.description
    type: string
    description: Product description
    value: White, S
  - name: fw.variants[\#].attributes.color
    type: string
    description: Color of product
    value: White
  - name: fw.variants[\#].attributes.colorSwatch
    type: string
    description: Hex color of product
    value: \#FFFFFF
  - name: fw.variants[\#].attributes.size
    type: string
    description: Size of product
    value: S
  - name: fw.variants[\#].stock
    type: string
    description: Current stock of product
    value: 0
  - name: fw.source
    type: string
    description: Type of FourthWall webhook
    value: ORDER
  - name: fw.update
    type: string
    description: What updated on the order
    value: STATUS
---
