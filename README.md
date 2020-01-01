# django-snippets README

This project is aimed at providing commonly used code snippets for Django to developers for faster development.

![Django Snippets](./static/django-snippet.gif)

## Features

Code Snippets for Django

1. Model Fields
2. Form Fields
3. Queryset API
4. Class Based View
5. Function Based View
6. User Model

## Snippet Documentation

### All the code snippets are according to Django 3.0.

##### Arguments passed to certain fields take default values so it does not cause any issue.


### Model Snippets

|          **No.**         |   **Snippet**  |           **Function**         |
|:------------------------:|:--------------:|:------------------------------:|
|                          |                |                                |                              
|            1.            |  **modclass**  |        Setup model class       |
|            2.            | **charfield**  |         Model CharField        |
|            3.            |  **intfield**  |         Model IntField         |
|            4.            |  **boolfield** |         Model BoolField        |
|            5.            |  **datefield** |         Model DateField        |
|            6.            |   **dtfield**  |       Model DateTimeField      |
|            7.            |**decimalfield**|        Model DecimalField      |
|            8.            | **emailfield** |         Model EmailField       |
|            9.            | **filefield**  |         Model FileField        |
|            10.           | **imagefield** |         Model ImageField       |
|            11.           | **floatfield** |         Model FloatField       |
|            12.           |  **slugfield** |         Model SlugField        |
|            13.           | **textfield**  |         Model TextField        |
|            14.           |  **timefield** |         Model TimeField        |
|            15.           |  **urlfield**  |          Model URLField        |
|            16.           |   **fkfield**  |     Model ForeignKey Field     |
|            17.           |  **m2mfield**  |     Model ManyToMany Field     |
|            18.           |  **otofield**  |      Model OneToOne Field      |

### Admin, URLs and Manager Snippets

|          **No.**         |   **Snippet**  |           **Function**         |
|:------------------------:|:--------------:|:------------------------------:|
|            1.            |   **admreg**   |     admin.site.register(..)    |
|            2.            |   **paturl**   |     Setup for urls.py file     |
|            3.            |    **dmnc**    |      Custom Manager Setup      |
|            4.            |   **cmmodel**  |     Custom Manager in Model    |

### Form Snippets

|          **No.**         |   **Snippet**   |           **Function**         |
|:------------------------:|:---------------:|:------------------------------:|
|            1.            |   **formpy**    |          Setup form.py         |
|            2.            |   **fclass**    |         Setup form class       |
|            3.            | **is_valid()**  |        Override is_valid()     |
|            4.            |**fchoicefield** |         Form ChoiceField       |
|            5.            |  **fmcfield**   |    Form MultipleChoiceField    |
|            6.            | **fcharfield**  |          Form CharField        |
|            6.            | **fintfield**   |          Form IntField         |
|            7.            | **fboolfield**  |          Form BoolField        |
|            8.            | **fdatefield**  |          Form DateField        |
|            9.            |  **fdtfield**   |        Form DateTimeField      |
|            10.           |**fdecimalfield**|         Form DecimalField      |
|            11.           | **femailfield** |          Form EmailField       |
|            12.           | **ffilefield**  |          Form FileField        |
|            13.           | **ffloatfield** |          Form FloatField       |
|            14.           | **fimagefield** |          Form ImageField       |
|            15.           |  **fslugfield** |          Form SlugField        |
|            16.           |  **ftimefield** |          Form TimeField        |
|            15.           |  **furlfield**  |           Form URLField        |

##### Form field snippet shorcut are similar to model fields shortcuts. However the only difference is we have a `f` as the starting character of each snippet


### View Snippets

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

### User Model Snippets

|          **No.**         |   **Snippet**            |           **Function**           |
|:------------------------:|:------------------------:|:--------------------------------:|
|            1.            |      **createuser**      |    Create a new user instance    |
|            2.            |   **validatepassword**   |     Validate a given password    |
|            3.            |     **setpassword**      |         Set a new password       |
|            4.            |       **authuser**       |        Authenticate a user       |
|            5.            |       **checkauth**      |  Check if a user is authenticate |

## Known Issues

Currently no issue has been reported. All issues must be reported at 

[Issues](https://github.com/Sid200026/Django-Snippets-VSCode/issues)

## Current Release

### 0.0.3
#### Initial Release of the django-snippets extension

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
