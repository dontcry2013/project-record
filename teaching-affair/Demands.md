Version 2
1, make sure the user has the permission to access the specific page
2, teachingBranchCalendar jumps to the arrangement page directly
3, filter records according to cohort, teacher, and classroom, to generate separate page and excel
4, optimize export excel function, assign color and border style to the excel cell
5, adjust curriculum schedule by TV or ASP's change
6, classification, show classrooms by select building, section firstly
7, statistics 

code improvement
* make enddate available in arrange page
* impove code quality
* debug
* vue component usage



完成：
1, 2, 3
thinking about use vue component to generate a reusable code in cohort and classroom part

app/Config/core.php	

app/View/Themed/Officer/Elements/sidebar.php	

app/View/Elements/addDocumentChecklist.ctp

