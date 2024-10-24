# Brevera 
# Points to be noted

Database connection is in ./php/database.php,
 cookie file inside cookie folder,
 sql file named iqc_db.sql inside database folder

---
Link to install AWS SDK and Textract for php refer this below link,

Link 1 -> https://docs.aws.amazon.com/sdk-for-php/v3/developer-guide/getting-started_installation.html

Link 2 -> https://docs.aws.amazon.com/textract/latest/dg/setup-awscli-sdk.html
---

###Places for each process

| Process       | Place         |
| ------------- | ------------- |
| Review        | Place 1       | Place Review
| QC            | Place 2       | Place QC
| Rack Organize | Place 3       | Place RO
| Kitting       | Place 4       | Place Kitting
| Rejected      | Place 5       | Item Rejected
| Placed        | Place 6       | Item placed in rack

###Formulas of 3 Different Bins

| Bin Size      | Formula In CM  | Formula In MM |
| ------------- | -------------- | --------------|
|Small          | 58 * 38.5 * 19 | 600*400*200  |
| Medium        | 58 * 39 * 24   | 615*425*250  |
| Large         | 57 * 37 * 33   | 600*400*340  |

###Default value of Item master
quantity_count_method - yes/no
temperature_controlled - yes/no
item_organize_status - Organized/Unorganized

---

###Default value of Rack Matrix
rack_type - Organized/Unorganized
temperature controlled - yes/no


1.) Need a cookie file for api access i have placed that out of this folder
2.) Database sql file is in sql folder


-> Item_Master (QC required)
    0 = new item needs to assign qc
    yes = QC not required
    no = QC required

-> Review Status
    Null = Default
    required
    modified
    avoidable














 

