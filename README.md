#SAAS for backlink check

The purpose of the tool is to allow the follow-up of backlinks for different sites, in an automatic way.

Here are some more details :

The purpose of the tool is to allow the follow-up of backlinks for different sites, in an automatic way.
The tracking should allow to detect the removal of pages on which backlinks are present, but also the removal of the link itself, or its nature (eg: change from dofollow to nofollow).
The tool will also allow customers to share with their own customers the view of projects.
Finally the tool will allow to check regularly the indexation or not of a backlink.

1) The objectives

The main objectives of the tool are to be able to follow the state of the backlinks but also to automatically inform the owners in case of problem

2) The targets
The people who will use the application are :
Users (direct customers of the application)
End customers (users' customers, who can see a campaign only)
Administrator

3) Type of application to develop
A software in SaaS mode.//Software as a Service
The recommended language is Laravel.
For the front end, it would be desirable to use Josh (https://codecanyon.net/item/josh-laravel-admin-template-front-end-crud/8754542) or OneUI
For the verification of backlinks, solid bases exist (https://phpsources.net/script/php/codes/2024-1_check-back-link)

4) Main views
The main views of the application will be :
- Project - Create, edit, delete
- Site - Add, edit, delete //
- URL - Add, edit, delete
- Bulk URL by CSV - Add, edit, delete
- Customer - Add, edit, delete //how???
- Credit - Add, edit, delete
- Backlink buying platforms - Create, edit, delete //meaning
- Choice of checking frequency - daily, weekly, bi-weekly, monthly, quarterly, yearly
- Choice of items that will generate an automatic email (for the user and for the backlink buying platform)
- Choice of the frequency of indexing verification
- Third party access - Create, edit, delete (for a single read-only project view)
- Mail alert - Choice of criteria that generate a mail (dofollow, noindex, deindexed page)
- Main view (dofollow / nofollow / etc.. indexed / not indexed, platforms used, anchors) //??
- Project view (dofollow / nofollow / etc. indexed / not indexed, platforms used, anchors) //??

5) Information present for each backlink
- URL of the source site (mandatory)
- Anchor of the backlink (optional)
- Manual score (optional)
- Price of the backlink (optional) 
- Backlink purchase platform (optional)

6) Other features to be implemented
- CSV export of all backlinks + CSV export per project with status of each backlink

https://www.freelancer.com/
Has a backlink here :
https://www.photoanywhere.com/
and here
https://www.etrusoft.com/links.htm
