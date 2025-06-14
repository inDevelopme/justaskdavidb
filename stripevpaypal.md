# Stripe and PayPal Payment Setup on Squarespace  

****Authored by:****  [Ryan Lang](https://github.com/langrh), 1st yr. college    

****Last Updated:**** September 21, 2023

## Overview

Stripe and PayPal are two payment services available on Squarespace, each with their own pros and cons. 
However, both can be used simultaneously. This guide will explain how to set up and use both payment processors, along with a comparison between them.

## How to Set Up

1. Navigate to *Commerce -> Payments*.
Once there, PayPal and Stripe will show up as payment methods.
For both, an account must be linked to use.
2. To create an account for Stripe, navigate to [Stripe Registration](https://dashboard.stripe.com/register).
3. To create an account for PayPal, navigate to [PayPal Business Signup](https://www.paypal.com/bizsignup).
4. Once an account is created, link the account on Squarespace then it will be ready for use.

## Stripe and PayPal Payment Comparison on Squarespace

| Aspect                       |  PayPal                                                                                                                                                                                  | Stripe                                                                                                                                                               |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Ease of Use**              | Squarespace integrates seamlessly with PayPal, but the setup process might require creating a PayPal business account. Users can use an existing PayPal account or set up a new account. | Squarespace offers native integration with Stripe, making it relatively straightforward to set up. Users can use an existing Stripe account or set up a new account. |
| **Transaction Fees**         | PayPal's fees may vary depending on factors such as transaction volume, currency conversion, and whether the payment is funded by a PayPal balance, bank account, or credit card.        | Stripe's fees are competitive, with transparent pricing based on transaction volume and other factors.Stripe’s processing fees vary by country.                      |
|
| **Processing**               | Allows checkout without sharing financial info on the merchant site. Payment occurs on PayPal’s website.                                                                                 | Payments take place on the merchant site with Stripe, providing a simpler user experience.                                                                           |
| **Accepted Payment Methods** | PayPal Balance, Bank Account, Credit Cards, and Debit Cards.                                                                                                                             | Credit Cards, Debit Cards, Apple Pay, Google Pay, Stripe subscriptions, and Custom Payment Forms (donations, event registrations, and booking fees.)                 |
| **Security**                 | Secure transactions processed off the merchant site with strong buyer protection policies.                                                                                               | Strong emphasis on security, using encryption to secure transactions and user data.                                                                                  |
| **Support**                  | Phone, email, help center for support.                                                                                                                                                   | Email support, live support for high-tier plans.                                                                                                                     |

*Source:* [ChatGPT](https://chat.openai.com/c/69d01e56-1bff-448c-a134-f51ecc4e8d89)

*Source:* [Payment Methods](https://support.squarespace.com/hc/en-us/articles/206541017-What-payment-methods-can-I-accept-with-Squarespace-Commerce)

## Pros and Cons of Integrating PayPal on Squarespace

### Pros:  
**Trust and Recognition**  
PayPal is one of the most recognized online payment systems. Customers often trust PayPal and are familiar with its payment process.

**Buyer Protection**  
PayPal offers buyer protection, which can make potential customers feel more secure about making purchases.  
*Source:* [PayPal's Purchase Protection for Buyers](https://www.paypal.com/us/webapps/mpp/paypal-safety-and-security)

**International Payments**  
PayPal facilitates international transactions, making it easier for merchants to sell to customers from different countries.  
*Source:* [PayPal's Cross-border Commerce](https://www.paypal.com/us/brc/article/cross-border-commerce)

**Easy Integration**  
Squarespace offers seamless integration with PayPal. Even users without technical experience can easily add PayPal as a payment method.  
*Source:* [Squarespace Help – Accepting PayPal](https://support.squarespace.com/hc/en-us/articles/206540797-Accepting-PayPal)

**Mobile Friendly**  
PayPal offers mobile-optimized solutions for customers shopping on smartphones or tablets.

---

### Cons:

**Fees**  
PayPal charges transaction fees for receiving payments. These fees can add up, especially for businesses with high sales volumes.  
*Source:* [PayPal Merchant Fees](https://www.paypal.com/us/webapps/mpp/merchant-fees)

**Account Holds**  
There have been instances where PayPal freezes accounts due to suspicious activities, which can disrupt the cash flow of a business.  
*Source:* [PayPal's Policy on Holds](https://www.paypal.com/us/smarthelp/article/faq2027)

**Limited Customization**  
While integrating PayPal with Squarespace is easy, customization options for the checkout experience might be limited compared to other payment processors.

**Potential Redirects**  
Depending on the setup, customers might be redirected to PayPal's website to complete the purchase. This can sometimes result in a disjointed user experience.

**Disputes and Chargebacks**  
Although PayPal offers seller protection, merchants can still face challenges with disputes and chargebacks, which can be time-consuming to resolve.  
*Source:* [PayPal's Seller Protection Program](https://www.paypal.com/us/webapps/mpp/security/seller-protection-learn-more)

## Pros and Cons of Integrating Stripe on Squarespace

### Pros:

**Ease of Integration**: 
Both Squarespace and Stripe are designed for users who might not be technically savvy. They have made it simple to integrate Stripe as a payment method on a Squarespace website. [Squarespace Help](https://support.squarespace.com/hc/en-us/articles/206540797-Stripe)

**Security**: 
Stripe is Payment Card Industry (PCI) compliant, which means that it adheres to high security standards. When integrated with Squarespace, you can reassure your customers that their payment details are safe. [Stripe's Security](https://stripe.com/docs/security/stripe)

**Real-time Payment Processing**: 
Transactions happen in real-time, allowing businesses to quickly receive confirmations and proceed with order fulfillment. [Squarespace Help](https://support.squarespace.com/hc/en-us/articles/206540797-Stripe)

**Currency Flexibility**: 
Stripe supports over 135 currencies, allowing Squarespace merchants to sell internationally with ease. [Stripe Global](https://stripe.com/global)

**Transparent Fees**: 
Both Squarespace and Stripe have straightforward fee structures. There are no hidden charges, making it easier for businesses to manage their finances. [Stripe Pricing](https://stripe.com/pricing)

---
   
### Cons:

**Additional Costs**: 
While Squarespace and Stripe have transparent fees, using both can add up. There's a fee from Squarespace for using their platform and a separate fee from Stripe for payment processing. [Squarespace Pricing](https://www.squarespace.com/pricing)

**Limited to Stripe's Payment Methods**: 
Although Stripe supports a wide range of payment methods, there might be some regional or niche payment methods it doesn't support. If a merchant's audience primarily uses one of these methods, they might miss out on sales. [Stripe Payment Methods](https://stripe.com/docs/payments/payment-methods/overview)

**Potential for Chargebacks**: 
Like with many other payment processors, Stripe merchants can face chargebacks. If a customer disputes a transaction, there is a possibility that the funds will be reversed, and the merchant might also incur a chargeback fee. [Stripe Documentation on Disputes](https://stripe.com/docs/disputes)

**Dependency on Third-party Platforms**: If either Squarespace or Stripe faces an outage or technical issue, it could prevent the business from processing transactions. This creates a dependency on both platforms' reliability. 

**Limited Customization**: 
While integrating Stripe with Squarespace is user-friendly, there might be limited customization options compared to integrating Stripe on a custom-built site or other platforms. 

## Conclusion

PayPal and Stripe are both excellent payment processors on Squarespace. The choice between the two depends on business needs, the target audience, and the desired user experience. Implementing both simultaneously is also an option.
