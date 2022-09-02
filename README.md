# WHATSAPP GROUP DATA ANALYSIS

![Icon](https://github.com/Mr-Art-coder/Whatsapp-Data-Analysis/blob/main/Charts/Whatsapp.jpg)

----
# PROBLEM STATEMENT

The intellectual Traditionist WhatsApp platform comprises all comrades who belong to a union group name Tradition in University. It was discovered that females do not participate often in the platform, they do not drop messages or join in discussions and debates, and if they do, it is only to comment or react to a message. This analysis was carried out to know the reason behind this, to discover how many messages were dropped by the female in the group, why the message was low, why they did not participate in discussions and what is the way out.

----

# DATA SOURCE

![Group Icon](https://github.com/Mr-Art-coder/Whatsapp-Data-Analysis/blob/main/Charts/group.jpg)

The dataset used for this analysis was gotten from the chat exported from the Intellectual Traditionist WhatsApp platform. All media were included.

----

# DATA TRANSFORMATION

![Transformation](https://github.com/Mr-Art-coder/Whatsapp-Data-Analysis/blob/main/Charts/PowerQuery.JPG)

After the exportation of the chats, all the data were together in a column. I opened the data in Microsoft Excel and study the single column to know how the data will be regrouped. After understanding the dataset’s arrangement, I imported the txt file into Power BI power query where I did all the wrangling. I added 5 new columns from the original single column. I separated the Year, Time, User, and Message into these five columns. Being a txt file, some messages spilled over to another row, because of this, new columns were added from the Year column, the columns are Day and Month. Because of the spilled messages, some rows in the Month column that does not contain number showed error, so these rows were removed, and the spilled message was also removed from other rows automatically. The four months came in number (5,6,7,8), but they were replaced with text (May, June, July, and August) for easy comprehension. To remove some unwanted data, all the columns were filtered. For example, in the username column, some data which include (someone who was added, someone who left, and the verification number of someone who has changed) were filtered out.

To differentiate Male from females, I went to the group and check individuals’ profiles and used conditional statements, nested IFs, to do the transformation e.g. (if [User]= “+234……” then “Male” else if, etc.).

To avoid Personally Identifiable Information (PII), data anonymization was introduced to keep the privacy of the group members. The dataset showcased their phone numbers, but lines of code were written in DAX in other to change the numbers to names. (If [User]="+2349067751244" then "Raphael" else if...) Nested If function. I went through this de-identification in other to wipe the data clean of all personally identifying information.
This work took me 7 days, one day was used to generate, and exported the dataset used, 5 days were used for data wrangling and research, 1 day was used for analysis, and the last day was used for visualization and documentation. The dataset used as sampling was between a certain timeframe, May to August 2022.


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

![Dashboard](https://github.com/Mr-Art-coder/Whatsapp-Data-Analysis/blob/main/Charts/Tradition%20Dataset.png)

I exported the charts of the group and analyze the data, after data wrangling and visualization, I discovered the total messages of the group and saw that most of the messages that were dropped in the group are from the male. I asked the question Why?

The digging continued, I used a donut chart to visualize the topic used mostly in the group, and I discovered that most of the topics discussed in the group were based on either politics or sport. I was not satisfied, why didn't females participate?
I went online and used different search engines, I discovered that ladies’ interest lies majorly in Fashion and entertainment, only a few ladies will be found at the spot where football or politics is discussed.

Then, how are we going to solve this problem? I projected to the group to always introduce entertainment and fashion or gossip gist into their discussion.
The group members acted on my prescriptions and lo and behold, ladies are not left behind again. Fairness was restored

----

## REASONS WHY LADIES HAVE LOW TURNOUT

1. The main topics discussed in the group based on POLITICS and SPORT.
2. Male is much more than female by 78 percent to 22 percent differences.
3. Females are not part of the administrators of the group.

----

## RECOMMENDATION

1. Ladies find interest in FASHION and ENTERTAINMENT or GOSSIP, these should be introduced to the platform as only a few females can be found at the spot where SPORT or POLITICS is discussed.
2. The platform has very low females, and this also affects the number of messages coming from the gender. To avoid gender bias, the platform should work on recruiting more ladies to the association, this will bridge the gap of discrimination.
3. The group has 6 admins who were all male, the members should try to make at least 2 females admin of the platform, this will also boost the morale of the other gender.


----
Follow me on [Twitter](https://twitter.com/AdegunleRT)

Let us connect on [LinkedIn](linkedin.com/in/raphael-adegunle-131844182/)










