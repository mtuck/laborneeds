# laborneeds


**Will we import from shopertrack to LastSixWeeks Traffic?**
  * Will we run ssis job to do this?
  
  
**What does line # mean in PercentOfDaily total?**


**Do we need to add foreign key to PercentofDailyTotal and WeeklyTotal**
  * Right now they only contain one week
  * Maybe key to relate to day in backup_lastSixWeeks
  
**Does current application actual calculate what the last six week are?**
   * Or does it just read the entire LastSixWeeks table.
   * I am assuming we will be storing more than just the last six weeks
  
