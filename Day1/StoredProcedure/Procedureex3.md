USE `sqlqueries`;</br>
DROP procedure IF EXISTS `getAddress`;</br>
USE `sqlqueries`;</br>
DROP procedure IF EXISTS `sqlqueries`.`getAddress`;</br>
DELIMITER $$</br>
USE `sqlqueries`$$</br>
CREATE DEFINER=`root`@`localhost` PROCEDURE `getAddress`()</br>
BEGIN</br>
select * from productions where Address="Bangalore";</br>
END$$</br>
DELIMITER ;

