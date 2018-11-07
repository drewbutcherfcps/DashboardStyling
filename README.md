Go to https://azdemo.hoonuit.com/Dashboard/ 
1. Example of Level 4 Navigation (see Essentials > District > Summary)
![before](https://github.com/drewbutcherfcps/DashboardStyling/blob/master/Level%204%20Navigation%20Before.png)
![after](https://github.com/drewbutcherfcps/DashboardStyling/blob/master/Level%204%20Navigation%20After.png)
```CSS
/* Start Level 4 Dropdown Styling */
.nav-item.dropdown  {
     position: relative;
}

.dropdown-menu.override-dropdown.flatten-that-ish {
     top: 34px;
}
```
2. Example of Table (see Essentials > Enrollment > Programs)
![before](https://github.com/drewbutcherfcps/DashboardStyling/blob/master/Table%20Before.png)
![after](https://github.com/drewbutcherfcps/DashboardStyling/blob/master/Table%20After.png)
```CSS
/* Table Stlying */

  /* Resetting Table column widths */
  div.th-inner-header {
       width: initial !important;  
  }


  /* Table flashing between rows */
  tbody > tr:nth-of-type(2n) {
       background-color: rgba(10,36,50,.05) !important;
  }
  tbody > tr:nth-of-type(2n+1) {
       background-color: #fff !important;
  }
  

  /* Remove extra right border in last element of heading */
  thead > tr > th:last-child > div.th-inner-header {
       border-right: 0px !important;
  }
```
On the Dashboard navigate to ***Site Administration > Services > Dashboard*** Services and click Edit

In the field Page Disclaimer under Disclaimer Setting add a link tag to your custom CSS file.  

