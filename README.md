# epa-echo-atf
Environmental Compliance Records for Firearms Manufacturers
Steps to reproduce

1) Use firearms manufacturing aggregate dataset, and calculate manufacturing totals for 2000-2019
Jordan, Lisa; Elessawy, Marwa; Munro-Ludders, Graham; Jordan, Jason (2022), “U.S. Annual Firearms Manufacturing and Export Report: Aggregate Time Series Dataset 2000-2020”, Mendeley Data, V2, doi: 10.17632/gmz374n75n.2
2) Sort by totals, descending.
3) Search EPA ECHO by facility to identify FRS ID values for each (URL: https://echo.epa.gov/).
4) Download EPA ECHO records for facilities, and include in your request the attributes for Latitude and Longitude, TRI totals and People of Color within 3 miles of facility.
5) Link EPA ECHO records to ATF AFMER totals, and RDS key to create one aggregate database.
6) Sort by People of Color, descending.
Note: EPA ECHO is routinely updated with more recent TRI summaries, compliance characteristics, and demographic data.  The reproduction steps will create to an updated dataset.
