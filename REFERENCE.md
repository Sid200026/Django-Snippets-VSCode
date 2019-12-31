## All the code snippets are according to Django 3.0.

#### Arguments passed to certain fields take default values so it does not cause any issue.


## Model Snippets

|          **No.**         |   **Snippet**  |           **Function**         |
|:------------------------:|:--------------:|:------------------------------:|
|                          |                |                                |                              
|            1.            |  **modclass**  |        Setup model class       |
|            2.            | **charfield**  |         Model CharField        |
|            3.            |  **intfield**  |         Model IntField         |
|            4.            |  **boolfield** |         Model BoolField        |

#### All other fields and snippet shortcuts are self-explanatory.

## Admin, URLs and Manager Snippets

|          **No.**         |   **Snippet**  |           **Function**         |
|:------------------------:|:--------------:|:------------------------------:|
|            1.            |   **admreg**   |     admin.site.register(..)    |
|            2.            |   **paturl**   |     Setup for urls.py file     |
|            3.            |    **dmnc**    |      Custom Manager Setup      |
|            4.            |   **cmmodel**  |     Custom Manager in Model    |

## Form Snippets

|          **No.**         |   **Snippet**  |           **Function**         |
|:------------------------:|:--------------:|:------------------------------:|
|            1.            |   **formpy**   |          Setup form.py         |
|            2.            |   **fclass**   |         Setup form class       |
|            3.            | **is_valid()** |        Override is_valid()     |
|            4.            |   **modform**  |         Setup modelForm        |

#### Form fields are similar to model fields. However the only difference is we have a f as the starting character of each snippet. So formfield snippet becomes fformfield and so on.

## View Snippets

|          **No.**         |   **Snippet**  |           **Function**           |
|:------------------------:|:--------------:|:--------------------------------:|
|            1.            |   **gencbv**   | Setup a generic class based view |
|            2.            |   **render**   |       Shortcut for render        |
|            3.            |    **htrd**    | Shortcut for HttpResponseRedirect|
|            4.            |    **cltd**    |   Cleaned Data Access for Forms  |
|            5.            |  **custfilt**  |     Template for Custom Filter   |
|            6.            |   **create**   |          *Create* query          |
|            7.            |     **all**    |           *All* query            |
|            8.            |   **filter**   |          *Filter* query          |
|            9.            |     **get**    |           *Get* query            |
|            10.           |   **exclude**  |         *Exclude* query          |
|            11.           |     **goc**    |       *Get or Create* query      |
|            12.           |     **uoc**    |     *Update or Create* query     |
|            13.           |    **count**   |           *Count* query          |
|            11.           |   **latest**   |          *Latest* query          |
|            12.           |  **earliest**  |         *Earliest* query         |
|            13.           |   **genfunc**  |   Setup a generic function view  |
