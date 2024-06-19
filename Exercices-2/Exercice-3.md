CREATE DATABASE formation;
USE formation;

CREATE TABLE stagiaire ( id INT AUTO_INCREMENT PRIMARY KEY, nom VARCHAR(255) NOT NULL, prenom VARCHAR(255) NOT NULL, date_naissance DATE NOT NULL, email VARCHAR(255) NOT NULL );

ALTER TABLE stagiaire ADD telephone VARCHAR(255);

ALTER TABLE stagiaire ADD UNIQUE (email);

