# Sagepay Module

> Note: Broadleaf Commerce currently offers integration with Sagepay through a commercial integration module. To obtain this third party integration or if you have any questions about this module, please contact us at info@broadleafcommerce.org

![Sagepay Diagram](payment-sagepay-diagram.png)

## How It Works
1. On the final checkout page, the customer fills out their shipping address and billing address and hits submit. This information will be saved and a Sagepay crypt will be generated with the customer and order information.
2. Broadleaf will then return a form with required fields populated for Sagepay. This page will automatically redirect the customer to Sagepay to complete the Credit Card information segment.
3. After filling out the credit card information with Sagepay and hitting complete purchase, the customer's browser will then redirect to a Broadleaf URL with a crypt to complete checkout. The customer will be redirected to either a success or failure URL.
4. Broadleaf will complete the checkout process.
5. If successful, Broadleaf will return the confirmation page.

There are two ways to get started integrating this payment gateway into your eCommerce application.
Broadleaf offers a [[Sagepay Quick Start]] solution that allows developers to easily add Sagepay functionality
with little configuration. If you have a simple eCommerce store and want an easy way to start accepting payment, this is a good place to start.
On the other hand, if your application has a more complex payment workflow, you can customize your implementation using the [[Sagepay Advance Configuration]] guide.
