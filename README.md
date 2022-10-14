# SEO Keyword Content Analysis

This application analyses data gathered from your site and your competitor's sites and gives you a comparitive report to highlight where you are missing out on providing content that could help you to rank higher in search engine results and therefore convert more customers.

## Structure

The structure of the data analysed and report given is categorised by the following tree:
1. Brand
2. Region
3. Project/Product
4. Main Site
5. Competitor Site(s)

### Admin Users

An administrative user has all the abilities of a client user, the only difference being that they can view **ALL** entities that are usualy restricted to a single user. Additionally to this an admin user has the permissions to create any of the categorisation entities and add/edit the associated data.

### Client Users

The client user has permissions to view only their allocated Brand, Projects and Sites. The Sites will already have the region set upon creation and so Region only reflects a filtering method for the client user.

## Features

Besides the main feature of displaying and exporting reports of various sites compared to a dictionary, there are some other admin facing features that will also be explained in this section.

### Reporting

To view a report for a project's main site, click on the button labelled `Solo Report` to the right hand side of the main site on the project's overview.

To view a report for a project's main site versus any one of it's competitors, click the button labelled `Vs Report` to the right hand side of the desired competitor site.

To view a full report that will include the main site versus all available competitors, click the `Full Report` button near the top right hand side of the project's overview.

### Exporting

When viewing any report, be it solo, vs or full, it is possible to export a `csv` file version of the report you are currently viewing. The `Export Report` button at the top right hand side of the reporting screen will automatically start the download and you can find the file in your default downloads folder.

The export will reflect exactly what report is currently on screen, so if any filters or other options are applied, the exported report will match. The only notable difference is that the export will include all results (matching the filters) as it is not paginated like the online version.

### Filters

While viewing a report, it is possible to filter the results in a few ways:

- Search
- Topic
- Only Gaps
- Include Opportunities
- Order By Search Volumes
- Order By Match Count

Once options are selected or have some input, click on `Filter` to apply them and the report will be re-generated to reflect the choices made.

#### Search

To search for a particular keyword, or keywords containing a particular word, input the desired word or phrase into the `Keyword Search` box.

#### Topic

The keywords are sub-divided in the dictionary by various topics. Click on the dropdown menu to see the list of available topics for that report. Choose a particular topic by clicking on it. If selected, you will see the chosen topic remaining in the dropdown menu's box.

#### Only Gaps

The gaps are considered to be:

> Keywords that are used by your competitor, but not used by you

The default reports will show both matches and gaps, so to produce a report that shows **ONLY** gaps where your competitors have content but you do not, check this box.

#### Include Opportunities

The opportunities are considered to be:

> Keywords that are neither used by you **OR** your competitor.

When you click on `Full Report` from the project overview, this option is already selected by default, meaning that you have the fullest report possible. To reduce the report down to be only matches and gaps, un-check this box. 

#### Order By Search Volumes

As the search volumes are an indicator of a particular keyword's value, you can order the report to display keywords with their matches in order of search volume from highest to lowest. To do this, click on the table heading `Search Volumes`.

#### Order By Match Count

If the interest is to see which keywords are getting the most coverage by a particular site, you can order the keywords and their matches by match count. Each site in the report has a `Match Count` column heading, so clicking on the desired site's match count will order the results by that site's number of matches per keyword.
