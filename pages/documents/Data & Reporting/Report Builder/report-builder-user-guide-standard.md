---
pagename: User Guide (standard)
categoryName: Data & reporting
subCategoryName: Report Builder
indicator: both
subtitle: 'User guide for users with read only access '
level3: ''
permalink: data-reporting-report-builder-report-builder-user-guide-(standard).html
isTutorial: false
date: '2019-01-10T09:10:56.000+00:00'

---
## Accessing Report Builder

Brands can access Report Builder through the LiveEngage UI, from the messaging real time dashboard, queue health dashboard, and campaign dashboard.

To access the Report Builder:

1. Log into LiveEngage using your campaign manager or agent manager credentials.
2. Open the dashboard by clicking the drag down icon.
3. Click the Report Builder icon on the left of the screen. A new tab is opened.
4. Click **shared reports**. Two folders are displayed:
   * **LE predefined dashboards**: All available predefined LiveEngage dashboards.
   * **My account**: Reports that have been designed specifically for your account.
   * **Analytics RB reporting**: Customized dashboards created by LP for brands with a customization package.
5. Click on a folder to view the available reports inside.

**How to video:** [**Getting started**](https://bcove.video/2vj2Sid)

## Data view restrictions

Report Builder filters data by agent groups, meaning that agent group managers can see data from their own group(s) and subgroups only.

Where there is data that cannot be pre-filtered by agent group, there are also restrictions by role:

* Agent managers are not allowed to view data in the business activity dashboard that cannot be filtered by agent groups.
* If a copy of the business activity dashboard is saved under the ‘my account’ folder, an agent manager trying to access it will receive an error message and will not be able to see any data.
* No restrictions apply for campaign managers.
* Agent managers required to view business data available on the business activity dashboard will need to be assigned the role of campaign manager as well.

## Report Builder folders

Dashboards in Report Builder are saved in folders. The available folders are as follows:

* **Shared reports -** dashboards saved here are visible to all the users in the account.
* **Predefined dashboards**: All available predefined dashboards.
* **My account**: Reports that have been designed specifically for your account, created by you, other users in the account or by the LP account team.
* **Analytics RB reporting**: Customized dashboards created by LP for brands with a customization package. All users eligible for receiving these customized reports will have view access to the folder and its dashboards.
* **My reports -** dashboards saved here are visible only to the user who created the dashboard.

## LiveEngage predefined dashboards

The LiveEngage Report Builder provides a robust reporting platform with powerful DIY features allowing brands to create their own business-intelligent dashboards. LiveEngage comes with a set of predefined dashboards which offer ready made reports for account data flowing into Report Builder from the LiveEngage data platform. These predefined dashboards can be used out of the box, or manipulated to create customized reports which contain unique key performance indicators.

If you wish to enrich the predefined dashboards, and customize them to their needs are requested to approach their LivePerson account manager.

The data currently available in the predefined dashboards are as follows:

* **Messaging & Live Chat dashboards:**
  * [**Agent activity dashboard**](data-reporting-messaging-messaging-dashboards-agent-activity-dashboard.html): Includes operational data about agents
  * [**Goals tracker dashboard**](data-reporting-messaging-messaging-dashboards-goal-tracker-report.html): Includes information about each conversion
* For Messaging only:
  * [Performance Dashboard for Messaging](data-reporting-messaging-messaging-dashboards-messaging-performance-dashboard.html) Includes operational and business data about messaging conversations.
  * Survey dashboard for Messaging: Includes information about responses to surveys
  * [Business dashboard for Messaging:](data-reporting-live-chat-chat-dashboards-business-activity-dashboard-grid.html) Includes information about campaigns and engagements performance. Business Activity Grids are also available in Excel export formats, in daily and monthly level aggregations.
* **Chat only dashboards:**
  * [**Operational & staffing dashboard**](data-reporting-live-chat-chat-dashboards-operational-staffing-dashboard.html) **for Live Chat:** Includes information about skill performance and skill demand
  * [**Survey dashboard for LiveChat:**](data-reporting-live-chat-chat-dashboards-survey-activity-dashboard.html) Includes information about responses to surveys
  * [**Skill dashboard** for Live Chat](data-reporting-live-chat-chat-dashboards-skills-activity-dashboard.html) Includes operational data about skills
  * Business dashboard for LiveChat: Includes information about campaigns and engagements performance.

{: .notice}  
The data included in Report Builder is constantly evolving.

## Metrics glossary

Before beginning your analysis using the available predefined dashboards, we highly recommend opening the glossary listing all metrics with their corresponding formulas and descriptions.

The glossary contains a full list of metrics available through report builder. Metrics that do not appear in the predefined dashboards can be added by a LivePerson member to the account specific dashboards upon request. Please reach out to your account manager or customer success manager for information about gaining access to additional metrics.

Click [here](https://developers.liveperson.com/essential-resources-report-builder-data-metrics.html) to access the Report Builder Data Metrics

## Field details sheet

Every predefined dashboard includes a sheet titled “field details.” This sheet presents a grid with the definitions of each metric and attribute displayed in the visualizations of the dashboard.

### **Viewing reports**

Each report in Report Builder includes dashboard view(s) and field details. You can change between views by using the tabs at the bottom of the screen.

**To run a report:** Click on the dashboard you wish to open.

### **Time-frame selector**

When selecting a dashboard to run you will be asked to select a timeframe for the dashboard data. This prompt is the “time frame selector.” The dashboard will only present data from the pre-loaded timeframe. You can always “re-prompt” from within the dashboard’s file menu.

In the selector, you may choose from one of the following time-frame options:

1. Last 120 days
2. Last 60 days (default)
3. Last 30 days
4. Filter for months - choose up to four individual months from the past 13 months

### **Hour offset selector**

When running the [agent activity dashboard](data-reporting-messaging-messaging-dashboards-agent-activity-dashboard.html) or the [goal tracker dashboard](data-reporting-messaging-messaging-dashboards-goal-tracker-report.html), another prompt will be shown - “hour offset selector.” This prompt presents a selection of time offsets from the default timezone of the account. Using this allows you to present the data in the dashboard in your local time zone (in case it is different from the account's).

If you do not require any change in view from the account default time zone setting, you won’t need to choose anything in the pop-up prompt before running the dashboard (the default offset is TZ+0 which is a zero hour offset from the account default setting).

### **Dashboard view**

Data is displayed in a graphical format and/or in grid view. The data is presented to all users according to their LiveEngage account-level time zone, even if their user-level time zone has been configured differently.

![](/img/User-guide6.png)

Hover over any report with your mouse to view an explanation of what the report displays. You can customize how the data is displayed by choosing your own color scheme.

## Filtering reports

Each report can be filtered to ensure that only the most relevant data is displayed. Reports can be filtered according to specific criteria. These criteria include some or all of the following parameters: date, agent group, agent, skill and so on.

To filter a report:

1. Select a report either from the predefined dashboards or from the reports in My Account. For the example below, the Agent Activity Dashboard is used.
2. On the left of the screen, select the dates for which you would like to display data.

   Please note:
   * Data will only display for dates chosen within the timeframe selected when you first ran the report.
   * You can select specific dates using the calendar option, or you can select dynamic date to select a timeframe relative to today’s date.

     ![](/img/User-guide-4.png)
3. Click **OK**.
4. Under each parameter, for example Agent, use the checkmarks to select the data you would like to be displayed.
5. At the top left of the screen, click **Apply.** The data will now be displayed according to your preferences.

![](/img/User-guide5.png)

**How-to video:** [**Filtering**](https://bcove.video/2wwcWD6)

## Exporting reports

Exports can be exported in PDF or Excel format.

To export a report:

1. Hover your mouse cursor over the top right corner of your screen until an arrow is displayed.
2. Click the arrow, and then select **export.** The following options are displayed: **Excel**, **PDF**, **data**.
3. Select an export option.

By default:

* Excel will be used when the view is grid.
* PDF will be used when the view is widgets.
* Data is exported to a CSV file.

## LivePerson technical support

LivePerson technical support is available 24/7 in the[ Connection Area](https://liveengage.liveperson.net/a/new/#registration!signUp).

Please note that LivePerson support troubleshoots and resolves issues in predefined dashboards officially released by LivePerson as part of the product.

Issues with dashboards residing in the “my account” or “my reports” folder should be directed to your account manager.