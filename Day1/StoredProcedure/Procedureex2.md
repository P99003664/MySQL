USE `sqlqueries`;
DROP procedure IF EXISTS `getMovieDetails`;

DELIMITER $$
USE `sqlqueries`$$
CREATE PROCEDURE `getMovieDetails` ()
BEGIN
select * from movie;
END$$

DELIMITER ;

