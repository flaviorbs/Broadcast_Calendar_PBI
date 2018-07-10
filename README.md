# Broadcast_Calendar_PBI
Broadcast Calendar Code in M (Power Query) and DAX

Working on TV I'm constantly building reports and dashboards in Power BI / Power Pivot using Ratings, Media Planning and Ad Sales datasets.

One common issue in this industry is the way calendar works. Broadcast Calendar has a few simple rules:
1.	Every week starts on Monday and ends on Sunday
2.	Every month has only full weeks, thus a month can have either 28 or 35 days
3.	The week in which the 1st day of the month (Gregorian Calendar) falls is the first week of the month. Therefore, if 1st of May is a Wednesday, for Broadcast Industry May actually started on April 29, the first Monday before May 1st. In this same example, Mays's last day is the 26, which is the last Sunday before June 1st.
