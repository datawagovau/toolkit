# Data.wa.gov.au Toolkit

## Introduction
Data.wa.gov.au simplifies access to Western Australian Government data by enabling anyone to discover data in one place, and is backed by a data infrastructure that facilitates the easy publishing and dissemination data. The platform serves citizens, business, and government alike by promoting the discoverability of data under the [State’s Open Data Policy](http://data.wa.gov.au).

The policy calls for WA Government agencies to release high-value data, openly to the public, in machine-readable formats, and in ways that are easily discoverable and useable. There are a range of resources and guidance to assist agencies in implementing the policy on [data.wa.gov.au](http://data.wa.gov.au) - including an overview checklist and detailed guide for identifying and preparing data for release, a number of factsheets on key components of implementing open data, and links to further websites and resources.

The platform established for data.wa.gov.au is available for use by all WA Government agencies at no cost as a whole-of-government data infrastructure - and we welcome the participation of the AACC Data Warehouse group in this trial.

This toolkit is an evolving resource to assist data custodians with the process of identifying, preparing, and publishing open data and should be read with reference to our exists [fact sheets and toolkit](http://data.wa.gov.au/fact-sheets-and-toolkit) resource.

For assistance with anything please contact [opendata@landgate.wa.gov.au](mailto:opendata@landgate.wa.gov.au).

*The Open Data Data.WA Team*


## Getting an account
Anyone can create an account on data.wa.gov.au, which can be used for commenting or following datasets.

To publish government data you must register an account with a .wa.gov.au email address. Before doing this you must have appropriate permission from your entity to publish on their behalf. You will also be required to request publishing permissions from the data.wa.gov.au team.

Landgate requires all new data custodians to get sign off from their organisation to before creating a publishing account. Landgate reviews publisher accounts periodically to ensure appropriate access to publish on data.wa.gov.au is maintained.

We recommend that you do not use an individual’s email address for the main management account for your data.gov.au organisation. It is much better to use a shared inbox as it provides for continuity should the named data custodian change.

To create an account, go to [http://catalogue.beta.data.wa.gov.au/user/register](http://catalogue.beta.data.wa.gov.au/user/register) and complete the form on the page. Then email [opendata@landgate.wa.gov.au](mailto:opendata@landgate.wa.gov.au) with the following email to verify who you are and that you wish to be granted publishing privileges:

> Dear Data.WA,
>  
> On behalf of the *{agency name}*, I request a data publishing account on data.wa.gov.au. *{agency name}* will be responsible for the management of this account and the data that is published using it. *{agency name}* will notify the Open Data Team at Landgate as to any changes in ownership of the account and of any issues if they arise. The responsibility of publishing data appropriately, in accordance with privacy, security and other relevant considerations rests entirely with the data publisher and Landgate take no responsibility.
> 
> I have registered the account name *{account name}* with email address *{email address}* on data.wa.gov.au and request access to the organisation(s) *{organisation name(s)}* to publish data and act as an administrator for my organisation.
> 
> I understand that Landgate intends to continue to provide data.wa.gov.au as a whole of government data publishing platform at no cost to government data publishers. If circumstances change, Landgate will give data publishers at least 2 months notice. Landgate will also provides documentation and minimal free technical support to data publishers.


## A note for SLIP Publishers
WA Government agencies who currently publish their geospatial data through the [Shared Location Information Platform (SLIP)](http://slip.landgate.wa.gov.au) will not need to republish their data on data.wa.gov.au. The available service endpoints (e.g. WMS, WFS, Downloads), and geospatial extent, of datasets published through SLIP are automatically updated in data.wa.gov.au each day.

All other aspects of datasets are however free to be managed and updated by custodians themselves via data.wa.gov.au, and we warmly welcome custodians who would wish to take direct control over maintaining their datasets.

In doing so, however, please note that you will **still need to following the standard SLIP change process** if you:

1. Wish to remove or delete a dataset from data.wa.gov.au;
2. Need to change the name of a dataset; or
3. Would like to make a dataset private to hide it, or restrict access to it.

Please fill out and email a copy of the [SLIP Data Services Change Request form](https://www2.landgate.wa.gov.au/c/document_library/get_file?uuid=35f06296-a1a7-45b8-adb1-d69fe9ede72b&groupId=10136) to [customerservice@landgate.wa.gov.au](mailto:customerservice@landgate.wa.gov.au) before taking any action in data.wa.gov.au so we can coordinate the process.

**NB:** Please note that the "date data last updated" field is currently not automatically update from SLIP. We're currently examining how to achieve this in the new SLIP environment.


## A note for SPC Members
If you are a member of the Western Australian Statistical Policy Committee (SPC) looking to publish your datasets, or metadata records for your data as part of the *SPC Metadata Project*, you will find a step-by-step guide to publishing data in the section below.

If you are publishing metadata records for the *SPC Metadata Project*, we suggest that you include an **"spc"** tag in any metadata records you publish so as to aid discoverability.

Additionally, the second step detailed below - Add data - is the point at which you will be able to upload the Word, PDF, et cetera documents you prepared as part of the project.


## Publishing Data
Data.wa.gov.au already contains explanations of the fields you'll need to fill in as part of the data publishing process. This longer step-by-step guide is intended for first-time users and includes some more descriptive explanations of certain fields.

* Login with your authenticated account 
* Browse to Datasets (top menu) 
* Click **Add Dataset** (Remember you may have multiple files in the one dataset.) 
* On the first page you’ll be asked to complete fields to describe your data (the metadata).
    * **Title** (required): name of the dataset.
    * **Description**: descriptive information about the dataset can also include further information or caveats pertaining to the data. * For formatting you can use [markdown](http://daringfireball.net/projects/markdown/syntax).
    * **Tags**: some tags (or keywords) that describe your data.
    * **License** (required): a dropdown of available licenses for data.wa.gov.au ([*Licensing Creative Commons is endorsed by WA Government and the recommended default under the Open Data Policy*](http://data.wa.gov.au/fact-sheets-and-toolkit/licensing-and-charging))
    * **Organisation**: a dropdown of organisations you can publish to. Most users can only publish to a single organisation. This will be automatically filled in.
    * **Visibility**: whether the dataset will be viewable to all users once complete. The default is private. 
    * **Data Portal**: another website or resource that users may go to to discover more context and information about the dataset (e.g. The relevant page on your agency's website). If that does not apply, leave it blank.
    * **Data Homepage:**: for datasets that exist in another catalogue (e.g. SLIP) this will be the access point for detailed catalogue-specific information about the dataset. If you're unsure, leave this blank.
    * **DOI**: the Digital Object Identifier assigned to your dataset (if you have created one). More information about the DOI system [is availabe here](http://www.doi.org), and is more typically used in scientific disciplines and publishing. If you're unsure, leave this blank.
    * **Citation**: the citation that users of the dataset should use in publications, articles, et cetera. If you're unsure, leave this blank. 
    * **Author & Author Email**: the name and email address of the person who is primarily dataset for creating and maintaining the data.
    * **Maintainer & Maintainer Email**: the name and email address of the person who is responsible for maintaining the dataset on data.wa.gov.au.
    * **Theme**: the [AGIFT](http://agift.naa.gov.au) top level government function to which the dataset relates.
    * **Language**: the language in which the dataset is published. The default is English.
    * **Published On**: the date on which this dataset was, or shall be, published.
    * **Data last updated on**: the date on which the data on data.wa.gov.au itself was last updated.
    * **Update Frequency**:    how often the dataset is updated. Eg: Daily, Weekly, Never.
    * **Temporal Coverage From / To** (required): the span of time from/to which the data is applicable. If the data applies only to a single point in time you should only fill in the Temporal Coverage From field.
    * **Geospatial Coverage** (required): this is the physical area which the data covers. It is used to power the search functionality of data.wa.gov.au, so it does not need to be precise. It can be;
        * a rectangle/polygon drawn by-hand;
        * a pre-defined extent; or
        * a [GeoJSON](http://geojson.org) formatted Polygon/MultiPolgon.
        * **NB**: Data sourced from SLIP will populate this field automatically.
* Click **Next: Add Data**
* Click **Upload** and select the file, or link to a file, you wish to add to the dataset (e.g. the data itself, or any data dictionaries, metadata statements, et cetera you may have. See [Supportive documentation/context](#Supportive documentation/context). Add a description for this file and add the (likely) 3 letter file extension to the Format field.
  * You can add additional files to the dataset by clicking **Save and add another** and repeating the process. When finished adding resources click **Next: Additional Info**.
* Click the **Finish** button.

### Supportive documentation/context
Publish any supportive documentation, caveats, user restrictions, and contextual information in the text of the descriptive information about the data set. If the information is extensive it can also be uploaded as a an additional resource to the dataset.

Please do not put the data into the documentation itself, as it means the platform will treat it as just another file like a PDF rather than as a data file. This means the data is inaccessible to users and no API or data visualisation will be available for your dataset.

### Publishing Screenshots
![A screenshot of the 'Create dataset' page on data.wa.gov.au ](../imgs/create-dataset-step-1.png)
**Publishing a new dataset – Step 1 - Details about the set**

![A screenshot of the 'Create dataset' page on data.wa.gov.au ](../imgs/create-dataset-step-2.png)
**Publishing a new dataset – Step 2 - Upload file(s) or a link to a data service**


## Updating an Existing Dataset
For information on updating an existing dataset, or uploading updated versions of data, please see [toolkit.data.gov.au](https://toolkit.data.gov.au/index.php?title=Publishing_Data#Updating_an_Existing_Dataset).


## Attribution
With thanks to the Data.gov.au Team. Parts of this toolkit are based on [toolkit.data.gov.au](https://toolkit.data.gov.au) under the Creative Commons Attribution 3.0 license.
