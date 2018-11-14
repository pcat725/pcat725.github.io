## Welcome to my page on Oracle vs MongoDB Comparison
This repository will be used to contain information on my project comparing MongoDB vs Oracle databases. Such as datafile and code used.

### Oracle Command used to create table

The following command was used to create the table in the Oracle Database.
This command was run through the Toad for Oracle GUI.

```markdown
DROP TABLE SYS.ADDRESS_BOOK CASCADE CONSTRAINTS;

CREATE TABLE SYS.ADDRESS_BOOK
(
  NAME            VARCHAR2(25 BYTE),
  PHONE_NUMBER    VARCHAR2(25 BYTE),
  STREET_ADDRESS  VARCHAR2(50 BYTE),
  CITY            VARCHAR2(50 BYTE),
  ZIP_CODE        VARCHAR2(10 BYTE),
  COUNTRY         VARCHAR2(50 BYTE)
)
```
### Creation of a table in MongoDB
The following was done using the 3T GUI to create a table in the MongoDB Database.
```markdown
-Select the Database for the data to be stored in
-Select the Collection
-Right click the connection and click add collection giving the data set a name
-The data collection is then created.
```

## Data Sets for the insertion
[CVS Dataset for MongoDB](https://github.com/pcat725/pcat725.github.io/blob/master/dataNov-14-2018.csv).
[SQL Dataset for Oracle](https://github.com/pcat725/pcat725.github.io/blob/master/dataNov-14-2018%20(1).sql).


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

You can use the [editor on GitHub](https://github.com/pcat725/pcat725.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pcat725/pcat725.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
