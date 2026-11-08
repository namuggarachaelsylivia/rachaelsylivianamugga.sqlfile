/* Create a table called Cultural_states with the following columns:state, state abbreviation, 
-- capital, slogan, date created, geopolitical zone, number of local government, governor's political party */

CREATE TABLE Cultural_states (
  					state VARCHAR(20), 
  					state_abbreviation CHAR(8),
  					capital VARCHAR(225),
  					slogan TEXT,
  					date_created DATE,
  					geopolitical_zone VARCHAR(20),
  					number_of_local_government VARCHAR(225),
  					governors_political_party VARCHAR(200)
  							   );

-- insert records into the new created table
INSERT into Cultural_states (state, state_abbreviation, capital, slogan, date_created, geopolitical_zone, number_of_local_government, governors_political_party)
VALUES ('Jigawa', 'JIG', 'Duste', 'Liberal state', '1991-08-27', 'North West', '27','APC'),
	   ('Delta', 'DEL', 'Asaba', 'The Big Heart', '1991-08-27', 'South West', '25', 'APC'),
       ('Yobe', 'YOB', 'Damaturu', 'The Young Shall Grow', '1991-08-27', 'North East', '17', 'APC'),
       ('Zamfara', 'ZAM', 'Gusau', 'Home of Agricultural Products', '1976-02-03', 'North West', '14', 'APC'),
       ('Ebonyi', 'EBO', 'Abakaliki', 'Salt of the Nation', '1996-10-01', 'South East', '13', 'APC'),
       ('Gombe', 'GOM', 'Gombe', 'Land of Hope', '1996-10-01', 'North East', '11', 'APC'),
       ('Akwa-Ibom', 'AKW', 'UYO', 'Home of All', '1987-09-23', 'South West', '31', 'APC'),
       ('Taraba', 'TAR', 'Jaringo', 'Natures Gift to the Nation', '1992-08-01', 'North East', '17', 'APC');
       
-- See the newly added records table
SELECT *
FROM Cultural_states;
       
-- Update slogan of Jigawa State
UPDATE Cultural_states
SET slogan = 'The New World'
WHERE capital = 'Duste';
       
-- Update slogan of Yobe State
UPDATE Cultural_states
SET slogan = 'Pride of the Sahel'
WHERE capital = 'Damaturu';                        

-- Update slogan of Akwa-Ibom State
UPDATE Cultural_states
SET slogan = 'Land of Promise'
WHERE capital = 'Uyo'; 

-- Update slogan of Zamfara State
UPDATE Cultural_states
SET slogan = 'Farming is our Pride'
WHERE capital = 'Gusau'; 

-- Update slogan of Gombe State
UPDATE Cultural_states
SET slogan = 'Jewel of Savannah'
WHERE capital = 'Gombe';   

-- Lets see our newly edited table
SELECT *
FROM Cultural_states;

 /* Alter the Cultural State table by adding a new column
 (name of the current governor) .
 Then add the following records to the previously existing data */
 ALTER TABLE Cultural_states
 ADD COLUMN name_of_the_curr_gov INT;
 
 -- Lets see the new table
SELECT *
FROM Cultural_states;

INSERT into Cultural_states (state, state_abbreviation, capital, slogan, date_created, geopolitical_zone, number_of_local_government, governors_political_party)
VALUES ('Sokoto', 'SOK', 'Sokoto', 'Seat of the Caliphate', '1976-02-03', 'North West', '23', 'APC'),
	   ('Niger', 'NIG', 'Minna', 'The Power State', '1976-02-03', 'North Central', '25', 'APC');

-- Lets see the new table
SELECT *
FROM Cultural_states;



                             
                         
 
