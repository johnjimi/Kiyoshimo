Clear existing tables:

DELETE FROM Ages;
INSERT INTO Ages (name, age) VALUES ('Brayden', 24);
INSERT INTO Ages (name, age) VALUES ('Kahlen', 14);
INSERT INTO Ages (name, age) VALUES ('Nikos', 32);
INSERT INTO Ages (name, age) VALUES ('Arandeep', 17);
INSERT INTO Ages (name, age) VALUES ('Armen', 21);
INSERT INTO Ages (name, age) VALUES ('Lorna', 33);

Then SQL command:

SELECT hex(name || age) AS X FROM Ages ORDER BY X

find the hex first of the list
