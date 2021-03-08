USE `sqlqueries`;
DROP procedure IF EXISTS `getProductionDetails`;

DELIMITER $$
USE `sqlqueries`$$
CREATE PROCEDURE `getProductionDetails` ()
BEGIN
select * from Productions;
END$$

DELIMITER ;

