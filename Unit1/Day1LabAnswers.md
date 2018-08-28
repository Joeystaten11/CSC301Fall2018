# Day 1 lab answers

* Create a new **pets** table. 
```sql
CREATE TABLE `pets` (
  `petNum` int(11) NOT NULL PRIMARY KEY,
  `petName` varchar(30) NOT NULL,
  `birthdate` date DEFAULT NULL,
  `petType` enum('cat','chicken','dog','fish','reptile') NOT NULL,
  `ownerFirst` varchar(30) NOT NULL,
  `ownerLast` varchar(30) NOT NULL,
  `sex` enum('m','f','unknown') DEFAULT NULL,
  `lastVisitDate` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP,
  `notes` text
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```
* Add some Pets to the table. 
Here are a few sample INSERT statements:
```sql
INSERT INTO `pets` (`petNum`, `petName`, `birthdate`, `petType`, `ownerFirst`, `ownerLast`, `sex`, `lastVisitDate`, `notes`) VALUES
(1, 'Suzie', '2017-09-03', 'cat', 'Tom', 'Jones', 'f', '2017-09-03 12:58:56', NULL),
(2, 'Murphy', '2017-09-04', 'dog', 'Sally', 'Smith', 'f', '2017-09-03 12:59:25', 'nothing much to say about this pet.'),
(3, 'PiedPiper', NULL, 'fish', 'Dinesh', 'Gilfoyle', 'unknown', '2017-09-03 13:00:14', NULL),
(4, 'Funny Beak', NULL, 'chicken', 'Kurt', 'Cobain', 'unknown', '2017-08-10 14:45:16', NULL);
```
* Modify the pets you added. 
```sql
UPDATE `pets` SET `sex` = 'm' WHERE `pets`.`petNum` = 4;
```
* Modify your table to show the option of a deceased pet; update one of the pets to use this column. 
```sql
ALTER TABLE `pets` ADD `isDeceased` BOOLEAN NOT NULL DEFAULT FALSE AFTER `sex`;
UPDATE `pets` SET `isDeceased` = '1' WHERE `pets`.`petNum` = 3;
```
