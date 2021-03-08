USE `sqlqueries`;</br>
DROP procedure IF EXISTS `getMovieDetails`;</br>
DELIMITER $$</br>
USE `sqlqueries`$$</br>
CREATE PROCEDURE `getMovieDetails` ()</br>
BEGIN</br>
select * from movie;</br>
END$$</br>
DELIMITER ;</br>

