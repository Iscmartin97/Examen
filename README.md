
 MySQL  localhost:3306 ssl  SQL > use sakila;
Default schema set to `sakila`
Fetching table and column names from `sakila` for auto-completion... Press ^C to stop.

 MySQL  localhost:3306 ssl  sakila  SQL > select a.actor_id, a.first_name, a.last_name, sum(e.amount) as total from actor a inner join
film_actor b on a.actor_id = b.actor_id 
inner join inventory c on c.film_id = b.film_id

SELECT actor.actor_id,actor.first_name,actor.last_name SUM rental FROM actor,rental
WHERE actor.actor_id = film_actor_actor_id

