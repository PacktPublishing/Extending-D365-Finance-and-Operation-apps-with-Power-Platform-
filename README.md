# Extending D365 Finance and Operation apps with Power Platform

<a href= "https://www.packtpub.com/product/extending-d365-finance-and-operation-apps-with-power-platform/9781801811590"> <img src="https://content.packt.com/B18765/cover_image_small.jpg" alt="Extending D365 Finance and Operation apps with Power Platform" itemprop="url" height="256px" align="right">

This is the code repository for [Extending-D365-Finance-and-Operation-apps-with-Power-Platform](https://www.packtpub.com/product/extending-d365-finance-and-operation-apps-with-power-platform/9781801811590), published by Packt.

**Integrate Power Platform solutions to maximize efficiency of your Finance & Operations projects**

## What is this book about?
Whether you are a technical or functional consultant, this book will help you master Power Platform tools and equip you for convergence scenarios, where Dataverse, the Power Platform, and Dynamics 365 F&O will unfold countless possibilities.

This book covers the following exciting features:
* Get to grips with integrating Dynamics 365 F&O with Dataverse.
* Discover the benefits of using Power Automate with Dynamics 365 F&O
* Understand Power Apps as a means to extend the functionality of Dynamics 365 F&O
* Build your skills to implement Azure Data Lake Storage for Power BI reporting
* Explore AI Builder and its integration with Power Automate Flows and Power Apps
* Gain insights into environment management, governance, and application lifecycle management (ALM) for Dataverse and the Power Platform

If you feel this book is for you, get your [copy](https://a.co/d/420s4zD) today!

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:

```
Patch(
    'CustomersV3',
    LookUp('CustomersV3', 'Customer account' = CustomerGallery.Selected.'Customer account'),
    {
        'Credit limit': Value(CreditLimitInput.Text)
    }
);
Refresh(CustomersV3);
Set(CreditLimitValue, Value(CreditLimitInput.Text));
```

**Following is what you need for this book:**
This book is for Dynamics 365 Finance and Operations consultants, as well as Power Platform consultants eager to harness the diverse tools from Power Platform in their F&O projects. If you are a technical or solutions architect, you’ll find this book useful for acquainting yourself with techniques for addressing business requirements using the Power Platform tools.

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).

## Software and Hardware List
| Software/ Hardware required | OS required/ Other requirements |
| ------------------------------------ | ----------------------------------- |
| Dynamics 365 Finance and Operations Apps | Windows, macOS, or Linux |
| Power Platform | Windows, macOS, or Linux |

## Related products
* Microsoft Power Platform Enterprise Architecture [[Packt]](https://www.packtpub.com/product/microsoft-power-platform-enterprise-architecture-second-edition/9781804612637) [[Amazon]](https://a.co/d/20wSDzC)
* Extending Microsoft Business Central with Power Platform [[Packt]](https://www.packtpub.com/product/extending-microsoft-business-central-with-power-platform/9781803240718) [[Amazon]](https://a.co/d/fwmQv3v)

## Get to Know the Author
**Adrià Ariste Santacreu**
Adrià Ariste Santacreu has been working in the Microsoft Business Applications sphere since 2010, starting with Axapta and Microsoft Dynamics AX, and since 2016 with Microsoft Dynamics 365 F&O. Adrià is a technical solutions architect and developer who loves solving requirements with all the tools available in the Microsoft ecosystem, including Power Platform and the Azure services that can be used with Finance and Operations. Adrià has been recognized as a Microsoft MVP since 2020 in the Business Applications category thanks to his community contributions, including speaking at events and conferences and writing technical articles about Dynamics 365 F&O, Azure, Dataverse, and the Power Platform.



