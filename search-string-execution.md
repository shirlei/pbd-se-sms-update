## Search String Execution

| Database | Search String | Records |
| ----------- | ------------- | ------- |
| IEEE Xplore[^1][^2] | ("Publication Title":"privacy by design") AND ("Publication Title":"software engineering" OR "Publication Title":"software development" OR "Publication Title":"information systems" OR "Publication Title":"requirements engineering") | 0  |
|  | ("Abstract":"privacy by design") AND ("Abstract":"software engineering" OR "Abstract":"software development" OR "Abstract":"information systems" OR "Abstract":"requirements engineering") | 10  |
| | |
| ACM[^2] | [Publication Title: "privacy by design"] AND [[Publication Title: "software engineering"] OR [Publication Title: "software development"] OR [Publication Title: "information systems"] OR [Publication Title: "requirements engineering"]] AND [Publication Date: (01/01/2018 TO 12/31/2021)] | 0|
|  | [Abstract: "privacy by design"] AND [[Abstract: "software engineering"] OR [Abstract: "software development"] OR [Abstract: "information systems"] OR [Abstract: "requirements engineering"]] AND [Publication Date: (01/01/2018 TO 12/31/2021)] | 6 |
| | |
| Scopus | TITLE-ABS-KEY ( {privacy by design}  AND  ( {software engineering}  OR  {software development}  OR  {information systems}  OR  {requirements engineering} ) )  AND  PUBYEAR  $>$  2017  AND  PUBYEAR  $<$  2022  AND  ( LIMIT-TO ( SUBJAREA ,  "COMP" ) ) | 304 | 

[^1]: Year filtering is done manually in the interface, so results were filtered from [2018-2021].

[^2]: Publication title and Abstract are two different searches in the database.
