# laborneeds


**Will we import from shopertrack to LastSixWeeks Traffic?**
  * Will we run ssis job to do this?
  * Will minimize api calls
    * is there a limit on api calls
  
  
**What does line # mean in PercentOfDaily total?**
  * looks like the hour ordering by day.


**Do we need to add foreign key to PercentofDailyTotal and WeeklyTotal**
  * Right now they only contain one week
  * Maybe key to relate to day in backup_lastSixWeeks
  
**Does current application actual calculate what the last six week are?**
   * Or does it just read the entire LastSixWeeks table.
   * I am assuming we will be storing more than just the last six weeks
   * Should we rename Table?
   
**Is current application doing PercentOfDailyTotal and weekly calculations or is it just reading from table?** 
  
**Should we store more than one week in percentOfDaily and weekly total?**
   * we would need to add week id field 
   
**Are we using percent of daily total?**
   
