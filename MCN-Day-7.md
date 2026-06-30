# 🗄️ What is a Data Lake Object (DLO) in Salesforce Data Cloud?

After data enters Data Cloud through a Data Stream, where does it go?

> 👉 **The answer is: Data Lake Objects (DLOs)**

A Data Lake Object (DLO) is where Data Cloud stores ingested source data in its original form. Think of a DLO as the landing zone for your data.

For example, if you're ingesting a CSV file containing subscriber information:
```text
Data Stream (CSV File) ➔ Data Lake Object (DLO)
```
The DLO stores the records as they were received from the source.

❓ Why is this important?
Data Cloud needs a place to store raw data before it can be standardized, mapped, and used for segmentation. That's exactly what DLOs provide.

🛠️ Real-World Example
In an IP Warming implementation, audience records were loaded into Data Cloud using CSV files. Once ingested through a Data Stream, those records were stored in a DLO before being mapped to Data Model Objects (DMOs).

🚀 What DLOs Help With
✅ Store source data

✅ Preserve incoming records

✅ Support data processing and mapping

✅ Act as the foundation for DMOs

⚖️ DLO vs DMO
One common misconception is that DLOs and DMOs are the same. They are not.

🔹 DLO = Stores raw ingested data (Landing Zone)

🔹 DMO = Organizes data into Salesforce's standardized business model (Harmonized Zone)

We'll dive deeper into DMOs in the next post!

💡 Key Takeaway
A Data Lake Object (DLO) is the first storage layer in Data Cloud. It preserves source data and serves as the foundation for building meaningful customer data models.

🏷️ Tags
#Salesforce #DataCloud #MarketingCloudNext #MCN #DLO #DataLakeObject #Customer360 #SalesforceDataCloud

<img width="1024" height="1536" alt="DAY 7 MCN Funderertain Series" src="https://github.com/user-attachments/assets/af3687f9-16c9-4873-8f4e-d55c317e4de1" />
