# **Financial Services Starter Template**


## Preconfigured Yext resources to build Financial Services digital experiences


# **Overview**

_Use the Financial Services Starter Template to jumpstart your next Yext project. It includes everything you need to begin building your Financial Services digital experiences on Yext including Yext Content configuration, sample data, search configuration, and frontend resources._


# **What’s Included**


## Content


### Entity types


#### Location

This template uses the built in **Location** entity type and includes 3 sample Locations.

#### ATM

This template uses the built in **ATM** entity type and includes 3 sample ATMs.

#### FAQ

This template uses the built in **FAQ** entity type and includes 3 sample FAQs.

#### Help Article

This template uses the built in **Help Article** entity type and includes 3 sample Help Articles.

#### Financial Product

This template uses a custom **Financial Product** entity type and includes 3 sample Products.


#### Service

This template uses a custom **Service** entity type and includes 3 sample Services.


See the Fields section below for a full list of fields included.


## Search


### Backend

Both JAMBO theme and react search experiences are powered by the same search configurations. There are three backend configurations - universal search, advisor search, and locator search. 


### JAMBO Theme

The theme frontends include a universal search experience, advisor lookup, and a locator search.


### React

The included react Pages frontends are not yet fully studio compatible. The search frontends include a universal search experience, a vertical search for Financial Professionals, and a locator for Locations and ATMs. The FAQ accordion cards leverage the answerV2 built-in field on the FAQ Entity Type and render Rich-Text when expanded. The Locator experience leverages the Search UI React Filter Search component. 


## Pages

This starter includes two statically generated templates built on Yext Pages and powered by the Yext Content configuration described above.


### Templates

The two repos includes two streams templates: one for the Financial Professionals and one for Locations. Read more about templates in Pages [here](https://hitchhikers.yext.com/docs/pages/templates/).

## Analytics

This template includes two custom dashboards titled Pages Performance Dashboard & Search Performance Dashboard. These simple dashboards includes insights for each search experience and entity-powered page to monitor engagement with your newly built digital experiences.

# **Installation Guide**


## Pre-requisites

This template requires access to the following Yext products:



* Content
* Pages
* Search


## How to Install



1. In the Yext platform, navigate to **Apps > Solutions**.
2. Select the **Financial Services Starter Template**.
3. Click **View Solution**. This will open up the Admin Console, an account configuration tool that will allow you to add all of the resources mentioned above to your account. 
4. In the upper right corner, click **Apply**.
5. A modal window will open and prompt you to **enter your Account ID**. You can quickly find this in the URL of your Yext account, which takes the form of “[www.yext.com/s/{accountId}/…](http://www.yext.com/s/{accountId}/…)”. Enter the ID and click **Continue**.
6. In the new modal, click **Start authorization flow**. This will open a new window. When prompted, click **Authorize**. Once you receive authorization confirmation, navigate back to the Admin Console window and click **Continue**.
7. Enter your Account ID as the value for the **businessId** variable you are prompted for, then click **Save**.
8. A modal window will pop up showing all of the resources that will be added / edited within your account. Click **Continue** and, when prompted, click **Confirm**.
9. In the Console, you’ll see the message “Applying resources…”. Wait while the resources are applied. You’ll see messages in the console for each resource that is applied and will eventually receive a message saying “Successfully applied resources”.  
10. You’re done! All of the template’s resources have been added to your account. Jump back into your Yext account and explore your new resources!
