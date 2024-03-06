This is a sample static website designed using PHP as the server-side language.
Templete can be used for free
It features signup, login and dashboard page 


CEREATE DB with SQL below;
CREATE TABLE adminlogin (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    username VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL,
    password VARCHAR(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1 COLLATE=latin1_swedish_ci;