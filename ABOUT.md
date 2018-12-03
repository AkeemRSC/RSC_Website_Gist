# RSC SharePoint Repository

###### 12.03.2018

This folder serves as a staging environment for all the breaks and customizations done to RSC Solutions' website.

If there are changes that need to be made, look for the specific alteration from the code by indexing the page from the direct page or droplinks and find the title of the section from goDaddy.

If a new page is to be added to the page, the naming convention should be enforced as follows:


     [section]__[page_section]__[PAGE (optional if the custom code is applied to all pages)]__[page or all pages(P or A)].html


Lets illustrate the naming protocol through a made-up situation.

> A developer would like to add a new page called **strategic partners** under the dropdown labeled _connect with us_ and have code to illustrate a graphic design placed in the _Site Content_ section. He headlines the html code as **Partners** and he minifies the section to be 0px wide upon loading.

The situation above calls for the html file to be saved to sharepoint as: 

**Partners__site_content__STRATEGIC_PARTNERS__P.html**

The first clip of the filename is refers to the title of the section. Sometimes a code solution's section will be labeled as _HTML_ if there are elements written in html that are required to appear at site navigation without a headline. Spaces in a page or headline will be replaced by `underscores` and each clip of the file name are separated by two underscores. The section where the page is being adjusted or having new code implemented is evaluated by the block name on goDaddy's goCentral framework. This second clip of the filename is in lower caps. The third snippet of the filename are all in uppercase denoting the page title of the document and finally the fourth clip indicated whether the code is defined for all the pages or for one page in particular.


