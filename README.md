# SEO Keyword Content Analysis

This application analyzes data gathered from your site and your competitor's sites and gives you a comparative report to highlight where you are missing out on providing content that could help you to rank higher in search engine results. 
This results in your conversion of more customers.
{: style="text-align: justify"}

### Table of Contents

- [How it works](#how-it-works)
	- [Dictionary](#dictionary)
	- [Site Data](#site-data)
- [Structure](#structure)
- [Features](#features)
	- [Reporting](#reporting)
	- [Exporting](#exporting)
	- [Filters](#filters)

## How it works

This tool takes a dictionary of terms that is curated by experts in SEO and specified for a particular industry and compares the terms given in that dictionary to data retrieved from your site and the sites of your competitors. 
{: style="text-align: justify"}

It aims to help highlight where you may be falling short or missing out altogether through comparison with your competitors and the search volumes for the keywords defined in the dictionary. 
{: style="text-align: justify"}

Using this comparison, it can produce a report which is tailored to your site, and can be further filtered depending on which information you wish to extract from the large amount of data it is capable of producing.
{: style="text-align: justify"}

The reports themselves are both visible online while using the tool and exportable as a `csv` file which can be viewed using any spreadsheet software like Excel.
{: style="text-align: justify"}

### Dictionary

A dictionary for a project is the base which the tool uses for it's comparisons.

The main element of the dictionary is the keywords and each of these also carries two other valuable pieces of informationwith them, allowing for further ranking and analysis, they are:
{: style="text-align: justify"}

- [Topic](#topic)
- [Search Volume](#search-volume)

#### Topic

This allows you to classify and group keywords together should you wish to look at a group of similar keywords or compare how a certain keyword performs compared to similar or alternative keywords.
{: style="text-align: justify"}

This can be considered a "sub-category" if the project/product is the "category".
{: style="text-align: justify"}

#### Search Volume

This figure shows the relative number of searches made on search engines in the given region for the particular keyword it accompanies.
{: style="text-align: justify"}

Keep in mind that they may change for the same keyword depending on which region the report is for as the dictionary of the project is provided with search volumes **in each** of the given regions.
{: style="text-align: justify"}

### Site Data

The site data is unique to the site as it is a record of the content from the entire site. This is what is compared to the dictionary and how the number of matches and types of matches are derived.
{: style="text-align: justify"}

This data is uploaded by the administrator and can only be altered by them.
{: style="text-align: justify"}

## Structure

The structure of the data analyzed and report given is categorized by the following tree:
1. Brand
2. Region
3. Project/Product
4. Main Site
5. Competitor Site(s)

### Admin Users

An administrative user has all the abilities of a client user, the only difference being that they can view **ALL** entities that are usualy restricted to a single user. Additionally to this an admin user has the permissions to create any of the categorisation entities and add/edit the associated data.
{: style="text-align: justify"}

### Client Users

The client user has permissions to view only their allocated Brand, Projects and Sites. The Sites will already have the region set upon creation and so Region will only reflect a filtering method for the client user.
{: style="text-align: justify"}

## Features

Besides the main feature of displaying and exporting reports of various sites compared to a dictionary, there are some other admin facing features that will also be explained in this section.
{: style="text-align: justify"}

### Reporting

#### Solo Report
To view a report for a project's main site, click on the button labelled `Solo Report` to the right hand side of the main site on the project's overview.
{: style="text-align: justify"}

#### Vs Report
To view a report for a project's main site versus any one of it's competitors, click the button labelled `Vs Report` to the right hand side of the desired competitor site.
{: style="text-align: justify"}

#### Full Report
To view a full report that will include the main site versus all available competitors, click the `Full Report` button near the top right hand side of the project's overview.
{: style="text-align: justify"}

### Exporting

When viewing any report, be it solo, vs or full, it is possible to export a `csv` file version of the report you are currently viewing. The `Export Report` button at the top right hand side of the reporting screen will automatically start the download and you can find the file in your default downloads folder.
{: style="text-align: justify"}

The export will reflect exactly what report is currently on screen, so if any filters or other options are applied, the exported report will match. The only notable difference is that the export will include all results (matching the filters) as it is not paginated like the online version.
{: style="text-align: justify"}

### Filters

While viewing a report, it is possible to filter the results in a few ways:
{: style="text-align: justify"}

- Search
- Topic
- Only Gaps
- Include Opportunities
- Order By Search Volumes
- Order By Match Count

Once options are selected or have some input, click on `Filter` to apply them and the report will be re-generated to reflect the choices made.
{: style="text-align: justify"}

#### Search

To search for a particular keyword, or keywords containing a particular word, input the desired word or phrase into the `Keyword Search` box.
{: style="text-align: justify"}

#### Topic

The keywords are subdivided in the dictionary by various topics. Click on the dropdown menu to see the list of available topics for that report. Choose a particular topic by clicking on it. If selected, you will see the chosen topic remaining in the dropdown menu's box.
{: style="text-align: justify"}

#### Only Gaps

The gaps are considered to be:

> Keywords that are used by your competitor, but not used by you

The default reports will show both matches and gaps, so to produce a report that shows **ONLY** gaps where your competitors have content but you do not, check this box.
{: style="text-align: justify"}

#### Include Opportunities

The opportunities are considered to be:

> Keywords that are neither used by you **OR** your competitor.

When you click on `Full Report` from the project overview, this option is already selected by default, meaning that you have the fullest report possible. To reduce the report down to be only matches and gaps, un-check this box. 
{: style="text-align: justify"}

#### Order By Search Volumes

Search volumes are an indicator of a particular keyword's value. You can order the report to display keywords with their matches in order of search volume from highest to lowest. To do this, click on the table heading `Search Volumes`.
{: style="text-align: justify"}

#### Order By Match Count

If the interest is to see which keywords are getting the most coverage by a particular site, you can order the keywords and their matches by match count. Each site in the report has a `Match Count` column heading, so clicking on the desired site's match count will order the results by that site's number of matches per keyword.
{: style="text-align: justify"}

