ChargeBee Wordpress Plugin for membership management.
=====================================================

[ChargeBee](https://www.chargebee.com/) is easy to use online billing platform for businesses using the paid membership model. With the ChargeBee wordpress Plugin, you will not only be able to manage all your subscriptions but also restrict content based on the plan the member has subscribed to.

##ChargeBee Feature Highlights
ChargeBee is your one shop stop for managing your subscriptions. You will be able to:

* Provide trial period or you can choose to use a freemium model
* Automatically invoice your customers and collect payment
* Notify your customers during various stages of the customer life cycle, through our email notifications
* Add one time charges
* Set up, run and manage different discount campaigns
* Handle credits 
* Use your choice  of payment gateway. ChargeBee suppports Stripe, PayPal Pro, Braintree, Authorize.net eWay, and many more
* Suitable for merchants based out of USA, Canada, Australia, Great Britain, Singapore and 48+ more countries 
* An intuitive system that handles proration when a customer changes plans
* Offline Payments Tracking
* Metered Billing
* Completely customizable Payment Pages to look exactly like your gorgeous website
* Data Portability
* Reports and Dashboards
* Manage Shipping Address
* EU VAT and General Tax Support
* Comprehensive API support. Easy to use client libraries for Python, Ruby, JAVA, PHP and .NET
* Free Tech and Setup Support

And much [more](https://www.chargebee.com/subscription-billing-saas-features.html).

##ChargeBee Plugin provides the following functionality out of the box

* When a user registers in wordpress a subscription is automatically created in ChargeBee with a default plan. You can control this behaviour.
* You will be able to share content with your customers based on their specific subscribed plan. The wordpress user id is used as the identifier with ChargeBee for user access.
* The plugin keeps the subscriber & customer information in sync with ChargeBee using ChargeBee webhook functionality. More on this in admin section. 


##Additional Functionality
If you need additional functionality, you could build it easily on top of this plugin using ChargeBee's php library that is included in this plugin. Please view the [apidocs](https://apidocs.chargebee.com/docs/api) for reference. 

**Note:** The api key initialization is automatically handled.


##Installation

1. Download the latest version of the plugin.
2. Unzip it under '/wp-content/plugins/'
3. Go to admin page -> plugin page. You will find ChargeBee plugin listed.
4. Activate the plugin
5. You will see ChargeBee plugin in the admin menu
6. Go to ChargeBee admin menu and update the ChargeBee site info and API key.
7. Copy the provided webhook url in the admin page and update it in ChargeBee's webhook settings.

Now you are ready to start using ChargeBee plugin.


##Screenshots
1. Configuring your ChargeBee site name, api key and a default plan.
    ![Site Name and API key](plugin_files/screenshot-1.png)

2. Providing the messages to be displayed for restricted content.
    ![Restriction Messages](plugin_files/screenshot-2.png)
3. Webhook configuration
    ![Webhook Configuration](plugin_files/screenshot-3.png)
4. Publishing post with restriction based on plans.
    ![Restricting posts and pages](plugin_files/screenshot-4.png)
5. User view of the content
    ![Viewing restricted content](plugin_files/screenshot-5.png)


##Changelog
= 1.1 =
Webhook calls are checked with the existing customer subscription information and if any change found they are fetched from the ChargeBee.

= 1.0 =
Initial version of ChargeBee plugin.


##Upgrade Notice

= 1.1 =
If the webook data is different from wordpress subscription and customer meta then Subscription or Customer retrieve API call is performed and then meta information are updated.

= 1.0 = 
This is the initial base version of ChargeBee plugin.




