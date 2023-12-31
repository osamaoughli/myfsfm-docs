
# Setting up Stripe



To setup Stripe,
`Explore &gt; Integrations &gt; Stripe Settings`


#### Setup Stripe


To enable Stripe payment service, you need to configure parameters like Publishable Key, Secret Key
![Razorpay Settings](/files/stripe_setting.png)


On enabling service, the system will create Payment Gateway record and Account head in chart of account with account type as Bank.


![Stripe COA](/files/stripe_coa.png)


Also it will create Payment Gateway Account entry. Payment Gateway Account is configuration hub from this you can set account head from existing COA, default Payment Request email body template.


![Payment Gateway Account](/files/payment_gateway_account_stripe.png)


After configuring Payment Gateway Account your system is able to accept online payments.


### Setup subscriptions plans


If you need to bill a recurring amount instead of a one-time charge, you can use Stripe's subscription system.


Once you have created your billing plans in Stripe, add one or several new "Payment Plan" in Frappe.


![Payment Plan](/files/payment_plan.png)


Afterwards, when you create your payment request, click the check field "Is a subscription" and add the system will fetch the corresponding susbscription plans from within the corresponding subscription.


![Payment Request](/files/subscription_payment_request.png)


ERPNext will automatically create a new subscription for this customer in Stripe.


#### Supporting transaction currencies



```
"AED", "ALL", "ANG", "ARS", "AUD", "AWG", "BBD", "BDT", "BIF", "BMD", "BND",
"BOB", "BRL", "BSD", "BWP", "BZD", "CAD", "CHF", "CLP", "CNY", "COP", "CRC", "CVE", "CZK", "DJF",
"DKK", "DOP", "DZD", "EGP", "ETB", "EUR", "FJD", "FKP", "GBP", "GIP", "GMD", "GNF", "GTQ", "GYD",
"HKD", "HNL", "HRK", "HTG", "HUF", "IDR", "ILS", "INR", "ISK", "JMD", "JPY", "KES", "KHR", "KMF",
"KRW", "KYD", "KZT", "LAK", "LBP", "LKR", "LRD", "MAD", "MDL", "MNT", "MOP", "MRO", "MUR", "MVR",
"MWK", "MXN", "MYR", "NAD", "NGN", "NIO", "NOK", "NPR", "NZD", "PAB", "PEN", "PGK", "PHP", "PKR",
"PLN", "PYG", "QAR", "RUB", "SAR", "SBD", "SCR", "SEK", "SGD", "SHP", "SLL", "SOS", "STD", "SVC",
"SZL", "THB", "TOP", "TTD", "TWD", "TZS", "UAH", "UGX", "USD", "UYU", "UZS", "VND", "VUV", "WST",
"XAF", "XOF", "XPF", "YER", "ZAR"

```



