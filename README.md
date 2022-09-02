# WHATSAPP GROUP DATA ANALYSIS

![Icon](https://github.com/Mr-Art-coder/Whatsapp-Data-Analysis/blob/main/Charts/Whatsapp.jpg)

----
# INTRODUCTION
Intellectual Traditionist WhatsApp platform is a group that comprises all bonafide comrades who belong to a union group called Tradition in TASUED. Being a very busy platform, I decided to carry out an analysis to know how busy the platform can be, how users send messages, and message trends daily. The motive of the analysis is to find out the members who keep the platform busy and how busy the platform can be in a day or month.

----

# DATA SOURCE

The dataset used for this analysis was gotten from the chat exported from the Intellectual Traditionist WhatsApp platform. All media were excluded.

----

# DATA TRANSFORMATION

After the exportation of the chats, all the data were together in a column. I opened the data in Microsoft Excel and study the single column to know how the data will be regrouped. After understanding the dataset’s arrangement, I imported the txt file into Power BI power query where I did all the wrangling.
I imported the single-column txt file into Power BI and cleaned it in the power query. I added 5 new columns from the original single column. I separated the Year, Time, User, and Message into these five columns.
Being a txt file, some messages spilled over to another row, because of this, new columns were added from the Year column, the columns are Day and Month. Because of the spilled messages, some rows in the Month column that does not contain number showed error, so these rows were removed, and the spilled message was also removed from other rows automatically.
The four months came in number (5,6,7,8), but they were replaced to text (May, June, July, and August) for comprehension.
To remove some unwanted data, all the columns were filtered. For example, in the username column, some data which include (someone who was added, someone who left, and the verification number of someone who has changed) were filtered out.

----

# VISUALIZATION

The charts used to visualize the analysis include card, clustered bar chart, line, slicers, stacked column charts, and table
1.	Card: Three cards were used to visualize the total number of group members, the total number of active participants and the total number of messages.
2.	Clustered bar chart: This was used to visualize the Top 5 most active members of the group.
3.	Stacked column charts: This was used to visualize number of messages per month.
4.	Line: It showcase the trend among the days.
5.	Table: It visualize all members with their total messages.
6.	Slicer: Two slicers were used, one to filter by day and other to filter by month.

----
# FINDINGS

The total number of messages generated from the group within the timeframe of May 29 to August 26 is 39858 thousand, these messages were dropped by 132 active members of the group out of the total 148 members.
In all the months covered, Ifedayo Jimcruiz stood as the most active member of the group who drop at least 4 messages in a day.

----
Follow me on [Twitter](https://twitter.com/AdegunleRT)

Let us connect on [LinkedIn](linkedin.com/in/raphael-adegunle-131844182/)










