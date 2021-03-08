USE `sqlqueries`;</br>
DROP procedure IF EXISTS `getProductionDetails`;</br>
DELIMITER $$</br>
USE `sqlqueries`$$</br>
CREATE PROCEDURE `getProductionDetails` ()</br>
BEGIN</br>
select * from Productions;</br>
END$$</br>
DELIMITER ;

