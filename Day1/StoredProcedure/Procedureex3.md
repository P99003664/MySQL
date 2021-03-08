USE `sqlqueries`;
DROP procedure IF EXISTS `getAddress`;

USE `sqlqueries`;
DROP procedure IF EXISTS `sqlqueries`.`getAddress`;
;

DELIMITER $$
USE `sqlqueries`$$
CREATE DEFINER=`root`@`localhost` PROCEDURE `getAddress`()
BEGIN
select * from productions where Address="Bangalore";
END$$

DELIMITER ;
;

